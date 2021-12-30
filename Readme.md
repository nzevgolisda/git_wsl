generate SSH key, add it to appdata/gitKraken
https://www.microsoft.com/en-us/p/ubuntu/9nblggh4msv6?activetab=pivot:overviewtab
wsl --install -d Ubuntu (as administrator)
wsl --install -d Ubuntu 20.04 LTS(as administrator)
wsl --install -d Ubuntu 18.04 LTS(as administrator)
connect github/gitKraken/vscode
restart
wsl --install
enable wsl (as administrator) through 
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

https://aka.ms/wsl2kernel (Download the Linux kernel update package)
https://github.com/microsoft/WSL/issues/5393
vs code / remote explorer / 
unix name / password
sudo apt update && sudo apt upgrade
https://docs.microsoft.com/en-us/windows/wsl/setup/environment



wsl -l -v
wsl -t Ubuntu
wsl --shutdown