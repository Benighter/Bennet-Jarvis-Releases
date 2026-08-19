# JARVIS Android 1.1.0

## What’s new

- Stores recent user and JARVIS text turns in encrypted storage on the phone.
- Keeps pinned memories when you say “keep this memory” or “remember…” during a live conversation.
- Sends relevant local memory into new OpenAI Realtime sessions as user context.
- Reconnects automatically when Hey Jarvis wakes JARVIS from standby, even if the live screen was already open offline.
- Adds a Clear Memory control in the main app screen.
- Keeps the persistent voice notification, boot restore flow, voice selector, and in-app updater.

## Privacy and Android behavior

JARVIS stores text context only; it does not save microphone recordings. Memory is encrypted with an Android Keystore key and can be cleared from the app. Automatic memory is active only during a live Realtime session; standby wake detection remains separate.

Android still requires the user to arm JARVIS and grant microphone and notification permissions. After a reboot, tap the “JARVIS is ready” notification once to restore standby. Future APK updates are detected by the in-app updater, and Android asks the user to approve each installation.
