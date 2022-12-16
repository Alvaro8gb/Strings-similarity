# There are several ways to determine if two strings are similar in Python. 

## Spacy 

Example -> `spacy_s.ipynb`

## Diiflib 

You can use the ratio() function to compare two strings.

Example -> `difflib_s.ipynb`

## Levenshtein

Use the Levenshtein distance: The Levenshtein distance is a measure of the similarity between two strings, defined as the minimum number of single-character edits (insertions, deletions, or substitutions) required to transform one string into the other. You can use the distance() function from the python-Levenshtein library to compute the Levenshtein distance between two strings.

Examaple-> `leven_s.ipynb`

## Fuzzywuzzy
The fuzzywuzzy library provides a range of functions for performing fuzzy string matching, including the ratio() function, which returns a score between 0 and 100 indicating the similarity between two strings. 

Example -> `fuzzy_s.ipynb`