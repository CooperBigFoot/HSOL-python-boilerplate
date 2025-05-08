# Python Project Boilerplate

A quickstart Python boilerplate with Ruff pre-configured for formatting and linting. `uv` is used for project and environment management.

## Prerequisites

Ensure you have `uv` installed. If not, you can install it using `pipx`:

```bash
pipx install uv
```

(If you don't have `pipx`, install it first: `python3 -m pip install --user pipx` followed by `python3 -m pipx ensurepath`)

## Get Started

1. **Create and activate the virtual environment, then install dependencies:**

    * **macOS/Linux:**

        ```bash
        uv venv && source .venv/bin/activate && uv sync
        ```

    * **Windows (PowerShell):**

        ```powershell
        uv venv; .\.venv\Scripts\Activate.ps1; uv sync
        ```

    * **Windows (CMD):**

        ```cmd
        uv venv && .\.venv\Scripts\activate.bat && uv sync
        ```

This creates a virtual environment in `.venv/`, activates it, and installs/syncs dependencies from `pyproject.toml`.

Happy coding!
