# TunnelForge tap

Homebrew tap and Scoop bucket for the [TunnelForge](https://www.tunnelforge.com) CLI.

## macOS / Linux

```sh
brew install furkankulaber/tunnelforge/tunnelforge
tunnelforge version
```

## Windows

```powershell
scoop bucket add tunnelforge https://github.com/furkankulaber/homebrew-tunnelforge
scoop install tunnelforge/tunnelforge
```

Then authenticate with the token from your dashboard and start a tunnel:

```sh
tunnelforge auth <YOUR_TOKEN>
tunnelforge http 3000
```
