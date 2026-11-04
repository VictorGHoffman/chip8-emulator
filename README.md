# CHIP-8 Emulator

## How to Run
SDL can be downloaded here https://github.com/libsdl-org/SDL/releases/tag/release-2.32.10

Place SDL2.dll in desktop/target/debug

Set LIBRARY_PATH environment variable:
```powershell
$env:LIBRARY_PATH = "path\to\x86_64-w64-mingw32\lib"
```

Run the emulator with:
```powershell
cargo run path/to/game
```

