# python-stuff
python snippets

## read & write json file
```python
import json
with open('data.json', 'w', encoding='utf-8') as f:
    json.dump(data, f, ensure_ascii=False, indent=4)
```
