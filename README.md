<p align="center">
  <img src="assets/icon.png" width="128" alt="SoundInbox">
</p>

<h1 align="center">SoundInbox</h1>
<p align="center"><strong>Stop checking email. Start hearing what matters.</strong></p>
<p align="center">A native macOS menu bar app that fires distinct audio alerts when important emails arrive.</p>

<p align="center">
  <a href="https://drolosoft.com/soundinbox.html"><img src="https://img.shields.io/badge/Platform-macOS_14%2B-000?logo=apple&logoColor=white" alt="macOS 14+"></a>&nbsp;
  <a href="https://drolosoft.com/soundinbox.html"><img src="https://img.shields.io/badge/Architecture-Universal-000?logo=apple&logoColor=white" alt="Universal Binary"></a>&nbsp;
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Proprietary-blue" alt="License"></a>&nbsp;
  <a href="https://github.com/drolosoft/soundinbox/releases"><img src="https://img.shields.io/badge/Status-Pre--release-orange" alt="Status"></a>
</p>

<p align="center">
  <a href="https://drolosoft.com/soundinbox.html">Website</a> &middot;
  <a href="https://github.com/drolosoft/soundinbox/releases">Download</a> &middot;
  <a href="https://github.com/drolosoft/soundinbox/issues">Report Bug</a> &middot;
  <a href="https://github.com/drolosoft/soundinbox/issues">Request Feature</a>
</p>

---

<!-- screenshot placeholder: replace with actual screenshot when available -->
<!-- <p align="center"><img src="assets/screenshot.png" width="720" alt="SoundInbox screenshot"></p> -->

## The Problem

You check email dozens of times a day looking for the one message that actually matters. Every interruption to glance at your inbox — even for two seconds — breaks your focus and steals time you don't get back. Current email apps give you one generic ding for everything, or nothing at all.

## The Solution

**SoundInbox** removes the need to check. It lives silently in the macOS menu bar and fires the exact sound you defined for the exact event you care about. Payment received? Cash register. Urgent client? Alarm. Everything else? Complete silence. You stay focused on your work — the right sound tells you when to look.

---

## Features

|  | Feature | Description |
|---|---|---|
| :test_tube: | **Formula Gallery** | 10 pre-built detection formulas — payments, sales, urgent, shipping, security, and more. Toggle on and start hearing alerts immediately. Zero configuration. |
| :gear: | **Custom Rule Engine** | Build your own rules with AND/OR logic, regex matching, domain filtering, and per-field conditions across sender, subject, body, and recipient. |
| :speaker: | **Sound Library** | 15 curated alert sounds — from a cash register cha-ching to a zen water drop. Each under 3 seconds, distinct, and non-intrusive. |
| :bar_chart: | **Match History** | A scrollable timeline of every alert fired, with stats on most active formulas and busiest hours of the day. |
| :mute: | **Silent by Default** | Unmatched emails produce no sound. You opt in to noise, not out of it. Only what you define as important makes a sound. |
| :pushpin: | **Invisible Until Needed** | No dock icon. No main window. Lives in the status bar doing its job — you forget it's there until the right sound plays. |

### 10 Pre-Built Formulas

| | Formula | Detects | Sound |
|---|---|---|---|
| :money_with_wings: | **Payment Received** | PayPal, Stripe, Wise, bank transfers | Cash Register |
| :shopping_cart: | **New Sale** | Shopify, WooCommerce, Gumroad, Etsy | Victory Chime |
| :white_check_mark: | **Approved / Confirmed** | approved, accepted, confirmed | Soft Success |
| :rotating_light: | **Urgent Client Email** | URGENT, ASAP, critical | Alarm Pulse |
| :package: | **Order Shipped** | shipped, tracking, on its way | Notification Ping |
| :love_letter: | **VIP Sender** | User-defined whitelist | Distinct Chime |
| :receipt: | **Invoice Received** | invoice, factura, bill | Paper Slide |
| :key: | **Login / Security** | login, password, 2FA | Security Alert |
| :calendar: | **Meeting / Calendar** | invitation, meeting, scheduled | Calendar Ping |
| :shushing_face: | **Everything Else** | Catch-all — silent by default | Silent |

### 15 Curated Sounds

Every sound is under 3 seconds, distinct, and non-intrusive — from subtle and informational to urgent and celebratory.

