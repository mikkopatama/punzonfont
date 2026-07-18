# punzonfont
Punzón is a SMuFL compliant music font inspired by Spanish music engraving, especially Casa Dotésio (later named Unión Musical Española).

The primary creator of the font is Mikko Patama. [Buy me a coffee](https://buymeacoffee.com/mikkopatama) if you wish to support this project.

## Files

| File | Description |
|---|---|
| `Installers` | Easy to use installer files for macOS and Windows |
| `Source/Punzon.ufo` | Font source files, Unified Font Object package |
| `Punzon.otf` | SMuFL-compliant OpenType music font |
| `PunzonText.otf` | SMuFL-compliant OpenType music text font |
| `Punzon.json` | SMuFL font metadata |


Manual installation:

1. Copy `Punzon.otf` and `PunzonText.otf` to `~/Library/Fonts/` (macOS) or `C:\Windows\Fonts\` (Windows) or `~/.fonts` (Linux)
2. Copy `Punzon.json` to:
   - macOS: `~/Library/Application Support/SMuFL/Fonts/Punzon/`
   - Windows: `%LOCALAPPDATA%\SMuFL\Fonts\Punzon\`
   - Linux: `$XDG_DATA_HOME/SMuFL/Fonts/Punzon/` 
3. Restart your notation app
4. Select Punzon as the music font in your notation app
