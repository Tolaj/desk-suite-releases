# Desk Suite releases

Installers for the Desk Suite desktop apps. Each app has its own release; open **Releases** and pick the app.

Each release has:

- **macOS** (`_aarch64.dmg`): Apple Silicon Macs.
- **Windows, small** (`_x64-setup.exe` or `_x64_en-US.msi`): Windows 11 and updated Windows 10. Fetches Microsoft WebView2 only when the PC lacks it.
- **Windows, with WebView2** (`_legacy`, about 213 MB): older Windows 10 and PCs with no internet.

The installers are not code-signed yet, so Windows SmartScreen and macOS may warn on first run. On a Mac, right-click the app and choose Open.
