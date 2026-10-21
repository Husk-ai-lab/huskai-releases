<p align="center">
  <img src="husk-logo-source.png" alt="Husk" width="140">
</p>

<h1 align="center">Husk releases</h1>

<p align="center">
  Official downloads of the Husk desktop app.<br>
  <em>Husk finds the repetitive work hidden in your company documents and turns it into automations. Everything runs on your computer.</em>
</p>

---

## Get Husk

This repository only hosts release files. You normally don't download anything from here by hand: the **Husk desktop app** fetches and installs the latest version for you, and offers updates when a new one is published.

To install by hand, open the [latest release](../../releases/latest) and pick the file for your system:

| System | File ends with |
| --- | --- |
| macOS, Apple silicon (M1 and later) | `aarch64-apple-darwin.tar.gz` |
| macOS, Intel | `x86_64-apple-darwin.tar.gz` |
| Windows, 64-bit | `x86_64-pc-windows-msvc.zip` |

A release may not include every system yet. If yours is missing, the desktop app shows it as "not available yet".

## Verify a download

GitHub shows a SHA-256 digest next to every file. Compare it with your copy:

```bash
shasum -a 256 husk-backend-<version>-<system>.tar.gz
```

Each release also includes `SHA256SUMS` and a short report of what was built and checked, including known gaps.

## Versions and channels

- **Stable**: the latest release that is not marked as a pre-release.
- **Beta**: pre-releases, offered only to people who opt in.

Release notes for each version are in [Releases](../../releases). A running history is kept in the changelog.

## Good to know

- Builds are currently **not code-signed**. Your system may ask you to confirm the first launch.
- Husk needs a company account to sign in. There is no guest mode.
- Your documents and data stay on your computer.

---

<p align="center"><sub>© Husk AI</sub></p>
