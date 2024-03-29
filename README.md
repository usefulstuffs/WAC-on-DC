> A wannabe Microsoft MVP -> [@shiroinekotfs](https://github.com/shiroinekotfs)

# Windows Admin Center on Domain Controller

![image](https://github.com/shiroinekotfs/WAC-on-DC/assets/115929530/39b27ad8-bf3b-4691-9603-4934de2d4268)

## Getting started

You, first, install Windows Admin Center (Preview). If you don't have, [download it here](https://www.microsoft.com/en-us/software-download/windowsinsiderpreviewserver)

Once downloaded and installed (please ignore all warnings and errors), move your Powershell current directory into this repo folder, and try this command:

```powershell
Import-Module .\Microsoft.WindowsAdminCenter.Configuration.psm1
Enable-WACPSRemoting
Register-WACLocalCredSSP
```

Once it is done, you can try WAC on DC!

## Patched stable versions

Stable Windows Admin Center with patchs for installation on Domain Controller can be access from [here](https://github.com/usefulstuffs/WAC-on-DC/releases).
