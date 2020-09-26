# Json Check

## Commands

Use this module to check if json structure is equal to python dict.


## Usage

```python

from json_checker import json_checker

is_equal, msg = json_checker.check_from_file('example.json', {"a": 1, "b": 2})

```


## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
