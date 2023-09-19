---
id: o74nl4naf2huytul33b9oq1
title: Buckets
desc: ''
updated: 1695126194225
created: 1695101354296
---

# Installation scripts for scoop

## Installation mit Angabe des Verzeichnisses
```powershell
$env:SCOOP='c:\Users\aachatz\scoop'
[environment]::setEnvironmentVariable('SCOOP',$env:SCOOP,'User')
iwr -useb get.scoop.sh | iex
```

## Installation
```powershell
iwr -useb get.scoop.sh | iex
```

## Bei Problemen
```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
```

## Weitere Info - Quickstart
https://github.com/lukesampson/scoop/wiki/Quick-Start


## checkver_manifest

```powershell
C:\Users\Anton Achatz\scoop\buckets\main> .\bin\checkver.ps1 ..\myapps\*
```

## export app names to scoop-apps.txt
```powershell
(scoop export) | sls '^([\w-]+)' |% { $_.matches.groups[1].value } > scoop-apps.txt
```

## install apps from scoop-apps.txt
```powershell
$apps = gc c:/users/aachatz/Nextcloud/PRIVAT/Scoop/scoop-apps.txt
scoop install @apps
```

## hashwert ermitteln
```powershell
certutil -hashfile "C:\temp\test.txt" sha256
```

## install myapps
```powershell
 scoop bucket add myapps https://github.com/aachatz/myapps.git
```

