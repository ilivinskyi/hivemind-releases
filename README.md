# Hivemind releases

Builds of Hivemind for macOS (Apple Silicon, macOS 26 or later).
The app updates itself from this repository through Sparkle: `appcast.xml` lists the versions, and every version is a release with the app as a zip.

To install, download the newest `Hivemind-<version>.dmg` from Releases, open it and drag Hivemind to Applications.
The first time, macOS says it cannot verify the app: open System Settings -> Privacy & Security and click Open Anyway (once).
The `.zip` of each release is what installed apps use to update themselves.
On first launch the welcome tour downloads the on-device search and speech models.

The source code is not in this repository.
