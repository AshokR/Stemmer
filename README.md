# Stemmer
This is my attempt at creating the first part of a rule based Tamil stemmer - it only handles nouns and verbs for now. I am using the following resources and thank them for the same:
 - Python 3.12
 - The list of Tamil nouns, unique_sorted_noun_master.txt, from [Kaniyam Foundation](https://github.com/KaniyamFoundation/all_tamil_nouns).
 - Bloom filter to check whether a given word is in the list of lexicon words: [pybloom_live](https://github.com/joseph-fox/python-bloomfilter).
 - The Flowchart of Tamil Noun and Verb Forms is from [AU-KBC கணக்கீட்டு மொழியியல் ஆராய்ச்சி குழு](https://www.au-kbc.org/nlp/).
 - The list of Tamil verbs is extracted from the crea.babylon file shared by [stardict-tamil site](https://github.com/indic-dict/stardict-tamil).
