# Createas

DAGS VB6 "create as" installer helper: picks an `.msi` (or other app) and runs it under alternate credentials via `LogonUser` / `CreateProcessAsUser` (NT4) or `CreateProcessWithLogonW` (Win2K). Open `Createas.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Createas.vbp`) | VB6 | WinForms exe | Project1 |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Createas.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `COMDLG32.OCX`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Createas`.
Company names in project files:  DAGS.

## License

MIT © 2026 Vader Consulting for Dave Robinson's code. See `LICENSE`.
