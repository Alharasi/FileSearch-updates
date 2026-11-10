# FileSearch Updates

Public distribution channel for FileSearch Windows installers only. The FileSearch source code remains private.

The app checks `latest.json` for the newest installer version, HTTPS download URL, and SHA-256 checksum. This file will be created automatically by the private repository build workflow after the `FILESEARCH_UPDATES_TOKEN` secret is configured.

Only publish trusted installer builds. Never upload user files or private source code here.
