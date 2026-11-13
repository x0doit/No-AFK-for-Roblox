# No AFK for Roblox — announcements

On startup (when the update/announcement checker is on) the app downloads `announcement.json` from the `main` branch of this repository. When `enabled` is `true` and `title` is not empty, the main window shows the announcement in place of the Discord row.

```json
{
    "enabled": true,
    "notify": false,
    "icon": "",
    "iconColor": "#ffffff",
    "title": "Title",
    "description": "Optional details"
}
```

- `enabled`: show the announcement when `true` and `title` is not empty.
- `notify`: also show a Windows tray notification on startup.
- `icon`: Segoe MDL2 Assets glyph, for example ``.
- `iconColor`: icon color as `#RRGGBB`.
- `title`: shown in the main window and the tray menu.
- `description`: optional details.

Clicking the announcement opens the Discord server: https://discord.gg/ayame
