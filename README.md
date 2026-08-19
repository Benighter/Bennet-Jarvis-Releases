# JARVIS Android Releases

Public release artifacts for the private [Bennet-Jarvis](https://github.com/Benighter/Bennet-Jarvis) source repository.

This repository contains only signed APKs, update manifests, checksums, and release notes.

## Current release: 1.0.0

- OpenAI Realtime voice over a persistent WebRTC session.
- Voice selector with Marin as the default.
- Persistent foreground notification so the running JARVIS state is visible.
- Wake-word standby after the app UI is closed, with stop/disarm returning to standby.
- Boot restore notification after a phone restart.
- The in-app updater checks this manifest and asks Android for approval before installing updates.

Android requires the user to tap the boot restore notification before microphone standby can resume after a restart.

The implementation source remains private in the linked repository above.
