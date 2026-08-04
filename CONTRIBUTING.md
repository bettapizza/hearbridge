# Contributing to HearBridge

Thank you for helping make in-person communication more accessible.

## Before contributing

1. Read `PRIVACY.md`, `SECURITY.md`, and `docs/REGULATORY_AND_SAFETY.md`.
2. For hearing-device work, also read `docs/DEVICE_PROTOCOL_RESEARCH.md`.
3. Open or comment on an issue before beginning a large change.
4. Never include proprietary application binaries, extracted credentials, private recordings, medical records, or identifying transcripts.

## Development principles

- Accessibility is a release requirement, not a later enhancement.
- Captioning must remain useful without a hearing aid connected.
- Local processing is preferred over cloud processing.
- Audio and transcripts are not stored by default.
- Production device commands must be explicitly allowlisted by model and firmware.
- Experimental device writes must never be enabled in a public release by accident.

## Pull requests

Include:

- What changed and why
- Screenshots or recordings for UI changes, with no private conversation content
- Accessibility impact
- Privacy and safety impact
- Tests performed
- Device model and firmware, when relevant

## Code of conduct

Be respectful, accessible, and patient. Do not question another person's disability, communication preferences, hearing-aid use, or need for accommodations.
