# SynSound Android Wrapper (Historical Repository)

This repository is an earlier Android wrapper snapshot. It is **not the canonical source for current SynSound releases** and its old badges or feature descriptions should not be interpreted as evidence that a feature is present in the current APK or that the app is listed in the official F-Droid repository.

## Use the current project

- **Canonical Android source and release history:** [Neurosyn-Dev/SYNSOUND](https://github.com/Neurosyn-Dev/SYNSOUND)
- **Current release information:** [GitHub Releases](https://github.com/Neurosyn-Dev/SYNSOUND/releases)
- **Current Android release workflow:** [Build & Release Actions](https://github.com/Neurosyn-Dev/SYNSOUND/actions/workflows/build.yml)
- **F-Droid submission:** [fdroiddata MR !47018](https://gitlab.com/fdroid/fdroiddata/-/merge_requests/47018)
- **Issue tracker:** [Canonical repository issues](https://github.com/Neurosyn-Dev/SYNSOUND/issues)

## Historical scope

This repository contains an Android WebView wrapper around the hosted SynSound web application. Historically, its native layer handled the app shell, trusted-origin navigation, microphone permission mediation, file selection/downloads, session persistence, and network/error recovery.

The hosted web service supplies the primary audio interface and remains a network dependency. Do not infer that every DSP, visualization, speech, mastering, or acoustic-analysis capability is implemented natively in this repository. Consult the canonical README and the exact release notes for the current feature boundary.

## Development and security

Use the canonical repository for current code changes, tests, security fixes, version numbers, release signing, and F-Droid metadata. Any changes made only in this historical repository do not update the canonical application or its published releases.

## License

This repository contains an MIT license. See [LICENSE](LICENSE).
