# Awesome niri with stars

<!--lint disable awesome-heading-->

<div align=center><img width="1058" height="595" alt="Awesome X niri" src="banner.png" /></div>
<div align=center><img src="https://awesome.re/badge-flat.svg" /></div>

[niri](https://github.com/niri-wm/niri) ⭐ 26,984 | 🐛 487 | 🌐 Rust | 📅 2026-08-18 is a scrollable-tiling Wayland compositor. This is a curated list of resources related to niri.

*Please read the [contributing guidelines](CONTRIBUTING.md) before contributing to this list.*

## Contents

* [Help and Discussion](#help-and-discussion)
* [Packages](#packages)
* [Tools](#tools)
  * [Toolkits](#toolkits)
  * [Window and Workspace Management](#window-and-workspace-management)
  * [Session Management](#session-management)
  * [Wallpapers and Visuals](#wallpapers-and-visuals)
  * [System Integration and Automation](#system-integration-and-automation)
  * [Miscellaneous](#miscellaneous)
* [Custom Shaders](#custom-shaders)
* [Bars and Widgets](#bars-and-widgets)
* [Custom Shells](#custom-shells)
* [DE Integration](#de-integration)
* [Distro Integration](#distro-integration)
* [Rices and OOTB Setups](#rices-and-ootb-setups)

## Help and Discussion

<!--We break the alphbetical order here because we would like to keep the official ones before the community maintained ones-->

* [niri Wiki](https://niri-wm.github.io/niri) - The official wiki, containing installation instructions and usage guides.
* [niri Matrix Channel](https://matrix.to/#/#niri:matrix.org) - The official Matrix channel, where you can ask questions and get help from the community.
* [niri Discord server](https://discord.gg/vT8Sfjy7sx) - A community maintained Discord server.
* [niri subreddit](https://www.reddit.com/r/niri) - A community driven subreddit.

## Packages

* [Community Packages](https://repology.org/project/niri/packages) - A list of community maintained packages for niri.
* [niri-flake](https://github.com/epireyn/niri-flake) ⭐ 67 | 🐛 2 | 🌐 Nix | 📅 2026-08-18 - A Nix flake with cached binary builds and batteries-included modules (actively maintained fork of [sodiboo/niri-flake](https://github.com/sodiboo/niri-flake) ⭐ 972 | 🐛 78 | 🌐 Nix | 📅 2026-08-18).
* [niri-nix](https://codeberg.org/bananad3v/niri-nix) - A Nix flake with cached binary builds and freeform config.

## Tools

### Toolkits

For bundles of various utilities.

* [niri tweaks](https://github.com/heyoeyo/niri_tweaks) ⭐ 117 | 🐛 2 | 🌐 Python | 📅 2026-08-04 - A collection of scripts. Notably includes a script which allows tiling N windows before scrolling new ones.
* [piri](https://github.com/Asthestarsfalll/piri) ⭐ 86 | 🐛 4 | 🌐 Rust | 📅 2026-08-07 - A collection of plugins making use of niri IPC.
* [niri-companion](https://github.com/dybdeskarphet/niri-companion) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2026-06-01 - A toolkit that adds extra functionality.
* [niri-scripts](https://github.com/0xwal/niri-scripts) ⭐ 27 | 🐛 3 | 🌐 Rust | 📅 2026-01-14 - A collection of scripts. Notably allows setting wallpaper per workspace.
* [Nirius](https://sr.ht/~tsdh/nirius) - Utility commands.

### Window and Workspace Management

For utilities that assist in managing windows and workspaces.

* [niri-sidebar](https://github.com/Vigintillionn/niri-sidebar) ⭐ 173 | 🐛 10 | 🌐 Rust | 📅 2026-05-16 - Manage windows using a floating sidebar.
* [niri-scratchpad](https://github.com/gvolpe/niri-scratchpad) ⭐ 138 | 🐛 0 | 🌐 Python | 📅 2026-03-22 - Scratchpad support.
* [miri](https://github.com/MintyDoggo/miri) ⭐ 102 | 🐛 12 | 🌐 Rust | 📅 2026-06-21 - A niri extension adding per-workspace tiling layouts, such as Master Stack, similar to hyprland or mangowm.
* [niri-float-sticky](https://github.com/probeldev/niri-float-sticky) ⭐ 101 | 🐛 1 | 🌐 Go | 📅 2026-05-12 - A utility to make floating windows visible across all workspaces — similar to "sticky windows" in other compositors.
* [niri-scratchpad-rs](https://github.com/argosnothing/niri-scratchpad-rs) ⭐ 77 | 🐛 3 | 🌐 Rust | 📅 2026-04-09 - Dynamic scratchpads.
* [ndrop](https://github.com/Schweber/ndrop) ⭐ 52 | 🐛 1 | 🌐 Shell | 📅 2026-01-24 - Emulate tdrop.
* [oniri](https://github.com/Antiz96/oniri) ⭐ 48 | 🐛 3 | 🌐 Rust | 📅 2026-08-17 - A tool that automatically maximizes the only window in a workspace.
* [nfsm](https://github.com/gvolpe/nfsm) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2026-05-23 - Fullscreen manager.
* [nsticky](https://github.com/lonerOrz/nsticky) ⭐ 41 | 🐛 0 | 🌐 Rust | 📅 2026-08-11 - A utility to make windows visible across all workspaces.
* [nirimap](https://github.com/alexandergknoll/nirimap) ⭐ 24 | 🐛 3 | 🌐 Rust | 📅 2026-08-05 - A minimal workspace minimap overlay.
* [niri-ror](https://github.com/boomskats/niri-ror) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2026-01-08 - Focuses an app if it's open, or starts a new instance if not. With advanced window matching and multi-instance cycling.
* [niri-empty](https://codeberg.org/lunahd/niri-empty) - Execute a shell command when focusing an empty workspace.

### Session Management

For saving, restoring, and managing user sessions.

* [niri-session-manager](https://github.com/MTeaHead/niri-session-manager) ⭐ 77 | 🐛 2 | 🌐 Rust | 📅 2025-07-25 - Automatically save and restore windows.
* [nirinit](https://github.com/amaanq/nirinit) ⭐ 74 | 🐛 5 | 🌐 Rust | 📅 2026-03-25 - Session manager that automatically saves and restores your window layout.
* [swaytreesave](https://github.com/fabienjuif/swaytreesave) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-07-05 - CLI to save and load your compositors tree/layout.

### Wallpapers and Visuals

For managing wallpapers and other visual elements.

* [hyprlax](https://github.com/sandwichfarm/hyprlax) ⭐ 213 | 🐛 10 | 🌐 C | 📅 2026-07-12 - Smooth parallax wallpaper daemon.
* [wayvid](https://github.com/YangYuS8/wayvid) ⭐ 131 | 🐛 16 | 🌐 Rust | 📅 2026-07-20 - A dynamic video wallpaper engine for Wayland compositors.
* [pandora](https://github.com/PandorasFox/pandora) ⭐ 48 | 🐛 1 | 🌐 Rust | 📅 2025-09-30 - Parallax-scrolling wallpaper daemon for Wayland.

### System Integration and Automation

For tools that integrate niri with other system components or automate tasks.

* [Anyrun](https://github.com/anyrun-org/anyrun) ⭐ 1,290 | 🐛 73 | 🌐 Rust | 📅 2026-08-14 - A Wayland native krunner-like runner, made with customizability in mind. Provides [niri-focus](https://github.com/anyrun-org/anyrun/blob/master/plugins/niri-focus/README.md) ⭐ 1,290 | 🐛 73 | 🌐 Rust | 📅 2026-08-14 plugin.
* [Stasis](https://github.com/saltnpepper97/stasis) ⭐ 174 | 🐛 7 | 🌐 Rust | 📅 2026-08-15 - A modern Wayland idle manager with smart timeouts, media awareness, and app-specific inhibition.
* [IIO-Niri](https://github.com/Zhaith-Izaliel/iio-niri) ⭐ 58 | 🐛 1 | 🌐 Rust | 📅 2026-08-16 - Listen to iio-sensor-proxy and update niri output orientation depending on the accelerometer orientation.
* [nirimon](https://github.com/stepbrobd/nirimon) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2026-08-18 - A TUI monitor configuration tool with visual layout, drag-and-drop, and profile management (profile schema compliant with hyprmon).
* [system76-scheduler-niri](https://github.com/Kirottu/system76-scheduler-niri) ⭐ 23 | 🐛 1 | 🌐 Nix | 📅 2026-04-25 - A simple daemon to update the foreground process of [system76-scheduler](https://github.com/pop-os/system76-scheduler) ⭐ 639 | 🐛 20 | 🌐 Rust | 📅 2026-07-29 based on the focused window.
* [vim-niri-nav](https://github.com/andergrim/vim-niri-nav) ⭐ 20 | 🐛 3 | 🌐 Vim Script | 📅 2026-06-19 - Seamless navigation between niri windows and (neo)vim splits with the same key bindings.
* [NASW](https://github.com/ledati16/nasw) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2026-03-08 - Automatically switch audio based on active windows.
* [nirilayout](https://github.com/calico32/nirilayout) ⭐ 14 | 🐛 2 | 🌐 Go | 📅 2026-06-09 - Quickly switch output configuration between different layouts.
* [kunai](https://github.com/mikkurogue/kunai) ⭐ 5 | 🐛 2 | 🌐 Rust | 📅 2026-08-15 - Automatically switch keyboard layouts based on which physical keyboard is being used.
* [niri-screensaver](https://github.com/jfreed-dev/niri-screensaver) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2026-08-07 - Idle-aware terminal screensaver for niri, driven by TerminalTextEffects, with an optional Noctalia plugin for IdleService integration.
* [niriSKL.nvim](https://github.com/MahouShoujoMivutilde/niriSKL.nvim) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-06-27 - A Neovim plugin that maintains your latin keyboard layout of choice for NORMAL mode and restores the layout you had when in INSERT mode.
* [niri-autoselect-portal](https://codeberg.org/debugloop/niri-autoselect-portal) - Always autoselect the dynamic cast target without any prompts.

### Miscellaneous

* [nirimod](https://github.com/srinivasr/nirimod) ⭐ 372 | 🐛 4 | 🌐 Python | 📅 2026-08-02 - A visual, interactive configuration interface.
* [niri-settings](https://github.com/stefonarch/niri-settings) ⭐ 149 | 🐛 2 | 🌐 Python | 📅 2026-07-18 - Basic configuration GUI for niri config.
* [niri-screen-time](https://github.com/probeldev/niri-screen-time) ⭐ 65 | 🐛 1 | 🌐 Go | 📅 2026-07-28 - A utility that collects information about how much time you spend in each application.
* [arbtt-capture-wl](https://github.com/franzos/arbtt-capture-wl) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-07-01 - Time tracker utility [arbtt](https://github.com/nomeata/arbtt) ⭐ 355 | 🐛 60 | 🌐 Haskell | 📅 2024-04-20 ported to Wayland.
* [niri-cwd](https://github.com/nouritsu/niri-cwd) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-03-29 - A program to print the focused window's working directory.
* [niri-screenshot-tools](https://codeberg.org/whenthesilly/niri-screenshot-tools) - A program that sends screenshots taken in niri to an annotator or uploads them to a server.

## Custom Shaders

* [Nirimation](https://github.com/XansiVA/nirimation) ⭐ 223 | 🐛 0 | 🌐 Python | 📅 2026-07-20 - A host for custom shaders to be used as animations.
* [shaders](https://github.com/liixini/shaders) ⭐ 210 | 🐛 0 | 🌐 GLSL | 📅 2026-07-23 - A collection of custom shaders.

## Bars and Widgets

* [Waybar](https://github.com/Alexays/Waybar) ⭐ 11,819 | 🐛 712 | 🌐 C++ | 📅 2026-08-14 - Highly customizable Wayland bar based on GTK.
* [Ironbar](https://github.com/JakeStanger/ironbar) ⭐ 1,434 | 🐛 123 | 🌐 Rust | 📅 2026-08-18 - A customisable Wayland GTK bar written in Rust.
* [ashell](https://github.com/MalpenZibo/ashell) ⭐ 1,068 | 🐛 102 | 🌐 Rust | 📅 2026-08-17 - A ready to go Wayland status bar.
* [Ignis](https://github.com/linkfrg/ignis) ⭐ 678 | 🐛 66 | 🌐 Python | 📅 2026-08-18 - A widget framework for building desktop shells, written and configurable in Python.
* [vibepanel](https://github.com/prankstr/vibepanel) ⭐ 161 | 🐛 3 | 🌐 Rust | 📅 2026-08-17 - A GTK4 panel for Wayland with integrated notifications, OSD, and quick settings.
* [Niri Taskbar](https://github.com/LawnGnome/niri-taskbar) ⭐ 151 | 🐛 29 | 🌐 Rust | 📅 2025-12-04 - Provides a Waybar taskbar module for niri.
* [i3bar-river](https://github.com/MaxVerevkin/i3bar-river) ⭐ 86 | 🐛 23 | 🌐 Rust | 📅 2025-05-19 - A port of i3bar for Wayland compositors, to be used with something like [i3status-rust](https://github.com/greshake/i3status-rust) ⭐ 3,136 | 🐛 120 | 🌐 Rust | 📅 2026-08-15.
* [bar-rs](https://github.com/faervan/bar-rs) ⭐ 80 | 🐛 12 | 🌐 Rust | 📅 2026-08-08 - A simple status bar, written using iced-rs.
* [niri\_window\_buttons](https://github.com/adelmonte/niri_window_buttons) ⭐ 56 | 🐛 1 | 🌐 Rust | 📅 2026-06-07 - A Waybar module for displaying and managing traditional window buttons.
* [waybar-niri-windows](https://github.com/calico32/waybar-niri-windows) ⭐ 46 | 🐛 4 | 🌐 Go | 📅 2026-06-02 - A module for Waybar that displays a focus indicator for the current workspace.
* [eww-niri-workspaces](https://github.com/druskus20/eww-niri-workspaces) ⭐ 27 | 🐛 0 | 🌐 Rust | 📅 2026-04-25 - A Rust binary that outputs workspace information from niri-ipc to be consumed by eww.
* [niri-ribbon](https://github.com/ews/noctalia-niri-ribbon) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-05-23 - A viewport mini-map widget for the Noctalia shell that tracks off-screen windows in real-time.

## Custom Shells

* [Noctalia](https://github.com/Ly-sec/Noctalia) ⭐ 9,610 | 🐛 255 | 🌐 C++ | 📅 2026-08-18 - A sleek and minimal desktop shell built with Quickshell.
* [DankMaterialShell](https://github.com/AvengeMedia/DankMaterialShell) ⭐ 7,645 | 🐛 447 | 🌐 QML | 📅 2026-08-18 - Quickshell based shell featuring Material 3 design principles, with a heavy focus on functionality and customizability.
* [iNiR](https://github.com/snowarch/iNiR) ⭐ 1,436 | 🐛 23 | 🌐 QML | 📅 2026-08-12 - [end-4's quickshell config](https://github.com/end-4/dots-hyprland) ⭐ 15,639 | 🐛 633 | 🌐 QML | 📅 2026-08-15 modified to work with niri.
* [Exo](https://github.com/debuggyo/Exo) ⭐ 683 | 🐛 13 | 🌐 Python | 📅 2026-01-16 - A Material 3 inspired desktop shell created with Ignis.
* [Delta Shell](https://github.com/Sinomor/delta-shell) ⭐ 208 | 🐛 14 | 🌐 TypeScript | 📅 2026-07-17 - A desktop shell based on AGS with many features.
* [GPUi Shell](https://github.com/andre-brandao/gpui-shell) ⭐ 120 | 🐛 2 | 🌐 Rust | 📅 2026-08-07 - A GPUI based shell written in Rust.
* [qml-niri](https://github.com/imiric/qml-niri) ⭐ 100 | 🐛 0 | 🌐 C++ | 📅 2026-08-08 - A QML plugin for interacting with niri via its IPC protocol.
* [desktop-shell](https://github.com/hashankur/desktop-shell) ⭐ 35 | 🐛 0 | 🌐 QML | 📅 2026-07-08 - Custom AGS shell for Wayland compositors supporting wayland-layer-shell.
* [IgnisNiriShell](https://github.com/lost-melody/IgnisNiriShell) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2026-01-28 - An Ignis based shell.
* [Glimpse](https://github.com/alex-oleshkevich/glimpse) ⭐ 10 | 🐛 2 | 🌐 Rust | 📅 2026-08-18 - A niri-first Wayland desktop shell toolkit with a panel, wallpaper, lock screen, night light, and idle management.

## DE Integration

* [niri on LXQt](https://lxqt-project.org) - LXQt is a lightweight Qt-based desktop environment that allows setting [niri as compositor](https://github.com/lxqt/lxqt/wiki/ConfigWaylandSettings) ⭐ 1,861 | 🐛 176 | 🌐 Shell | 📅 2026-05-17, while its modules can also be used standalone in `niri-session`.
* [niri on Cosmic](https://github.com/Drakulix/cosmic-ext-extra-sessions) ⭐ 181 | 🐛 15 | 🌐 Shell | 📅 2025-04-02 - A Cosmic extension that allows niri as a session option, allowing you to use niri with the [Cosmic desktop environment](https://github.com/pop-os/cosmic-epoch) ⭐ 6,654 | 🐛 1,792 | 🌐 Just | 📅 2026-07-29.

## Distro Integration

* [CachyOS](https://wiki.cachyos.org/configuration/desktop_environments/niri) - An Arch Linux based distribution focused around gaming, performance, and being user-friendly. It provides niri as an install option via its installer.
* [KaOS](https://kaosx.us/desktop/niri) - An independent, built from-scratch Linux distribution, focused on Qt. niri and Noctalia are shipped as the default desktop environment.
* [Pika OS](https://wiki.pika-os.com/en/home#niri-edition) - PikaOS is a Debian sid based Linux distribution focused on gaming and performance optimization, which provides a niri edition ISO.

## Rices and OOTB Setups

* [Setup Showcase](https://github.com/niri-wm/niri/discussions/325) ⭐ 26,984 | 🐛 487 | 🌐 Rust | 📅 2026-08-18 - A showcase of niri setups, where users can share their configurations and get inspiration from others.
* [OOTB setups](https://github.com/Vortriz/awesome-niri/discussions/30) ⭐ 1,403 | 🐛 0 | 🌐 Nix | 📅 2026-08-10 - A collection of out-of-the-box niri configurations that can be easily installed to get a fully functional setup quickly.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
