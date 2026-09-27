*This project has been created as part of the 42 curriculum by vloth.*

# Call Me Maybe

Call Me Maybe is a Python project about constrained function calling with a
small language model.

## Python environment with uv

The project requires Python 3.12 or later and uses
[`uv`](https://docs.astral.sh/uv/) to manage its environment and dependencies.

Install `uv` if it is not already available:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Create or synchronize the virtual environment from `pyproject.toml` and
`uv.lock`:

```bash
uv sync
```

Run the current project entry point inside the managed environment:

```bash
uv run python -m src
```

Activating `.venv` manually is optional. When needed, use:

```bash
source .venv/bin/activate
```

To add a new dependency and update the lock file:

```bash
uv add <package-name>
```
