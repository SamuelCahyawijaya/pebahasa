PEBAHASA
========

**Notes:** This is a Python3 compatible version of Indonesian POS Tagger ported from https://github.com/pebbie/pebahasa, please check `pos_tagging_example.ipynb` for a simple example on how to use it.

Indonesian NLP (Natural Language Processing) web service using `bottle <http://github.com/defnull/bottle>`_
for now it's still an early morphological operation to break down a lexicon into phonemes

added Oct 2011: 
- HMM based POS Tagger, based on "Alfan Farizki Wicaksono, Ayu Purwarianti. HMM Based POS Tagger for Bahasa Indonesia. On Proceedings of 4th International MALINDO (Malay - Indonesian Language) Workshop. 2nd August 2010.", available `here <http://nlp.pebbie.net/tag>`_

added Feb 2012:
- single front-end
- html cleaning (html to text)
- sentence boundary detection
- simple extractive summarization
- term extraction (not working on GAE)
- chunking based on capitalization