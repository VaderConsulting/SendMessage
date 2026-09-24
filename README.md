# SendMessage

VB6 ActiveX DLL (`SendMessage.dll`): `clsNetMessage.BroadcastMessage` via `NetMessageBufferSend` (messenger service) and `clsEmail.SendEmail` via CDO SMTP.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX DLL

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SendMessage` (`SendMessage.vbp`) | VB6 | ActiveX DLL | NetMessage broadcast and CDO SMTP email helpers |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `SendMessage.vbp`

Then compile and register the DLL.

## Requirements

- Visual Basic 6.0 IDE
- Windows messenger/`NetMessageBufferSend` APIs (historical)
- CDO for SMTP email helpers

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/SendMessage`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
