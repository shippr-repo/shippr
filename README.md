# News Fiction

## Layout

```
episodes/           Latest episodes only (current working set)
archive/episodes/   Older episodes, moved here when replaced
docs/               Project Markdown files (concept, style guide, notes)
templates/          Episode and prompt templates
scripts/            Python scripts
ledgers/            Ledgers (episode log, continuity, sources)
data/               Input data (e.g. news sources) used by the scripts
```

## Conventions

- `episodes/` only ever holds the most recent episodes; move older ones to
  `archive/episodes/` instead of deleting them.
- Name episodes with a sortable prefix, e.g. `ep-0001-title.md`.

## Scripts

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
