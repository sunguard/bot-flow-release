# Bot Flow

A macOS app by **Studio Miji** that handles Slack requests through editable automation flows.

This public repository hosts downloads and signed application updates. Application source is maintained privately.

## Install

Requires **macOS 14 or later**, on Apple Silicon or Intel.

1. Download the ZIP from the [latest release](https://github.com/sunguard/bot-flow-release/releases/latest).
2. Extract **Bot Flow.app**, move it to `/Applications`, and open it.
3. Configure Slack and your local model tools in the app. Message reception starts only when you turn it on.

Downloads become available after the first release is published. Quit any earlier Bot Flow instance before replacing it. Existing local settings, rules, and history are retained; macOS may ask for Keychain approval again.

## Updates

Choose **Bot Flow → 업데이트 확인…** or **연결 및 설정 → 앱 업데이트**. Automatic update checks are enabled by default. Automatic download and installation are optional and initially off. The app verifies signed update metadata and archives, then offers installation and restart.

Public releases use bundle identifier `studio.miji.flow`, Studio Miji Developer ID signing (team `Q49V3VUTFQ`), and Apple notarization. Update restart stops message reception and current work. Reception remains off after restart until you turn it on.

Earlier builds without the updater need one manual installation of this version before they can receive in-app updates.
