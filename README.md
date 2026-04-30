<p align="center">
  <a href="https://padlinq.com">
    <img src="https://padlinq.com/favicon.png" width="72" height="72" alt="PadlinQ" />
  </a>
  <h3 align="center">PadlinQ</h3>
  <p align="center"><strong>Your phone is the controller you forgot you had.</strong></p>
  <p align="center">
    <a href="https://github.com/Triomax66/padlinq-dist/releases/latest">
      <img src="https://img.shields.io/github/v/release/Triomax66/padlinq-dist?label=latest&style=flat-square&color=00ff85" alt="Latest release" />
    </a>
    <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-blue?style=flat-square" alt="Windows 10/11" />
    <img src="https://img.shields.io/badge/free-while%20in%20beta-00ff85?style=flat-square" alt="Free while in beta" />
  </p>
  <p align="center">
    <a href="https://padlinq.com">Website</a> &nbsp;·&nbsp;
    <a href="https://padlinq.com/app">Host a session</a> &nbsp;·&nbsp;
    <a href="https://github.com/Triomax66/padlinq-dist/releases/latest">Download</a>
  </p>
</p>

---

## Three steps. Under a minute.

| | |
|--|--|
| **01 · Install** | Run `padlinq-setup.exe`. One click — Windows prompts for admin, the driver is set up for you. |
| **02 · Claim** | The helper prints a link to `padlinq.com/app` with your PC prefilled. Hit Claim and a session QR appears. |
| **03 · Play** | Point your phone's camera at the QR. The controller loads in the browser, and Windows sees it as an Xbox pad. |

---

## What it does

> Scan a QR. Play Steam, Game Pass, or any PC game — at home or across the internet. Stream the screen back to your phone, split it between up to 8 players, and pick from 15+ controller layouts. No app on the phone. No cables. No spare controllers to hunt down.

### Play

- **No phone app, ever** — Scan a QR and the controller loads in your phone's browser. iPhone and Android, no App Store, no permissions dance.
- **Feels like a real gamepad** — Windows sees a virtual Xbox 360 (XInput) or DualShock 4 (DInput) pad. Steam, emulators, Game Pass, every PC game.
- **Up to 8 players** — Couch co-op for the whole room without ever buying another controller. Each player picks their own layout.
- **Plays anywhere on the internet** — Default mode pairs over a tiny signalling relay so the phone doesn't need to be on the same WiFi. Inputs flow peer-to-peer over WebRTC after pairing.
- **Add to Home Screen on iPhone** — PadlinQ installs as a PWA. One tap launches the controller fullscreen — no Safari chrome, no accidental swipes.
- **Bring your own controller** — Plug in a Backbone, Razer Kishi, or any Bluetooth/USB pad and the phone auto-hides the on-screen layout.

### Stream your PC screen

- **See your game on your phone** — Toggle screen streaming in admin and your PC display appears live behind the on-screen controller — couch, kitchen, patio, anywhere.
- **Stream a single window** — WGC capture sends just one app instead of the whole desktop. Notifications and second monitors stay private.
- **Splitscreen for every player** — Drag-and-drop region editor assigns each phone a slice of the stream. One-click presets for 2-up, 3-up, and 2×2 quad.
- **Hardware-accelerated** — NVENC, Quick Sync, AMF, and VAAPI paths with playout-delay hints set to zero.

### Customize

- **15+ controller layouts** — Xbox, PlayStation, NES, SNES, N64, GameCube, Genesis, Joy-Con (single & dual), fight stick, racing wheel, touchpad, and fully custom.
- **7 visual themes** — Default, Dark, Neon, Mono, Arcade, Glass, and High-Contrast.
- **Smart triggers** — Tap = digital press. Drag past the threshold = analog. Same button, both behaviors, no settings menu to learn.
- **Design your own layout** — In-app editor for every button, stick, and trigger. Resize, reposition, share by URL.
- **Tilt steering & haptics** — Racing layout uses phone tilt for the left stick. Android gets rumble on every press.

### Trust

- **Peer-to-peer** — The relay only introduces your phone to your PC. Once paired, every byte — inputs, audio, screen — flows directly between the two devices and never touches our servers.
- **No account. No telemetry.** — No sign-up, no email collection, no analytics ping by default.
- **Free while in beta** — No card, no nag screens. Uninstall takes everything with it.

---

## Who it's for

| | |
|--|--|
| 🛋️ **Couch gaming** | TV mirrored from your PC, phone in hand. No cables, no extra hardware. |
| 👥 **Game nights** | Friends walk in, scan a QR, they're player two. Skip the controller hunt. |
| ✈️ **Travel & remote play** | Hotel WiFi, parents' house, anywhere with internet — your PC is one QR away. |
| 👶 **Kid-friendly** | They use their phones or tablets, not an extra controller. Custom layouts for small hands. |
| 🕹️ **Retro & emulators** | NES, SNES, N64, fight stick layouts ship in the box. Built for emulator front-ends. |
| 🎮 **Streamers** | Capture a single game window so your second monitor and notifications stay off-stream. |

---

## Download

| File | When to use |
|--|--|
| **`padlinq-setup-X.Y.Z.exe`** | Recommended for most users. Installs the ViGEmBus driver and registers a Start Menu shortcut. |
| **`padlinq-portable-X.Y.Z.exe`** | Self-contained single executable. Runs without installing. ViGEmBus must already be present (the admin UI will prompt if not). |
| **`padlinq-helper-X.Y.Z-windows-amd64.zip`** | Raw binaries for power users or silent-install deployment. |

> **Requirements:** Windows 10 or 11 (64-bit) · ~8 MB installer · Uninstall anytime

[**→ Download latest release**](https://github.com/Triomax66/padlinq-dist/releases/latest)

---

## FAQ

<details>
<summary>Is it really free?</summary>

Yes — free while in beta, with no account, no card, and no upsell screens. We'll be transparent well before that ever changes.
</details>

<details>
<summary>What do I need?</summary>

A Windows 10/11 PC, an internet connection, and any phone with a browser. The phone does not have to be on the same WiFi as the PC.
</details>

<details>
<summary>Do I need to install an app on my phone?</summary>

No. Your phone just loads a webpage. iPhone users can tap "Add to Home Screen" for a fullscreen, app-like experience — still no App Store involved.
</details>

<details>
<summary>Does it work without internet?</summary>

Yes, with the `--lan-only` flag. The helper serves the admin page on your LAN and pairs phones on the same WiFi — no relay involved. The default online mode uses a small signalling relay to introduce the two devices, then gets out of the way; inputs flow peer-to-peer over WebRTC in both modes.
</details>

<details>
<summary>How does screen streaming work?</summary>

Enable it in the admin panel and your PC screen (or a single window) appears live behind the on-screen controller. The stream is captured via Windows Graphics Capture and sent peer-to-peer — your video never passes through our servers.
</details>

<details>
<summary>How many controllers can I connect?</summary>

Up to eight phones per PC. Each phone gets its own session code from the admin page, and you can force a layout or button skin per slot.
</details>

<details>
<summary>What about latency?</summary>

Inputs go peer-to-peer over a WebRTC data channel. On the same WiFi you'll typically see single-digit milliseconds; across networks, it's roughly your phone's ping to your PC.
</details>

<details>
<summary>Does it work on macOS or Linux?</summary>

Linux support is in beta (uinput backend). macOS support is planned but not yet shipped.
</details>

---

<p align="center">
  <a href="https://padlinq.com">padlinq.com</a> &nbsp;·&nbsp;
  <a href="https://padlinq.com/privacy">Privacy</a>
</p>
