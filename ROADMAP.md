# HearBridge Roadmap

## Phase 0 — Foundation
- [x] Publish project vision and safety boundaries
- [x] Add Android Compose UI prototype
- [x] Add contribution, privacy, and security policies
- [ ] Recruit hearing-aid users and accessibility reviewers
- [ ] Establish automated Android build checks

## Phase 1 — Captioning MVP
- [ ] Capture microphone audio with explicit user consent
- [ ] Integrate a fully local transcription engine
- [ ] Display partial and final captions
- [ ] Add adjustable text size and contrast controls
- [ ] Add landscape meeting mode
- [ ] Add hold, clear, and optional save actions
- [ ] Verify no audio is retained by default

## Phase 2 — Captioning Quality
- [ ] Add voice activity detection
- [ ] Add vocabulary hints for names and technical terms
- [ ] Add multilingual model selection
- [ ] Add optional speaker separation where technically reliable
- [ ] Add accessibility testing and documented results

## Phase 3 — Device Discovery
- [ ] Build a simulated hearing-device adapter
- [ ] Detect supported Bluetooth services read-only
- [ ] Display connection state and safe device metadata
- [ ] Publish a model and firmware compatibility matrix

## Phase 4 — Carefully Limited Controls
- [ ] Create model-specific allowlists
- [ ] Add volume, mute, and existing-program selection only where verified
- [ ] Add restore-previous-state protection
- [ ] Add confirmation and experimental-feature warnings
- [ ] Perform safety and usability review before production release

## Explicitly Out of Scope
- Audiogram fitting
- Firmware flashing or modification
- Bypassing device authentication or safety controls
- Unrestricted gain or maximum-output changes
- Claims that HearBridge diagnoses, treats, or cures a condition
