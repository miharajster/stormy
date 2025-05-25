# Stormy - cat proof your keyboard
Stormy is a small background application that keeps your computer safe when your cat decides your keyboard is the perfect place for a nap. Press a hot-key once to block every keystroke, press it again to unlock. A tray icon lets you open a simple settings window or exit the app.

## Why Stormy exists

Cats are curious and heavy-pawed. One unexpected walk across the keyboard can close unsaved work, send half-written messages, reorder browser tabs, or wake a sleeping PC. Stormy freezes the keyboard until you are ready to type again.

## Features

- Toggle keyboard lock with one configurable shortcut (default: **Ctrl + Alt + L**)
- Global low-level keyboard hook (works in every app)
- Tray icon shows lock state
- Native settings window for changing the shortcut
- Configuration saved under your profile directory
- Safety fallback: **Ctrl + Alt + Del** or unplugging the keyboard always breaks the lock

## Build from source

```bash
https://github.com/miharajster/stormy.git
cd stormy
cargo build --release
