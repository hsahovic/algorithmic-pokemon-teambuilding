## Algorithmic Pokémon Teambuilding (Gen 1 OU)

This repository contains the code for the blog post [Algorithmic Pokémon Teambuilding](https://sahovic.fr/algorithmic-pokemon-teambuilding).

### Repository contents

- `teambuilding.ipynb`: Main notebook. End-to-end pipeline: data → simulation → models → evaluations → exports.
- `teambuilding_gen1ou_data.json`: Saved output with win rates and model parameters produced by the notebook.
- `cache/`: Cached inputs/outputs (Smogon usage JSON and simulated battles) to avoid re-downloading/re-simulating.
- `pyproject.toml` / `uv.lock`: Project dependencies (PEP 621) and lockfile for `uv`.
- `.python-version`: Target Python version (3.13).


