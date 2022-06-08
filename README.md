# codename-sci
Python library to encode strings into human-readable phrases. Docker-inspired scientist mode as well as color mode available.

## Example usage

You can choose different types of combinations of words, including the docker container naming made up of adjectives * scientist surnames. 


```
from scicodename import codenamize

codenamize("22-11-1991")
# untidy title
codenamize("22-11-1991", type="scientist")
# hungry curie
codenamize("22-11-1991", type="color")
# bumblebee

```
