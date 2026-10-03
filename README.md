# JamesDSPManager
This module enables JamesDSPManager. [More details in support thread](https://forum.xda-developers.com/android/apps-games/app-reformed-dsp-manager-t3607970).

## This fork
Fork of [Zackptg5/JamesDSPManager](https://github.com/Zackptg5/JamesDSPManager) (inactive since 2024) with one fix:

* **v6.2:** works on newer Magisk (tested on v31). Magisk no longer sets `NVBASE`, so v6.1 put its boot and uninstall scripts in a path that does not exist. The JamesDSP app was then not installed, and was not disabled or removed with the module.

Install: download [`install.zip`](install.zip) and flash it in Magisk (**Modules → Install from storage**).

### Profiles are incompatible between old and new JDSP!

## Changelog
* See [Changelog](changelog.md)

## Credits
* [James34602](https://forum.xda-developers.com/android/apps-games/app-reformed-dsp-manager-t3607970)

## Source Code
* Module [GitHub](https://github.com/therealahrion/JamesDSPManager)
* App [GitHub](https://github.com/james34602/JamesDSPManager)
