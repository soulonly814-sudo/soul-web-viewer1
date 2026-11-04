[README.txt](https://github.com/user-attachments/files/34367767/README.txt)
SOUL PUBLISHER v6 — YANDEX DISK PUBLIC SHARE TEST

Windows PowerShell 5.1, Python not required.

1. Extract the entire ZIP into a NEW folder.
2. Copy yandex_token.dpapi from the WORKING v5.2 folder to this folder.
   Keep this file private. It is encrypted for your Windows account.
3. Run Start_Soul_Publisher.cmd and enter the B3D models folder.
4. In BAZIS save the model with Ctrl+S, then press the Soul button.
5. Watch the console:
   YANDEX UPLOADED: app:/soul_....b3d
   YANDEX PUBLIC LINK: https://disk.yandex...  (if API permits publishing)
   or YANDEX SHARE ERROR / HTTP / CODE / DETAIL.

The local viewer still works at http://127.0.0.1:8765/ while Publisher runs.
The Yandex public link points to the B3D FILE, not to an online Soul Web Viewer.
The online viewer needs separate hosting and a CORS-safe file delivery mechanism.

Important: Public sharing means anyone with the link can access/download the model.
Do not publish confidential projects without permission. To revoke access, unpublish
or remove the file on Yandex Disk. App-folder permission may not allow publishing;
if the API returns 403, share only the error code/details (never OAuth tokens).
