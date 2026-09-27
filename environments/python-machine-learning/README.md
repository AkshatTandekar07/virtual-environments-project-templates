# Python Machine Learning Environment (uv)

A robust machine learning environment configuration utilizing `uv` for high-performance dependency resolution and caching. Includes PyTorch, TensorFlow, Keras, and essential data analysis libraries.

## Setup Instructions

1. Copy `pyproject.toml` to your target project directory.
2. Navigate to the project directory in your terminal.
3. Sync the environment using `uv` (this will automatically resolve dependencies, fetch the latest stable versions, and construct the `.venv` directory):
   ```bash
   uv sync
   ```

## Execution

`uv` manages the virtual environment inherently; manual activation is not required. Prefix execution commands with `uv run`.

**Launch Jupyter Notebook:**
```bash
uv run jupyter notebook
```

**Execute a Python Script:**
```bash
uv run python script.py
```
