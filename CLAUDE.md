# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a simple front-end-only project with no build tools, package manager, or test framework. All code lives in self-contained HTML files that can be opened directly in a browser.

## Running

Open any `.html` file directly in a browser — no server or build step required.

## Git Workflow

- Commit and push to GitHub after completing each piece of work. Never leave changes uncommitted.
- Use clean, descriptive commit messages that explain *why*, not just *what*.
- Remote: `origin` → `hamzclini2/tictactoeClaude` (GitHub, public).
- The `gh` CLI is installed at `/c/Program Files/GitHub CLI/gh.exe`.

## Architecture

- **tictactoe.html** — Single-file Tic Tac Toe game (HTML + CSS + JS embedded). Features a minimax AI opponent and a 2-player local mode.
