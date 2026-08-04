# Security Policy

## Reporting a vulnerability

Please do not publicly disclose an exploitable issue involving hearing-device commands, sensitive transcripts, authentication, or unsafe state changes before maintainers have had a reasonable opportunity to address it.

Open a private GitHub security advisory for this repository when available. Do not include real private conversations, medical information, device credentials, or extracted manufacturer secrets.

## Supported versions

HearBridge is currently an early prototype. No release is approved for clinical, safety-critical, or emergency use.

## Security priorities

- Prevent unintended hearing-device writes
- Keep experimental adapters disabled by default
- Encrypt saved transcript data
- Minimize permissions
- Avoid unnecessary network access
- Reject unknown commands, models, and firmware versions
