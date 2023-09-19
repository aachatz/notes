---
id: 8m999m8k04nc7iyke5c1cit
title: Birt
desc: ''
updated: 1695146063761
created: 1695103157659
---


```json
{
    "version": "4.13.0-20230302",
    "description": "Tool for creating reports",
    "homepage": "https://sourceforge.net/projects/opensourcebirtreportdesigner//",
    "license": "Unknown",
    "url": "https://download.eclipse.org/birt/updates/release/4.13.0/downloads/birt-report-designer-all-in-one-4.13.0-20230302-win32.win32.x86_64.zip",
    "extract_dir": "eclipse",
    "hash": "sha512:fbb289dc928d0b9a1239097e1b73116eae093b15eceeee2b53601aef297ffa695633996013e5aa6cecbd0d8ae243aaf1cef016eab686df4494d604bba17ce62a",
    "shortcuts": [
        [
            "birt.exe",
            "Birt Designer"
        ]
    ],
    "checkver": {
        "url": "https://download.eclipse.org/birt/updates/release/latest",
        "regex": "birt-report-designer-all-in-one-(([\\d\\.]+)-(\\d+))-win32.win32.x86_64.zip"
    },
    "autoupdate": {
        "url": "https://download.eclipse.org/birt/updates/release/$matchHead/downloads/birt-report-designer-all-in-one-$version-win32.win32.x86_64.zip",
        "hash": {
            "url": "$url.sha512"
        }
    }
}
```