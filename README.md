<p align="center">
  <img src="assets/logo.svg" alt="DeltaVision" height="120" />
</p>

<p align="center">
  <a href="https://deltavision.app">Website</a> •
  <a href="https://deltavision.app/changelog">Changelog</a> •
  <a href="https://github.com/impaktfull/delta_vision/releases">Downloads</a> •
  <a href="https://github.com/impaktfull/delta_vision/issues">Issues</a>
</p>

# DeltaVision

> Visual diff for Git-tracked images. DeltaVision detects the images that changed in your Git
> repository and shows you exactly what changed, pixel by pixel, commit by commit. Built for
> reviewing Flutter golden test changes.

## Alpha

DeltaVision is in alpha, and **free for approved testers**. Request access at
[deltavision.app](https://deltavision.app/#alpha). Once you are approved, you get an email; sign in
to the app with that address.

## Install

| Platform | Install |
| -------- | ------- |
| macOS 12 or later | `brew install --cask impaktfull/tap/deltavision`, or the `.dmg` |
| Windows 10 or 11 | `DeltaVision-X.Y.Z-setup.exe` |
| Linux (x86_64) | `DeltaVision-X.Y.Z-x86_64.AppImage` |

Downloads are on the [releases page](https://github.com/impaktfull/delta_vision/releases), each
with a `.sha256` checksum. The app tells you when a new version is out.

- **macOS:** the app is signed and notarized by Apple. Update a Homebrew install with
  `brew upgrade --cask deltavision`.
- **Windows:** the installer is not signed yet, so Windows SmartScreen may warn the first time:
  choose *More info*, then *Run anyway*.
- **Linux:** make the AppImage executable (`chmod +x DeltaVision-*.AppImage`) and run it.

DeltaVision compares images with [ImageMagick](https://imagemagick.org) and Git, so both need to be
installed; the app checks for them when it starts.

## Issues and ideas

This repository is the public home of DeltaVision: the place to report a bug or ask for a feature.
The source code of the app and the platform is closed.

- **Found a bug?** [Open a bug report](https://github.com/impaktfull/delta_vision/issues/new?template=bug_report.yml).
- **Missing something?** [Suggest a feature](https://github.com/impaktfull/delta_vision/issues/new?template=feature_request.yml).
- **A question about your access or your account?** Mail [hello@impaktfull.com](mailto:hello@impaktfull.com).
  Never put personal details in an issue: issues are public.

---

DeltaVision is made by [impaktfull](https://impaktfull.com).
