# Usage

## Requirements

- Java 21
- Windows 10 or 11 (or the platform listed in the README)

## Install

1. Install Fabric Loader 1.21 from the official site.
2. Drop the Vanta jar into .minecraft/mods.
3. Launch the Fabric profile.
4. Press RIGHT SHIFT to open the ClickGUI.
5. Load a config or start from the default profile.

## Configuration

```text
%APPDATA%\Vanta\
├── config.ini
├── profiles\
└── logs\
```

- Modules are rate-limited per tick.
- Panic key disables everything instantly.
- Configs are plain JSON.

## Commands

```text
# install
curl -L -o vanta.jar https://example.com/vanta-2.1.0.jar
mv vanta.jar .minecraft/mods/

# hotkeys
RIGHT SHIFT   ClickGUI
RIGHT CTRL    panic (disable all modules)
GRAVE         config switcher
```

## Uninstall

Delete the application folder and `%APPDATA%\Vanta`. No services, no
drivers, no scheduled tasks are installed.