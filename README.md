<p align="center">
  <!-- <img src="https://box.buxjr.com/img/logo.svg" alt="Box" width="80"> -->
  <h1 align="center">Box</h1>
  <p align="center"><strong>Your email belongs to you.</strong></p>
  <p align="center">A beautiful desktop email client for Linux, built on privacy, speed, and respect for your data.</p>
</p>

<p align="center">
  <a href="https://box.buxjr.com/download">Download</a> &nbsp;&bull;&nbsp;
  <a href="https://box.buxjr.com/features">Features</a> &nbsp;&bull;&nbsp;
  <a href="https://box.buxjr.com/privacy">Privacy</a> &nbsp;&bull;&nbsp;
  <a href="https://box.buxjr.com/pricing">Pricing</a> &nbsp;&bull;&nbsp;
  <a href="https://box.buxjr.com/faq">FAQ</a>
</p>

---

<!-- PLACEHOLDER: Hero screenshot of Box in dark mode showing three-pane layout -->
<!-- <p align="center"><img src="https://box.buxjr.com/img/screenshots/hero.png" alt="Box screenshot" width="800"></p> -->

---

## What is Box?

Box is a desktop email client for Linux that combines a modern, polished interface with a privacy-first architecture. Your email stays on your machine. No cloud. No telemetry. No middleman.

**Free for one account. $10 one-time for unlimited accounts.**

## Features

- **Multi-account** — Gmail, Outlook, Yahoo, Fastmail, self-hosted IMAP — all in one window
- **Beautiful email rendering** — Smart padding detection, dark mode support, contrast-aware styling
- **Full-text search** — SQLite FTS5-powered search across sender, subject, body, and snippets
- **Offline-first** — Outbox queues messages when offline, deferred sync replays operations on reconnect
- **OAuth2** — Secure browser-based authentication for Google and Microsoft accounts
- **Rich compose** — Bold, italic, underline, text color, inline images, drag-and-drop attachments
- **Desktop integration** — System notifications, OS keyring credential storage, .eml file association, print support
- **Dark mode** — Full light/dark/system theme support with intelligent email rendering in both modes
- **Keyboard shortcuts** — Ctrl+N, Ctrl+R, Ctrl+Enter, Ctrl+P, and more
- **35+ email providers** — Pre-configured server settings for major providers, plus auto-discover for the rest

## Privacy

Box does not collect telemetry, analytics, usage data, or crash reports. This is an architectural guarantee, not a policy.

Box communicates only with:
- Your mail servers (IMAP/SMTP), as configured by you
- The licensing service at `locksmith.buxjr.com` (activation and optional validation only)

Your credentials are stored in your OS keyring (GNOME Keyring / libsecret), never in plaintext.

[Read the full Privacy Architecture &rarr;](https://box.buxjr.com/privacy)

## Download

| Format | Description |
|--------|-------------|
| **AppImage** | Works on any modern Linux distribution — Ubuntu, Fedora, Arch, Mint, Manjaro, and more |
| **Debian Package (.deb)** | For Ubuntu, Mint, Debian, and derivatives |

Download the latest release from the [Releases](../../releases) page or from [box.buxjr.com/download](https://box.buxjr.com/download).

All releases include SHA256 checksums and GPG signatures for verification.

## System Requirements

| Resource | Minimum | Recommended |
|----------|---------|-------------|
| **RAM** | 512 MB | 1 GB |
| **Disk Space** | 200 MB | 500 MB |
| **Display** | 1280x720 | 1920x1080+ |

## Pricing

**Free** — One email account, full functionality, no time limit, no crippled features.

**$10 one-time** — Unlimited accounts on up to 5 machines. No subscription. No recurring fees. Ever.

[Buy a License &rarr;](https://box.buxjr.com/pricing)

## Support

- **Bug reports and feature requests** — [Open an issue](../../issues)
- **FAQ** — [box.buxjr.com/faq](https://box.buxjr.com/faq)
- **Direct support** — [box.buxjr.com/support](https://box.buxjr.com/support)

## Verifying Downloads

All releases are signed. To verify:

```bash
# Verify checksum
sha256sum -c SHA256SUMS

# Verify GPG signature (after importing our public key)
gpg --import box-public-key.asc
gpg --verify SHA256SUMS.asc SHA256SUMS
```

GPG public key available at [box.buxjr.com/download](https://box.buxjr.com/download).

---

<p align="center">
  <a href="https://box.buxjr.com">box.buxjr.com</a>
</p>
