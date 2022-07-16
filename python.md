##  Resources
- https://www.python.org/
- https://docs.python.org/3/
- https://realpython.com/

##  Operators

| symbol | name |
| ------- | ------ |
| `+` | addition |
| `+=` | add and assign |
| `-` | subtraction |
| `-=` | sub and assign |
| `*` | muliplication |
| `/` | float division |
| `**` | exponentiation |
| `%` | modulo |
| `//` | integer division |

##  Comments

```python

  # multiline comments are just consecutive single line comments
  # one after another

  # a single line comment
  print("hello") # a trailing comment


  """
  Docstrings can be multi or single line but have specific documentation
  purposes and shouldn't be used for random comments
  """
  
```


**resources**
- docstrings - https://peps.python.org/pep-0257/
- documenting python code - https://realpython.com/documenting-python-code/


## Conventions

```python

  snake_case_variables
  SCREAMING_SNAKE_CONSTANTS
  UpperCamelCaseClasses
  __double_under_things__
  "double quotes are okay"
  'single quotes are okay'
  "probably be 'consistent'"
  
```

## Data Types

| type | description |
| --- | --- |
| bool | True or False |
| NoneType | None, nothing, null/nil |
| int | Integers |
| float | Floating point numbers |
| str | string, sequence of characters |
| list | an ordered sequence of data types, dynamic array [1, 2, 3] |
| dict | a collection of key value pairs { key: value } |

- None - https://realpython.com/null-in-python/#understanding-null-in-python

### String

type is `str`

concatenate with `+` `"this" + " " + "that"`
interpolate with F-Strings or format

```python

  guess = 8
  # f"
  print(f"your guess of {guess} was incorrect!")
  # format
  print("you guess of {} was incorrect!".format(guess))

```

### Conditionals

```python
  if thing:
    do_stuff
  elif other_thing:
    do_other_stuff
  else:
    do_fallback
```

Be mindful of the trailing colon
Truthy/falsey is a thing
presence = truthy
empty string/0/None are falsey

### Comparisons

```python
  x = 1
  x == 1
  x != 1
  x is 1
  x < 1
  x > 1
  x <= 1
  x >= 1
```

`==` compares value and `is` compares identity in memory

https://realpython.com/courses/python-is-identity-vs-equality/#:~:text=The%20%3D%3D%20operator%20compares%20the,the%20same%20object%20in%20memory.

### Boolean Operators

```python
  and
  or
  not
```


### Casting types

```python
value = "3"
int(value) # 3
```