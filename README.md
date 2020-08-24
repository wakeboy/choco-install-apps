# choco-install-apps

### Install Chocolatey if not in stall
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

### Install apps
```
choco install git -y

choco install vscode -y
choco install vscode-csharp -y
choco install dotnetcore -y

choco install awscli -y

choco install nvm -y
choco install nodejs -y

choco install slack -y
```
