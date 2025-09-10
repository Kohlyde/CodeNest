# SECURITY.md
# Security Policy

## Threat Model
- Attacker does not have your password.
- Browser/device compromise is out of scope.
- Network attackers: no effect; app is offline.

## Protections
- AES-GCM-256 with PBKDF2-SHA256 key derivation.
- Encrypted vault at rest; encrypted exports/backups.
- Optional Backup Folder writes encrypted artifacts only.

## Reporting
Security concerns: open a private issue or email security@codenest.io.
