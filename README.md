# JamesDSPManager
This module enables JamesDSPManager. [More details in support thread](https://forum.xda-developers.com/android/apps-games/app-reformed-dsp-manager-t3607970).

## This fork
Fork of [Zackptg5/JamesDSPManager](https://github.com/Zackptg5/JamesDSPManager) (inactive since 2024) with these fixes:

* **v6.3:** fixes silence with per-session (enhanced) processing. The 32-bit ARM effect library is built from [Etsum/libjamesdsp](https://github.com/Etsum/libjamesdsp).
* **v6.2:** works on newer Magisk (tested on v31). Magisk no longer sets `NVBASE`, so v6.1 put its boot and uninstall scripts in a path that does not exist. The JamesDSP app was then not installed, and was not disabled or removed with the module.

Install: download the zip for the version you want from [Releases](https://github.com/Etsum/JamesDSPManager/releases) (latest: v6.3), then install it in Magisk (**Modules → Install from storage**) and restart. To roll back, install an older zip the same way. Each release lists the effect libraries in its zip, with their SHA-1.

### Profiles are incompatible between old and new JDSP!

## Changelog
* See [Changelog](changelog.md)

## Credits
* [James34602](https://forum.xda-developers.com/android/apps-games/app-reformed-dsp-manager-t3607970)

## Source Code
* Module [GitHub](https://github.com/therealahrion/JamesDSPManager)
* App [GitHub](https://github.com/james34602/JamesDSPManager)
