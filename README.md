# ksp-unity-tools

## Introduction
This package is a UPM compatible package providing a tweaked version of KSP's PartTools, combined with the required TextMesh Pro DLLs.

I'm not completely sure of the distribution terms for Part Tools - after hunting around everywhere, I can't find any license or terms and conditions. I'm assuming since the download is freely available, that while reverse engineering or modifying the binaries (DLLs) is not allowed, it is legal to repackage the files into a git repository with the appropriate metadata to make it work as a Unity Package.

## Installing

Installing this package is pretty simple;

 1. Create a new unity project, or open an existing one.
 2. Open the Package Manager, and make sure that TextMesh Pro is *not* installed.
 3. Edit the packages/manifest.json, and add a new entry to the "dependencies":
```
    "com.luciddan.ksp.parttools": "https://github.com/LucidDan/ksp-unity-tools.git#191.1.3",
```

## Support

If you have an issue with the package itself, [log an issue](https://github.com/LucidDan/ksp-unity-tools/issues). Any issues regarding Part Tools should be asked at the [KSP Forums](https://forum.kerbalspaceprogram.com/).


