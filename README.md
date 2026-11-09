# greet-release

A small Python greeting program.

Install Python 3.11 or later and uv, then run:

```sh
uv sync --locked
uv run --locked python greet.py Hee
uv run --locked python greet.py
uv run --locked pytest -q greet.py
```

This project follows Semantic Versioning (MAJOR.MINOR.PATCH).
