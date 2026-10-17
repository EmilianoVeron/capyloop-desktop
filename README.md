# Capyloop desktop

Downloads for the Capyloop desktop app. Pick the latest release on the right, then the file for your computer:

| Computer | File |
|---|---|
| Mac with Apple Silicon (M1 or later) | `Capyloop-<version>-mac-arm64.dmg` |
| Mac with Intel | `Capyloop-<version>-mac-x64.dmg` |
| Windows | `Capyloop-<version>-windows-setup.exe` |
| Linux | `Capyloop-<version>-linux-x64.AppImage` |

The app also needs [git](https://git-scm.com) and the [GitHub CLI](https://cli.github.com). Setup steps are in the guide your company received.

**The app isn't signed yet**, so your computer warns you the first time you open it:
- **macOS:** right-click the app in Applications and choose **Open**, then **Open** again. If macOS says the app is damaged, run `xattr -cr /Applications/Capyloop.app` in Terminal, then open it.
- **Windows:** on the "Windows protected your PC" screen, click **More info**, then **Run anyway**.
- **Linux:** make the file executable (`chmod +x Capyloop-*.AppImage`) and run it.

This repository holds release builds only.
