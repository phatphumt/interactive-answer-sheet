# Answer Sheet (Tauri)

Desktop app wrapper for the interactive answer sheet (`src/index.html`).

## Prerequisites (Windows)
- [Rust](https://rustup.rs/) (`cargo`, `rustc`) — required to build Tauri
- Node.js + npm (already used for the Tauri CLI scripts)
- Microsoft C++ Build Tools / Visual Studio Build Tools (for Rust on Windows)
- WebView2 Runtime (normally preinstalled on Windows 10/11)

## Build
```powershell
cd C:\Users\Phatphum\Downloads\saman-pat2-answer-sheet-tauri
npm.cmd install
npm.cmd run build
```

The installer/exe will be produced under `src-tauri\target\release\bundle\`.

## Dev
```powershell
npm.cmd install
npm.cmd run dev
```

> Note: this machine currently does not have Rust/Cargo installed, so the project is scaffolded but not yet compiled here. Install Rust from https://rustup.rs/ and re-run the build commands.
