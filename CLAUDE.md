# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Status

This is a new, empty project. Update this file once the project structure and toolchain are established.

## Security Rules

- Never read `.env`, API keys, private keys, tokens, passwords, or credentials. Handle variable names only, never values.
- Before running any Bash command that might display secrets, explain the command and get approval first.
- Before `git add` or `git push`, always show the list of files to be staged/pushed and wait for explicit confirmation.
- Never execute operations that affect production environments or incur billing charges without explicit user approval.
