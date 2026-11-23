# Credits

The word data in this app was modified from the sources below: filtered, ranked,
shortened and combined. Application code is MIT. Word data is CC BY-SA 4.0 (see NOTICE).

## SUBTLEX-CH (word order)

Cai, Q., & Brysbaert, M. (2010). SUBTLEX-CH: Chinese Word and Character Frequencies
Based on Film Subtitles. PLoS ONE, 5(6), e10729. https://doi.org/10.1371/journal.pone.0010729

Only a derived word and rank are used. The raw frequency data is not included.
The word and rank list is published with the permission of Marc Brysbaert, given by email.

## CC-CEDICT (pinyin, meanings, measure words)

Community maintained free Chinese-English dictionary, published by MDBG.
Licence line in the file used: Creative Commons Attribution-ShareAlike 4.0 International License
https://creativecommons.org/licenses/by-sa/4.0/
CEDICT - Copyright (C) 1997, 1998 Paul Andrew Denisowski
https://cc-cedict.org/wiki/

Meanings were shortened and selected, and tone-mark pinyin was generated from them.

## English Wiktionary (parts of speech)

Part-of-speech labels (noun, verb and so on) come from the Chinese entries of English Wiktionary,
https://en.wiktionary.org, licensed CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/).
The data was taken from the machine-readable extract at https://kaikki.org, made with Wiktextract
(Tatu Ylonen, https://github.com/tatuylonen/wiktextract). Only the part-of-speech labels are used,
matched to each word's traditional form and reading; a word with no clear label shows none.
Words Wiktionary doesn't label use the part-of-speech tags in the HSK word list credited above. For a word
with several readings, only the tags that fit the reading the card teaches are kept (listed for review in
`data/review/parts_of_speech_readings.csv`).

## Tatoeba (example sentences and translations)

https://tatoeba.org, CC BY 2.0 FR. Each sentence in `data/sentences.json` keeps its Tatoeba
sentence numbers and contributor names in its `attribution` field. Pinyin was added here
and is not from Tatoeba.

## Make Me a Hanzi (character breakdowns)

https://github.com/skishore/makemeahanzi. `data/components.json` is adapted from its `dictionary.txt`,
which is derived from Unihan and CJKlib and licensed under the GNU LGPL, version 3 or later. The
licence and the Unicode notice are in `data/LGPL-3.0.txt`. Its stroke graphics are not used.

## Grammar cards

Written for this app, and not copied from any other source. Pattern names are ordinary grammar terms.

## Speaking phrases and topics

The starter phrases, topics and sentence starters were written for this app. Their pinyin was
generated here, and word links use the word list above.

## Written example sentences

Words the sentence collection has no example for have one or two sentences written for this app,
marked "Written for this app; unreviewed". Their pinyin was generated here and checked.

## Stories

The graded readers were written for this app and are not adapted from any published reader. Their
pinyin was generated here and checked, and word links use the word list above.

## HSK levels

Level numbers per word from https://github.com/drkameleon/complete-hsk-vocabulary (MIT label).
No official word list is included.
