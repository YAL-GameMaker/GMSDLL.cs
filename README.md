# GMSDLL

This is a "template" project for creating C# DLLs for GameMaker!

Intended to be copied via [copyre](https://github.com/YAL-Haxe/copyre), like
```
copyre GMSDLL.cs MyExtension GMSDLL
```

The project is set up with
[DllExport](https://github.com/3F/DllExport)
to generate unmanaged wrappers for functions and
[GmxGen](https://github.com/YAL-GameMaker-Tools/GmxGen)
in post-build step to auto-update functions in GM extensions.

`export/` folder contains sample scripts for re-generating Local Asset Packages without going through GameMaker UI, along with a sample script for uploading releases to `itch.io`.

Caveat: it is unclear whether and how to use this for non-Windows.