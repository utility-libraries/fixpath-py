# FixPath.py
 fix incorrect user-path-inputs


# Usage
```python
from fixpath import findpath

path = input("Enter path: ")
# path = 'scr/fipath'
path = findpath(path)
# path = 'src/fixpath'
```
- `findpath('REAMDE.md')` -> `README.md`
- `findpath('LIECNSE')` -> `LICENSE`

# Comment
tested in windows but should also work under linux
