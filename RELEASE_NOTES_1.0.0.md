# JARVIS Android 1.0.0

## What’s new

- Keeps JARVIS live voice visible in an ongoing Android foreground notification.
- Keeps the listening service available after the normal app UI is closed.
- Returns to Hey Jarvis standby after stop, disarm, or sleep commands.
- Restores the configured state with a JARVIS notification after phone startup.
- Keeps the OpenAI Realtime voice selector, with Marin as the default.
- Keeps the signed APK updater and public artifact-only release channel.

## Android behavior

The user must arm JARVIS from the visible app UI and allow microphone and notification permissions. Android does not allow a microphone foreground service to start directly from `BOOT_COMPLETED`, so after a reboot JARVIS posts a “JARVIS is ready” notification. Tapping that notification restores Hey Jarvis standby.

Future APK updates are detected by the in-app updater, and Android asks the user to approve each installation.
