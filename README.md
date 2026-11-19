# juggle-ales-8k-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m juggle_ales_8k_kit.cli --help
```

```python
from juggle_ales_8k_kit.core import JuggleAles8kTool

tool = JuggleAles8kTool()
print(tool)
```

## Layout

```
juggle_ales_8k_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 juggle-ales-8k
