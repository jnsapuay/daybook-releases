# Daybook releases

Update files for Daybook, a personal planner for Windows.

This repository holds no source code. Each release carries two files that installed copies of Daybook read when they check for updates:

- `latest.json` names the newest version and where its update is.
- `Daybook_<version>_update.bin` is the update itself. It is scrambled, signed, and only opens in an installed copy of Daybook. It cannot be used to install Daybook for the first time.

To get Daybook, ask the person who gave it to you for the installer.
