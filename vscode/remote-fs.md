Extension "Remote FS" installieren

Konfigurieren

File -> Preferences -> Settings

´´´json
    "remotefs.remote": {
      "smarthome": {
        "scheme": "sftp",
        "host": <host>,
        "username": <user>,
        "privateKeyPath": <privateKey>,
        "rootPath": "/opt/openhab/conf"
      }
    }
´´´

Dann mit STRG + Shift + P "Remote FS: Add Folder to Workspace" auswählen, da sollten die konfigurierten Remote-FS auch schon auftauchen.

Siehe auch https://github.com/liximomo/vscode-remote-fs