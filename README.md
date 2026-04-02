# VRMod Semiofficial Module (v102)

Enhanced C++ module for [VRMod](https://steamcommunity.com/workshop/filedetails/?id=1678408548) (Garry's Mod VR).

Built from the original open-source VRMod module by **catse** (zlib license).

## What this adds

- **Keyboard input emulation from VR controllers** — send real keyboard input to Garry's Mod from VR. Game modes like TTT that only respond to keyboard input should now be playable in VR.

## Download

Pre-built Windows binaries are in the `release/` folder:
- `gmcl_vrmod_win32.dll` — for 32-bit Garry's Mod
- `gmcl_vrmod_win64.dll` — for 64-bit Garry's Mod (x86-64 branch)

### Installation
1. Download the DLL matching your Garry's Mod version
2. Place it in `GarrysMod/garrysmod/lua/bin/` (create the folder if it doesn't exist)
3. Restart Garry's Mod

**Note:** This replaces your existing VRMod module. To revert, reinstall the original VRMod or x64 module.

## Building from source

### Windows
Requires Visual Studio 2019/2022 with C++ Desktop Development workload.
```
build.bat
```
Output: `install/GarrysMod/garrysmod/lua/bin/gmcl_vrmod_win32.dll` and `gmcl_vrmod_win64.dll`

### Linux
Push to GitHub and the Actions workflow (`.github/workflows/build.yml`) will build automatically.
Download the artifacts from the Actions tab.

## Compatibility

- Works with original VRMod and semiofficial fork
- Works on both Normal and x86-64 branch of Garry's Mod
- API-compatible with existing VRMod Lua code

## License

zlib License — see [LICENSE](LICENSE)

Original software copyright (c) 2019 Catse.
Modified by the vrmod_semioffcial project, 2026.

## Related

- [VRMod Semiofficial (Steam Workshop)](https://steamcommunity.com/sharedfiles/filedetails/?id=2780083257)
- [Original VRMod (Steam Workshop)](https://steamcommunity.com/workshop/filedetails/?id=1678408548)
