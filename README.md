# scoop-bucket

[Scoop](https://scoop.sh) bucket for Windows builds of tools by [aovestdipaperino](https://github.com/aovestdipaperino).

## Install

```powershell
scoop bucket add aovestdipaperino https://github.com/aovestdipaperino/scoop-bucket
scoop install tokensave
```

## Manifests

| Manifest | Description |
|---|---|
| `tokensave` | Code intelligence tool that builds semantic knowledge graphs from source code (x64 and arm64) |
| `tokensave-beta` | Beta channel of tokensave |
| `oronzo` | A toolkit for Claude Code sessions |

Each manifest points at the Windows zip attached to the project's GitHub release and uses `checkver` and `autoupdate` to track new versions. For macOS and Linux, see [homebrew-tap](https://github.com/aovestdipaperino/homebrew-tap).
