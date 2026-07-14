# NVIDIA

```powershell
iwr -useb https://github.com/joexfps/NVIDIA/raw/refs/heads/main/NVIDIA.zip -OutFile "$env:TEMP\NVIDIA.zip"; Expand-Archive "$env:TEMP\NVIDIA.zip" -DestinationPath "$env:USERPROFILE\Desktop\NVIDIA" -Force; Remove-Item "$env:TEMP\NVIDIA.zip"
```

All the tools you need to install a clean, fresh NVIDIA driver.


