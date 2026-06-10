# Daily Paper

## Local Setup

```bash
uv sync
uv run python daily_arxiv.py --config_path config.yaml
```

Update paper/code links only:

```bash
uv run python daily_arxiv.py --config_path config.yaml --update_paper_links
```