| Sound | Description |
|---|---|
| Cash Register | Classic mechanical register — money sound |
| Victory Chime | Short ascending melody — celebratory |
| Soft Success | Gentle two-tone confirmation — calm |
| Alarm Pulse | Repeating electronic pulse — urgent |
| Notification Ping | Clean single ping — neutral |
| Distinct Chime | Bell-like — attention-grabbing |
| Paper Slide | Paper-shuffle — subtle |
| Security Alert | Low two-tone — serious |
| Calendar Ping | Light marimba — friendly |
| Message Pop | Soft pop — messaging style |
| Trumpet Fanfare | Micro fanfare — major wins |
| Ocean Drop | Water drop — zen |
| Electric Spark | Electric zap — energetic |
| Marimba Up | Ascending marimba — cheerful |
| Silent | No sound — suppresses audio |

---

## Installation

### Direct Download

Download the latest `.dmg` from [GitHub Releases](https://github.com/drolosoft/soundinbox/releases) or from [drolosoft.com/soundinbox](https://drolosoft.com/soundinbox.html).

> A single zip, no installer, no dependencies. Unzip, drag to Applications, done. Under 1 MB.

### Homebrew

```bash
brew install --cask drolosoft/tap/soundinbox
```

---

## How It Works

```
# 1  Install and connect your Gmail or Outlook account
# 2  Activate the formulas you care about (or create your own)
# 3  Go back to your work — the right sound plays when the right email arrives
```

---

## Free vs Pro

|  | Free | Pro — $9.99 |
|---|---|---|
| All formulas & custom rules | :white_check_mark: | :white_check_mark: |
| All 15 sounds + custom uploads | :white_check_mark: | :white_check_mark: |
| Regex matching, speech alerts, DND | :white_check_mark: | :white_check_mark: |
| Match history & statistics | :white_check_mark: | :white_check_mark: |
| Email accounts | 1 | **Up to 5** |
| Mac devices | 1 | **Up to 3** |
| Price | **Free forever** | **$9.99 one-time** |

> **No subscription. No recurring charges. You own it.**

---

## System Requirements

| | Requirement |
|---|---|
| OS | macOS 14.0 (Sonoma) or later |
| Architecture | Apple Silicon and Intel (Universal Binary) |
| Disk | 888 KB |
| Memory | Minimal — menu bar app |
| Network | Internet connection for email polling |

---

## Built With

Fully native. No Electron, no web wrappers, no cross-platform frameworks.

- **Swift 6.3** — Strict concurrency, modern async/await
- **SwiftUI + AppKit** — NSStatusItem, NSPopover, native menus
- **AVAudioPlayer** — System audio with macOS sound fallback
- **Sparkle** — Automatic updates

---

## FAQ

<details>
<summary><strong>How do I activate my Pro license?</strong></summary>
<br>
After purchase you'll receive a license key by email. In SoundInbox, open <strong>Preferences → License</strong>, paste your key, and click Activate. Takes about two seconds.
</details>

<details>
<summary><strong>Can I use one license on multiple Macs?</strong></summary>
<br>
Yes. A Pro license supports up to <strong>5 Gmail accounts</strong> and lets you activate SoundInbox on up to <strong>3 Mac devices</strong> simultaneously. Need to swap a device? Deactivate from Preferences → License → Manage Devices.
</details>

<details>
<summary><strong>Is there a subscription or recurring charge?</strong></summary>
<br>
No. $9.99 is a one-time payment. You own the license. No annual fees, no surprise charges.
</details>

<details>
<summary><strong>What's your refund policy?</strong></summary>
<br>
If SoundInbox doesn't work for you within 30 days of purchase, email <a href="mailto:support@drolosoft.com">support@drolosoft.com</a> and we'll issue a full refund — no questions asked.
</details>

<details>
<summary><strong>Does it work offline?</strong></summary>
<br>
SoundInbox requires an internet connection to poll email. The license check works offline once the key is activated.
</details>

<details>
<summary><strong>Does SoundInbox support Outlook or IMAP?</strong></summary>
<br>
Currently SoundInbox supports Gmail and Google Workspace accounts via the Gmail API. Outlook / Microsoft 365 and generic IMAP support are on the roadmap.
</details>

---

## License

SoundInbox is proprietary software by [Drolosoft](https://drolosoft.com). See [LICENSE](LICENSE) for details.  
Documentation is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

<p align="center">
  <a href="https://drolosoft.com">drolosoft.com</a> &middot;
  <a href="mailto:support@drolosoft.com">support@drolosoft.com</a>
</p>
