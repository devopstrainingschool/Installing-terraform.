# Installing-terraform.
## On mac OS
```
brew tap hashicorp/tap
```
```
brew install hashicorp/tap/terraform
```
```
brew update
```
```
 brew upgrade hashicorp/tap/terraform
 ```
 
 
 ## On Linux centos
 ```
 sudo yum install -y yum-utils
 ```
 ```
 sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo
 ```
 ```
 sudo yum -y install terraform
 ```
 ## On Windows 10 and 11
 ### Install choco first
 #### With Powershell
 ```
 Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
 ```
 #### With CMD terminal
 ```
 @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
 ```
 ### Now install terraform
 ```
 choco install terraform
 ```
