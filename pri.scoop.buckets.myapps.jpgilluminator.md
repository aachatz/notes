---
id: 6ws8if3u1pnd2nj8vgc8izz
title: Jpgilluminator
desc: ''
updated: 1695103142349
created: 1695103099427
---



```json
{
    "version": "5.4.0.5",
    "description": "Programm zum verbessern von jpg Bildern",
    "homepage": "https://www.jpg-illuminator.de",
    "license": "Unknown",
    "url": "https://www.jpg-illuminator.de/downloads/JPG-Illuminator-x64_v54.zip",
    "extract_dir": "JPG-Illuminator-x64",
    "hash": "2a748058a8d1c60f260c54b75a98539e0d5eb89d7674698b17f26aa1ecfde19d",
    "bin": "jpgIlluminator.exe",
    "shortcuts": [
        [
            "jpgIlluminator.exe",
            "JPG-Illuminator"
        ]
    ],
    "checkver": {
        "url": "https://www.jpg-illuminator.de/download.htm",
        "regex": "Programm-Version ([\\d\\.]+)"
    },
    "autoupdate": {
        "url": "https://www.jpg-illuminator.de/downloads/JPG-Illuminator-x64_v$majorVersion$minorVersion.zip",
        "hash": {
            "url": "$url.sha256"
        }
    }
}
```