# Daalu CLI

The **`daalu`** command-line coding agent — chat with Daalu's sovereign coding
model from any local project, right in your terminal.

## Install

**Linux / macOS**

```sh
curl -fsSL https://get.daalu.io/install.sh | sh
```

**Windows (PowerShell)**

```powershell
irm https://get.daalu.io/install.ps1 | iex
```

**Homebrew**

```sh
brew install daalu-io/tap/daalu
```

The installer downloads the single-file `daalu` binary for your platform from
the [latest release](https://github.com/daalu-io/cli/releases/latest) — no
Python required.

## Use

```sh
daalu login                  # browser device-flow login
cd ~/your/project && daalu   # the agent, over your local code
```

`daalu --help` for everything.

---

This repository hosts the **installer and prebuilt binaries** only. The Daalu
CLI is proprietary software © Daalu.
