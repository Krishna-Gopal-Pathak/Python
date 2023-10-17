# Dictionary
- Dictionary is a collection which is ordered** and changeable. No duplicate members.
- Dictionaries are used to store data values in key:value pairs.
```
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)
```
<b>Output: {'brand': 'Ford', 'model': 'Mustang', 'year': 1964}</b>
##
```
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict["brand"])
```
<b>Output: Ford</b>
```
# No duplicate members. Dictionaries cannot have two items with the same key. Duplicate values will overwrite existing values
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964,
  "year": 2020
}
print(thisdict)
```
<b>Output: {'brand': 'Ford', 'model': 'Mustang', 'year': 2020}</b>

