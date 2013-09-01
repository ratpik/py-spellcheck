py-spellcheck
=============
Based on http://norvig.com/spell-correct.html

A simple pure python spellcheck library for a custom (small) dictionary. 
Config
======
Assign `DICTIONARY` inside `config.py` to your dictionary file.

A dictionary file is a list of names in the English Alphabet.

Eg. data/cities.txt

Mumbai
Delhi
Bangalore
Chennai
Kolkata


Usage
=====

```
>>> from spellcheck import correct
>>> correct('Mumbia')
'mumbai'
```
