# Asset Simulator Installer

This public repository contains only the files needed to install Asset Simulator. The source code and application container images remain private.

## Install on Windows

1. Download the latest installer:
   https://github.com/rhobot-ai/asset-simulator-releases/releases/latest/download/Install-AssetSimulator.bat
2. Double-click `Install-AssetSimulator.bat`.
3. If Windows shows **Windows protected your PC**, click **More info**, then **Run anyway**. The installer is unsigned, so this warning is expected.
4. Paste the access code supplied by the sender when prompted. The input may stay hidden while you paste.
5. When setup finishes, use the **Asset Simulator** desktop icon. The app opens at:
   http://localhost:8080

## Notes

- Docker Desktop is required. The installer checks for it and tries to install it if missing. If Windows asks for a restart, restart and run the installer again.
- Use the desktop icon every time; it checks for app updates on launch.
- If you see `unauthorized` or `403 Forbidden`, run the latest installer again and paste the access code carefully. If it still fails, ask the sender for a fresh access code.
- To uninstall, run `docker compose down -v` in `%LOCALAPPDATA%\AssetSimulator`, then delete that folder and the desktop icon.