# koda-releases

Public host for koda release artifacts. The koda source lives in a private
repository; prebuilt binaries, install scripts, and checksums for every
tagged release are attached to the GitHub Releases on this repo.

## Install

Shell:

```sh
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/xinquiry/koda-releases/releases/latest/download/koda-installer.sh | sh
```

Homebrew:

```sh
brew install xinquiry/tap/koda
```

## Supported platforms

- Apple Silicon macOS (`aarch64-apple-darwin`)
- ARM64 Linux, static musl (`aarch64-unknown-linux-musl`)
- x86_64 Linux, static musl (`x86_64-unknown-linux-musl`)
