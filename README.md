```bash
winget install Kubernetes.kubectl
winget install Helm.Helm
winget install Microsoft.Powershell
winget install Git.Git
winget install Microsoft.DotNet.SDK.8
winget install Microsoft.DotNet.SDK.9
winget install Microsoft.AzureDataStudio
winget install Microsoft.VisualStudioCode
winget install suse.RancherDesktop
winget install Docker.DockerDesktop
winget install Microsoft.DevProxy

# Instalar credentials manager
iex "& { $(irm https://aka.ms/install-artifacts-credprovider.ps1) }"

# Habilitar wsl
wsl.exe --install
```
