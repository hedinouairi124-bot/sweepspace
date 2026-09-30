# Security

## Reporting a problem

Please don't open a public issue for security problems. Use **[Report a vulnerability](https://github.com/hedinouairi124-bot/sweepspace/security/advisories/new)** on this repository instead, so the report stays private until a fix ships.

Include the Sweepspace version, what you did, and what happened. We'll reply as soon as we can.

## Supported versions

Only the latest release gets security fixes.

## Checking a download

Every release lists the SHA-256 hash of its installer in `SHA256SUMS.txt`. In PowerShell:

```powershell
Get-FileHash .\Sweepspace_0.1.0_x64-setup.exe
```

Download Sweepspace only from [the releases page](https://github.com/hedinouairi124-bot/sweepspace/releases) or [sweepspace.pages.dev](https://sweepspace.pages.dev).
