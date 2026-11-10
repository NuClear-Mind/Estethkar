# Changelog

**English** | [العربية](CHANGELOG.ar.md)

## 1.0.19
- The floating panel can no longer be dragged outside the screen.
- **Move with mouse** is now a switch: it stays on, so you can drag as many times as you like, until you press the button again.
- Adhan correction (earlier or later) and the wait before the iqama are now set in **minutes and seconds**.

## 1.0.18
- The black look is now a softer charcoal grey instead of pure black.

## 1.0.17
- New: a **light** look for the settings window (Settings > General > Appearance), next to Default and Black.

## 1.0.16
- New: **Reminders** tab. Write anything you want to remember, with an optional time and repeat (once, every day, chosen days, or every few minutes).
- New: an option to make the whole floating panel fade in and out smoothly before adhan and iqama (on by default).
- New: a black look for the settings window (Settings > General).
- Language is now a button instead of a list. Lists, numbers and sliders no longer change when you scroll the page with the mouse wheel.
- The check-for-updates button has a turning arrow, a download line shows the progress of an update, and the uninstall button moved to the bottom in red.

## 1.0.15
- Lighter. The app file is less than half the size (about 56 MB down to 26 MB) and idle memory use is about a quarter of before.
- The settings window now frees its memory when you close it, and the city list is no longer kept in memory.
- Alert sounds use Windows' own player instead of a bundled media library.

## 1.0.14
- The floating panel now raises itself about three times a second, so a game that goes full screen no longer hides it. If a window still covers it, a line is written to `overlay.log` next to the app.

## 1.0.13
- Fixed the crash right after an in-app update ("DLL load failed while importing QtWidgets").

## 1.0.12
- Adhan and iqama alerts (pop-up and sound) always work while a game is running. The mute option was removed.
- The welcome dialog is gone. On first launch a yellow frame blinks around "Start with Windows" in Settings, and a banner shows while it is off.

## 1.0.11
- The iqama countdown is gold and labelled, so it stands out from the adhan countdown.

## 1.0.10
- More reliable update: the exe is swapped in one step, with an `update.log` to trace any problem.

## 1.0.9
- Removed the update button from the floating panel. The dot blinks 3 seconds before adhan and 5 before iqama, silently.

## 1.0.8
- Windows startup approval flag, and a clean name in the startup list.

## 1.0.7
- Full uninstall, and a tick on checked boxes.

## 1.0.6
- No crash when time zone data is missing.

## 1.0.5
- Only one copy runs at a time, a ✓ when up to date, and a desktop shortcut from the installer.

## 1.0.4
- A separate uninstaller next to the app, and a one-file installer.

## 1.0.0 to 1.0.3
- First releases: floating countdown, adhan and iqama alerts, Umm al-Qura times, Arabic and English, in-app update, and the name Estethkar.
