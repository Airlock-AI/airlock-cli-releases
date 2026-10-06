# Airlock CLI releases

Official release packages for Airlock's local security-scanning workspace.
The application source is maintained in a separate private repository.

The first public release is being prepared. Once published, install with:

```sh
curl -fsSL https://www.tryairlock.ai/install.sh | sh
```

Then open a project with `airlock /path/to/project`. New runs require account
pairing and an online credit check; accepted runs cost 10 Airlock credits.
Saved local reports remain available offline. Docker is required for isolated
source checks; `airlock doctor` reports the available tools.

Packages target macOS and glibc Linux on arm64 and x64. Releases include
SHA-256 checksums and per-platform installation/startup verification receipts.

Visit [Airlock](https://www.tryairlock.ai) for the hosted service.
