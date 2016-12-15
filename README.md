## Git Pre-Reqs
### Powershell
* `Set-ExecutionPolicy RemoteSigned`

### Chocolatey
* `iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex`

### Install Packages
* `choco install git`
* `choco install visualstudiocode`
* `choco install poshgit`

### Git from the command line
~~~~
git init
git pull https://cva.stuartgalloway.xyz/gallows/git-install.git
git add .
git config --global user.name "Stuart Galloway"
git config --global user.email "stuart.galloway@computacenter.com"
git commit -m "1st Commit"
git remote add origin https://cva.stuartgalloway.xyz/gallows/git-install.git
git add .
git commit -m "2nd Commit"
git push origin master
~~~~

### Git from VisualStudio Code
* Open Folder
* Edit File
* Save
* Use Git Button, enter commit, sync"# testapp" 
