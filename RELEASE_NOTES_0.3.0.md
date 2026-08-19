# JARVIS Android 0.3.0

## What’s new

- Uses OpenAI Realtime voice over WebRTC for low-latency, two-way conversation.
- Adds a selector for the supported Realtime voices, with Marin as the default.
- Fixes Android WebView microphone routing so live voice capture can start.
- Keeps the private source repository separate from this public artifact-only release repository.

## Update behavior

The app checks the public manifest for newer versions and opens Android’s package installer after verifying the download checksum. Android still requires the user to approve the installation.
