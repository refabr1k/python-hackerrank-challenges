# python-stuff
python snippets

## read & write json file
```python
import json
with open('data.json', 'w', encoding='utf-8') as f:
    json.dump(data, f, ensure_ascii=False, indent=4)
```

## validate for only digit/float
```python
if re.match("^[0-9]*\\.?[0-9]*$", amountStr):
    return str(round(float(amountStr),2))    
```

