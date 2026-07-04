# koda-releases

Public host for [koda](https://github.com/xinquiry/koda) release artifacts.

The koda source lives in a private repository. Prebuilt binaries, install
scripts, and checksums for every tagged release are attached to the GitHub
Releases on this repo.

## Install

Shell:

```sh
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/xinquiry/koda-releases/releases/latest/download/koda-cli-installer.sh | sh
```

Homebrew:

```sh
brew install xinquiry/tap/koda-cli
```

npm:

```sh
npm install -g @koda-ai/koda-cli
```
