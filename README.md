# RevKeen Homebrew tap

Homebrew formulae for [the RevKeen CLI](https://github.com/RevKeen/cli) and future RevKeen command-line tools.

[![License: MIT](https://img.shields.io/badge/license-MIT-000?style=flat-square)](./LICENSE)
[![Docs](https://img.shields.io/badge/docs-docs.revkeen.com-000?style=flat-square)](https://docs.revkeen.com/docs/cli)

## Install the CLI

```bash
brew install revkeen/tap/revkeen
```

That's it. No `brew tap` step needed — Homebrew auto-taps on the first `install` from a scoped formula path.

Verify:

```bash
revkeen --version
```

## Available formulae

| Formula | What it installs | Docs |
|---------|------------------|------|
| `revkeen/tap/revkeen` | The RevKeen CLI — Go binary, macOS + Linux | [docs.revkeen.com/docs/cli](https://docs.revkeen.com/docs/cli) |

## Upgrading

```bash
brew upgrade revkeen
```

## Uninstalling

```bash
brew uninstall revkeen
brew untap revkeen/tap   # optional, removes the tap entirely
```

## How this tap is maintained

Formulae are generated automatically by [`goreleaser`](https://goreleaser.com/) on every CLI release. The source is in [RevKeen/cli](https://github.com/RevKeen/cli) — open issues there for CLI bugs.

Tap-specific issues (formula resolution, Homebrew metadata, tap discoverability) belong on this repo's [issue tracker](https://github.com/RevKeen/homebrew-tap/issues).

## License

[MIT](./LICENSE) — © RevKeen.
