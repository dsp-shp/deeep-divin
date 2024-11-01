> *"My summary on [Python 3 docs](https://docs.python.org/3/library/index.html)"*

## Built-in types
- Numeric (int, float, complex)
- Bool (bool)
- Iterator
- Generator
- Sequences (list, tuple, range)
- Text (str)
- Bytes (bytes, bytearray, memoryview)
- Set (set, frozenset)
- Mapping (dict)
- Other (module, class, code, type, None, NotImplemented, ...)

## Built-in exceptions
- The one should use Exception instead of BaseException class for inheritance
- ExceptionGroups - used for raising multiple unrelated exceptions (```except*```)
- Watch [this](https://docs.python.org/3/library/exceptions.html#exception-hierarchy) for exception list and hierarchy

## Text processing services

### ```string```
- Has usefull symbol colletions constants: ascii (lower & upper), digits, punctuation
- The one can realize it's own ```Formatter``` class for string formatting cases
- The one can create ```Template``` and fill it with substitutions

### ```re```
- Has multiple regex flags constants (```MULTILINE```, ```IGNORECASE```, ...)
- Has ```Pattern``` & ```Match``` objects defined
- Has main regex functions: ```search, match, split, findall, ...```

### ```difflib```
- Has ```Differ``` class & ```context_diff, ndiff, ...``` functions defined

### ```textwrap```
- Has some usefull text-related functions: ```wrap, fill, shorten, ...```

### ```unicode``` & ```stringprep```
...

### ```readline``` & ```rlcompleter```
- Defines a number of functions to facilitate completion and reading/writing of history files from the Python interpreter

## Binary data services

### ```struct``` & ```codecs```
...

## Data types
