# koda

Personal command-line coding-agent runtime by [@xinquiry](https://github.com/xinquiry).
Distributed as **prebuilt binaries only** — the source is not publicly available.

## License

Koda is proprietary software. Use is permitted for **personal, non-commercial
purposes only**. Redistribution, modification, and reverse engineering are
prohibited. For commercial use, please contact the author.

See [`LICENSE`](LICENSE) — the same file is bundled inside every release tarball.

## Install

Shell (macOS & Linux):

```sh
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/xinquiry/koda-hub/releases/latest/download/koda-installer.sh | sh
```

Homebrew (macOS):

```sh
brew install xinquiry/tap/koda
```

## Supported platforms

- Apple Silicon macOS (`aarch64-apple-darwin`)
- ARM64 Linux, static musl (`aarch64-unknown-linux-musl`)
- x86_64 Linux, static musl (`x86_64-unknown-linux-musl`)

Intel Mac and Windows are not currently supported.

## Support

This is a personal project maintained on a best-effort basis. There is no
warranty, no service-level agreement, and no roadmap commitment. Bug reports
are welcome as issues on this repository; response time depends on my
availability.
