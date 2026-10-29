# NIRUX Theme: Hackerman Modern

A NIRUX suite theme pack.

- Theme ID: `niru-hackerman-modern`
- Display name: **Niru Hackerman Modern**
- Background: `#0b0810`
- Foreground: `#e6ddea`
- Muted: `#8f7f99`
- Border: `#38233f`
- Focus: `#e044b7`
- Wallpaper: `nirux-wallpaper-hackerman-modern-4k.png` (3840×2160)

## Install

NIRUX must be installed and `niructl` must be in `PATH`.

```sh
./install.sh
niructl theme niru-hackerman-modern
```

The installer uses `niructl theme-import`, so it validates the theme and
installs both the palette and wallpaper into the standard per-user locations.
No root access is required.

To replace an existing installation after a pack update:

```sh
./install.sh --replace
niructl theme niru-hackerman-modern
```

## Uninstall

```sh
./uninstall.sh
```

## Compatibility

The theme is a user theme, so the suite discovers it without being added to any
built-in theme list. Components that follow the shared NIRUX theme pick it up:
NIRUWM, NIRUBAR, NIRU Launcher, NIRUNOTIFY, NIRULOCK, NIRUSCREENSAVER,
NIRUSHOT, NIRUPRES editor chrome, NIRUFLOW, NIRUORG and NIRUNOTE with
**Follow NIRUX**. NIRUPRES slide themes remain independent by design.
