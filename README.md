# Homebrew tap for Dispatch

[Dispatch](https://rundispatch.sh) at rundispatch.sh is the local CLI for
validating coding-agent changes.

```sh
brew install rundispatch/tap/dispatch
dispatch version
```

Prebuilt for macOS on Apple Silicon and Linux x86_64. Upgrade with
`brew upgrade dispatch`.

The formula is generated from each release's `SHA256SUMS` by
`scripts/update-formula.sh`. A scheduled workflow moves it to every new
[Dispatch release](https://github.com/rundispatch/dispatch/releases), then
installs it from this tap on macOS and Linux and runs its test.
