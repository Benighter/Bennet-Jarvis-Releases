# JARVIS Android 1.1.1

## Fixes

- Fixes encrypted phone-local memory writes on Android 16 by using the Keystore-generated AES-GCM initialization vector.
- Applies saved memory through a valid OpenAI Realtime session update after the session is created.
- Forces the live voice page to refresh when the Android app version changes, so the phone receives the current memory logic.
- Recognizes natural commands such as “keep it in memory” and “save it in memory” in addition to “keep this memory” and “remember…”.
- Refreshes the memory count when returning to the main screen.

## Verification

The signed APK preserves the production signing certificate and was installed over the existing JARVIS app. The phone test confirmed encrypted writes, persistence after leaving the live screen, and memory context being included in the next Realtime session without the previous session-update error.

Android still requires approval for future APK installations, and a tap on the boot notification after a phone restart.
