1. Install `Azure Developer CLI` run `Invoke-WebRequest -Uri https://aka.ms/installazurecliwindows -OutFile .\AzureCLI.msi; Start-Process msiexec.exe -Wait -ArgumentList '/I AzureCLI.msi /quiet'; rm .\AzureCLI.msi"`
2. Run `azd init` to initialize Azure Developer - On separate terminal not project terminal
3. Login to azure account using `azd auth login`
4. Run `azd up`
