# JARVIS Android Releases

Public release artifacts for the private [Bennet-Jarvis](https://github.com/Benighter/Bennet-Jarvis) source repository.

This repository contains only signed APKs, update manifests, checksums, and release notes.

## Current release: 1.1.1

- OpenAI Realtime voice over a persistent WebRTC session.
- Voice selector with Marin as the default.
- Encrypted phone-local text memory for recent conversations and pinned memories.
- Automatic memory capture plus “keep this memory” and “remember…” commands.
- Wake-word reconnect from standby without reopening the app or tapping Connect Live Voice.
- Persistent foreground notification so the running JARVIS state is visible.
- Boot restore notification after a phone restart.
- The in-app updater checks this manifest and asks Android for approval before installing updates.
- Android 16 memory encryption and Realtime session initialization are fixed in 1.1.1.

Android requires the user to tap the boot restore notification before microphone standby can resume after a restart.

The implementation source remains private in the linked repository above.
