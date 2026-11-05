# EXP Pulse releases

Installers for EXP Pulse, by EXP Interactives. This repository holds release files only. It contains no source code.

EXP Pulse scans a Windows gaming PC, finds what is holding back performance, stability, network and input, and explains how to fix each issue. It only reads your PC and changes nothing.

## Install

1. Open the latest release on the Releases page.
2. Download `EXP-Pulse-Setup-<version>-friends.exe` and `SHA256SUMS`.
3. Optional: check that the download is intact. In PowerShell, run:
   `Get-FileHash .\EXP-Pulse-Setup-<version>-friends.exe -Algorithm SHA256`
   The hash it prints must match the one in `SHA256SUMS`.
4. Run the installer. Friends builds are not code-signed yet, so Windows SmartScreen will show a warning. Click **More info**, then **Run anyway**.

EXP Pulse asks for administrator rights every time it starts. It needs them to read hardware details, event logs and system settings.

## Updates

The app checks this page for a newer version a few seconds after it starts. When an update has been downloaded and checked, a **Restart to update** button appears in Settings. The app never restarts on its own.
