<div align="center">
  <img src="assets/hearbridge-mark.svg" width="120" alt="HearBridge logo">

# HearBridge

**Private, accessible in-person captions and responsible hearing-device controls.**

![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)
![Status](https://img.shields.io/badge/status-early%20prototype-orange.svg)
![Platform](https://img.shields.io/badge/platform-Android-brightgreen.svg)

</div>

HearBridge is an open-source accessibility project from **OpenWearable Revival**. Its goal is to help people with compatible hearing aids use private, full-screen captions during in-person conversations and eventually access a carefully limited set of hearing-device controls.

> [!IMPORTANT]
> HearBridge is an early software prototype. The current Android project demonstrates the captioning interface with simulated text. It does **not** yet perform live transcription or communicate with hearing aids.

## Why HearBridge?

Many hearing-device companion apps are closed, manufacturer-specific, account-dependent, or focused primarily on device settings. HearBridge starts with a universal need: making face-to-face conversations easier to follow.

The project is designed around four principles:

- **Accessibility first:** large text, high contrast, landscape meeting mode, and simple controls.
- **Private by default:** local processing is the target; audio and transcripts should not be retained without clear consent.
- **Safe device control:** no audiogram fitting, firmware modification, unrestricted gain changes, or undocumented write commands in production builds.
- **Open collaboration:** compatibility research, accessibility decisions, and limitations are documented publicly.

## Planned capabilities

### In-person captions

- Full-screen, resizable captions
- High-contrast light and dark modes
- Landscape meeting and presentation modes
- Hold, clear, and explicitly save transcript actions
- Local speech recognition using an on-device engine
- Vocabulary support for names and technical terms
- Multilingual transcription where the selected model supports it

### Hearing-device companion features

- Connection state
- Left and right battery information where available
- Mute and volume controls on explicitly supported devices
- Selection of programs already installed by a hearing professional
- Restore-previous-state protection
- A public model and firmware compatibility matrix

## Current repository status

Included today:

- Android Jetpack Compose UI prototype
- Simulated caption engine for interface testing
- Accessibility, privacy, security, and safety documentation
- Device-protocol research rules
- Public roadmap and contribution templates
- Initial vector identity assets

Not included yet:

- Production speech recognition
- Bluetooth hearing-aid discovery or control
- Stored transcripts
- Cloud services, user accounts, analytics, or advertising

## Run the Android prototype

Requirements:

- Android Studio
- JDK 17
- A recent Android SDK

1. Clone this repository.
2. Open the `android` folder in Android Studio.
3. Let Android Studio sync the project.
4. Run the `app` configuration on an Android 8.0 or newer emulator/device.

The repository does not include a generated Gradle wrapper JAR. Generate it from the `android` directory with your installed Gradle version:

```bash
gradle wrapper
```

## Repository map

```text
hearbridge/
├── android/                 Android application prototype
├── assets/                  Project identity assets
├── docs/                    Architecture, accessibility, and research guidance
├── .github/                 Issue and pull-request templates
├── CONTRIBUTING.md
├── PRIVACY.md
├── ROADMAP.md
├── SECURITY.md
└── LICENSE
```

## Safety boundary

HearBridge is not a replacement for an audiologist, hearing professional, medical evaluation, emergency alerting system, or manufacturer-supported fitting software. See [Regulatory and Safety Boundaries](docs/REGULATORY_AND_SAFETY.md).

## Trademark and affiliation

HearBridge is independent and is not affiliated with, sponsored by, or endorsed by Phonak, Sonova, or any other hearing-device manufacturer. Product and company names belong to their respective owners and are used only to describe compatibility.

## Contributing

Start with [CONTRIBUTING.md](CONTRIBUTING.md), review the [device research rules](docs/DEVICE_PROTOCOL_RESEARCH.md), and choose an item from the [roadmap](ROADMAP.md). Accessibility feedback from hearing-aid users, Deaf and hard-of-hearing contributors, audiologists, captioners, mobile developers, and privacy researchers is especially valuable.

## License

Licensed under the [Apache License 2.0](LICENSE). Third-party speech models and libraries may use separate licenses and must be documented before distribution.
