# peck-62spoils-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m peck_62spoils_kit.cli --help
```

```python
from peck_62spoils_kit.core import Peck62spoilsTool

tool = Peck62spoilsTool()
print(tool)
```

## Layout

```
peck_62spoils_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 peck-62spoils
