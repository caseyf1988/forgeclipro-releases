# Forge Pro — releases

This repository is the **update feed** for the Forge Pro (ForgeCLI Pro) macOS app: the Sparkle
appcast (`appcast.xml`) and the notarized, Developer-ID-signed DMGs attached to each Release.
The app checks this feed itself (Settings → Updates); you can also download a DMG from the
Releases page and drop `ForgeCLI Pro.app` into Applications.

- **Stable** releases are ordinary Releases; **beta** builds are pre-releases and only offered
  to apps set to the Beta channel.
- The source code lives in a private repository. Third-party notices for everything the app
  ships with are in [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md); each DMG also carries
  them inside the app (Settings → Updates → Third-party notices).
