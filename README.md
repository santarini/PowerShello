### PowerShell

###### Find Powershell Version

`$PSVersionTable`

###### Print working dir

`pwd`

###### List files in pwd

`dir`

`ls`

###### Clear shell

`clear`

###### Comments

`# I'm a comment` 

###### Go to Home Directory

`cd ~`

###### Launch browser go to URL

`start "C:\Program Files\Mozilla Firefox\firefox.exe":www.google.com` # firefox doesn't navigate to url

`start "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe":www.google.com`

###### Open path in notepad

`notepad \Item\path.txt`

###### Open Explorer at Current Path

`explorer .`

`Invoke-Item .`

`ii .`

###### Make Directory

`mkdir`

`echo >> \Item\path.txt`

###### Copy Directory or file

`copy \Item\Startpath.txt \Item\Finishpath.txt`

`cp \Item\Startpath.txt \Item\Finishpath.txt`

###### Move or Rename Directory or file

`move \Item\Startpath.txt \Item\Finishpath.txt`

`mv \Item\Startpath.txt \Item\Finishpath.txt`

###### Input history

`h`

###### Current Directory Tree

`tree /f`

###### Remove file or folder

`Remove-Item \Item\path.txt -force -recurse`

###### View all aliases

`Get-Alias`

###### View custom profile path

`$profile`

###### Enable scripting (includes loading custom profilesS)

`Set-ExecutionPolicy RemoteSigned`

###### Find all .txt files in directory and subdirectories

`Get-ChildItem -Path *.txt -Recurse -Force`

###### Close PowerShell

`exit`

### vim

`vim \Item\path.txt`

`:qw`

`:q!`

ESC

I
