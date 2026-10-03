# AGENTS.md

## Project Overview

Single-file static HTML tic-tac-toe game (Portuguese: "Jogo da Velha PRO"). No build step, no backend, no dependencies.

## Running

```bash
docker compose -f docker-compose.base44.yml up -d
```

Serves `jogo_da_velha.html` as `index.html` via nginx on port 3000.

## Editing

Edit `jogo_da_velha.html` directly. Changes are live immediately (nginx serves the bind-mounted file). Call `reload_preview` after edits to refresh the preview iframe.

## Secrets

None required.
