# <img src="https://psychonauts-api.netlify.app/static/media/psychonauts-logo.741d0b4d.png" width="80" style="vertical-align:middle;" /> psychonauts.py

> Web-API for [Psychonauts API](https://psychonauts-api.netlify.app) browse characters and psi powers from the Psychonauts game universe.

## Quick Start
```python
from psychonauts import Psychonauts

ps = Psychonauts()
print(ps.get_all_characters())
```

---

## Characters

| Method | Description |
|--------|-------------|
| `get_all_characters(limit)` | Get all characters |
| `get_character_by_name(name)` | Find a character by name |
| `get_character_by_gender(gender)` | Filter characters by gender |

## Psi Powers

| Method | Description |
|--------|-------------|
| `get_all_psi_powers(limit)` | Get all psi powers |
| `get_psi_power_by_name(name)` | Find a psi power by name |
