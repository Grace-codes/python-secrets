# Python Secrets
Curated list of all the hidden jokes, easter eggs and secrets in Python


## Table of Contents
- [Easter Eggs](#easter-eggs)
- [Command Line](#command-line)


## Easter Eggs

### 1. Zen of Python
```py
import this
```

### 2. Easiest Hello World
```py
import __hello__
```

### 3. Braces in python?
```py
from __future__ import braces
  File "<stdin>", line 1
SyntaxError: not a chance
```

### 4. Hash of Infinity
```py
>>> hash(float('inf'))
314159
>>> hash(float('nan'))
0
```

### 5. Antigravity
```py
import antigravity
```

### 6. Friendly Language Uncle For Life
```py
>>> from __future__ import barry_as_FLUFL
>>> 1 != 3
  File "<stdin>", line 1
    1 != 3
       ^
SyntaxError: with Barry as BDFL, use '<>' instead of '!='
>>> 1 <> 3
True
```

## Command Line

### 1. CLI month calendar
```bash
python -m "calendar" 2021 7
``` 
For options: `python -m "calendar" --help`



