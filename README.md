# Pocket Alert Homebrew Tap

Homebrew formulae for [Pocket Alert](https://pocketalert.app): push notifications to your phone from the terminal, scripts and CI.

## Install

```bash
brew install pocketalert/tap/pocketalert
```

Or tap first, then install by name:

```bash
brew tap pocketalert/tap
brew install pocketalert
```

Shell completions for bash, zsh and fish are installed automatically.

## Get started

```bash
pocketalert auth                                   # paste your API key
pocketalert send "Deploy finished" "v1.4.2 is live"
pocketalert exec -- make release                   # push when a long job ends
```

Create an API key at [pocketalert.app/account/apikeys](https://pocketalert.app/account/apikeys).

## Update

```bash
brew upgrade pocketalert
```

## Formulae

| Formula | Description |
|---|---|
| `pocketalert` | [Pocket Alert CLI](https://github.com/PocketAlert/cli) |

## Links

- CLI source and releases: [github.com/PocketAlert/cli](https://github.com/PocketAlert/cli)
- Documentation: [info.pocketalert.app/cli](https://info.pocketalert.app/cli)
- Other install options (script, Go, manual download): see the [CLI README](https://github.com/PocketAlert/cli#install)
