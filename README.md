# configs

Personal config files, synced with [Task](https://taskfile.dev).

## Layout

- `configs/ghostty/` — Ghostty config
- `configs/zed/` — Zed settings
- `Taskfile.yaml` — sync tasks

## Tasks

| Task | Action |
|------|--------|
| `task ghostty:pull` | Copy config from the Ghostty app into the repo |
| `task ghostty:push` | Copy config from the repo into the Ghostty app |
| `task zed:pull` | Copy settings from the Zed app into the repo |
| `task zed:push` | Copy settings from the repo into the Zed app |
