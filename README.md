# psychonauts.py
Web-API for [psychonauts-api.netlify.app](https://psychonauts-api.netlify.app) tribute to the cult classic game

## Example
```python
from psychonauts import Psychonauts

psychonauts = Psychonauts()
character_info = psychonauts.get_character_by_name(name="")
print(character_info)
```
