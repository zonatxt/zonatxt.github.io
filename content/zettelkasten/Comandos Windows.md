---
title: Comandos Windows
date: 2024-01-28
tags:
  - programa
---
###### Create User
```powershell
net user username /add
```

###### Fix corrupt NTFS
```bash
sudo ntfsfix -b -d /dev/disk
```

###### Create Symbolic Link
``` powershell
mklink /J "C:\Users\User\AppData" "H:\AppData"
```

###### Limpar AutoStart Windows
```
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run
HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Run
```
