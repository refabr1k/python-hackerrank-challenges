# python-stuff
python snippets

## write json file
```python
#write data.json
import json
with open('data.json', 'w', encoding='utf-8') as f:
    json.dump(data, f, ensure_ascii=False, indent=4)
```

## read json file and print all key values
```python
with open('data.json') as json_file:
    data = json.load(json_file)
    
    #print all key value of json files
    for key, value in data.items():
        print(key,value)
```


## validate for only digit/float
```python
if re.match("^[0-9]*\\.?[0-9]*$", amountStr):
    return str(round(float(amountStr),2))    
```

