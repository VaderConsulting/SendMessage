# SendMessage

VB6 ActiveX DLL (`SendMessage.dll`): `clsNetMessage.BroadcastMessage` via `NetMessageBufferSend` (messenger service) and `clsEmail.SendEmail` via CDO SMTP. Open `SendMessage.vbp` in the VB6 IDE and compile/register the DLL.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX DLL

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SendMessage` (`SendMessage.vbp`) | VB6 | ActiveX DLL | Net messenger broadcast + CDO email helpers |
