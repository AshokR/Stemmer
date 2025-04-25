# Stemmer
This is my attempt at creating the first part of a rule based Tamil stemmer - it only handles nouns for now. I am using the following resources and thank them for the same:
 - Python 3.12
 - List of Tamil nouns, unique_sorted_noun_master.txt, from [Kaniyam Foundation](https://github.com/KaniyamFoundation/all_tamil_nouns).
 - Bloom filter to check whether a word is in the list of nouns: [pybloom_live](https://github.com/joseph-fox/python-bloomfilter).
 - The Flowchart of Tamil Noun Forms is from AU-KBC.
