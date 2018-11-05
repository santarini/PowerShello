Set-Location C:\Users\santa

$Shell = $Host.UI.RawUI
$Shell.WindowTitle="Makoa Systems Shell"


$host.ui.rawui.ForegroundColor = "White"
#$host.ui.rawui.BackgroundColor = <ConsoleColor>
#$Host.PrivateData.ErrorForegroundColor = <ConsoleColor>
#$Host.PrivateData.ErrorBackgroundColor = <ConsoleColor>
#$Host.PrivateData.WarningForegroundColor = <ConsoleColor>
#$Host.PrivateData.WarningBackgroundColor = <ConsoleColor>
#$Host.PrivateData.DebugForegroundColor = <ConsoleColor>
#$Host.PrivateData.DebugBackgroundColor = <ConsoleColor>
#$Host.PrivateData.VerboseForegroundColor = <ConsoleColor>
#$Host.PrivateData.VerboseBackgroundColor = <ConsoleColor>
#$Host.PrivateData.ProgressForegroundColor = <ConsoleColor>
#$Host.PrivateData.ProgressBackgroundColor = <ConsoleColor>

$options = Get-PSReadlineOption
$options.CommandForegroundColor = 'Magenta'

function djangoPath { cd "C:\Users\santa\OneDrive\DjangoForBegin" }

function djangoPreview { start "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe":http://127.0.0.1:8000 }

function chromeSearch($SearchTerm){ start "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe":"www.google.com/search?q="$SearchTerm}

Set-alias vim "C:\Program Files (x86)\Vim\vim81\vim.exe"

Set-alias vi "C:\Program Files (x86)\Vim\vim81\vim.exe"
