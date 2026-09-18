# Netwksta

Karl E. Peterson VB6 workstation info demo (project Project1, form `FWkstaInfo` caption "CNetWksta Test Form"). Class `CNetWksta` calls NetAPI32 `NetWkstaGetInfo` (level 102) and `NetWkstaUserGetInfo` (level 1), then Refresh prints machine name, domain, LanMan version/root, logged-on user count, and the current logon domain/server/other domains. Copyright header in the class is 1997.

**Source last updated:** 1997-06-01 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Netwksta.vbp`) | VB6 | WinForms exe | NetWkstaGetInfo / NetWkstaUserGetInfo workstation and logon viewer |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Netwksta.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Windows NT with NetAPI32 workstation query support

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Netwksta`.
Class copyright: (C)1997, Karl E. Peterson.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
