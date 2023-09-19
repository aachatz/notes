---
id: dtou3dxq3ne836q9hpv2el0
title: Minizinc
desc: ''
updated: 1695103236776
created: 1695103236776
---


```json
{
    "version": "2.7.6",
    "license": "unknown",
    "url": "https://github.com/MiniZinc/MiniZincIDE/releases/download/2.7.6/MiniZincIDE-2.7.6-bundled-setup-win64.exe#/mz.exe",
    "homepage": "https://www.minizinc.org",
    "hash": "7b251be641cd78f3da3389f91c5541f2c874f4d7afa6b0a50190351d6fcc39aa",
    "bin": "minizincide.exe",
    "installer": {
    
        "args": [
            "/VERYSILENT",
            "/CURRENTUSER",
            "/DIR=$dir"
        ]
    },

    "checkver": {
        "url": "https://www.minizinc.org/software.html",
        "regex": "MiniZinc ([\\d\\.]+)"
    },
    "autoupdate": {
        "url": "https://github.com/MiniZinc/MiniZincIDE/releases/download/$version/MiniZincIDE-$version-bundled-setup-win64.exe"
    }

}
```