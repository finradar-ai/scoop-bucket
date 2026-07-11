# scoop-bucket

Scoop bucket for FinRadar tools.

## Install

```powershell
scoop bucket add finradar https://github.com/finradar-ai/scoop-bucket
scoop install finradar
```

This installs the `finradar` CLI — a command-line client for the
[FinRadar](https://api.finradar.ai/integrations/cli) REST API.

## Update

```powershell
scoop update finradar
```

## Source

Binaries are released from [finradar-ai/cli](https://github.com/finradar-ai/cli).
Manifest is patched automatically by the release CI on every `cli-v*` tag.
