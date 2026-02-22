```bash
winget install Kubernetes.kubectl
winget install Helm.Helm
winget install Microsoft.Powershell
winget install Git.Git
winget install Microsoft.DotNet.SDK.8
winget install Microsoft.DotNet.SDK.9
winget install Microsoft.DotNet.SDK.10
winget install Microsoft.VisualStudioCode
winget install Docker.DockerDesktop
winget install Microsoft.DevProxy
winget install Starship.Starship
winget install OpenJS.NodeJS
winget install Hashicorp.Terraform
winget install jqlang.jq

# Instalar credentials manager
iex "& { $(irm https://aka.ms/install-artifacts-credprovider.ps1) }"

# Habilitar wsl
wsl.exe --install

# Setup starship, Add the following to the end of your PowerShell configuration (find it by running $PROFILE):
Invoke-Expression (&starship init powershell)
```
