# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A single-file Pomodoro timer web app (`pomodoro-timer/index.html`) with work/break/long-break modes, task tracking, session log, and Web Audio API beep notifications. `serve.ps1` runs a lightweight local HTTP server on port 3333.

## Development

```powershell
# Start local server
.\serve.ps1
# Then open http://localhost:3333
```

## Security Rules

- Never read `.env`, API keys, private keys, tokens, passwords, or credentials. Handle variable names only, never values.
- Before running any Bash command that might display secrets, explain the command and get approval first.
- Before `git add` or `git push`, always show the list of files to be staged/pushed and wait for explicit confirmation.
- Never execute operations that affect production environments or incur billing charges without explicit user approval.

# コンプライアンス
@../_common/privacy-law-japan.md