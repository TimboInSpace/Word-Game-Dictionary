# Word-Game-Dictionary
English dictionary, with proper nouns removed, and only containing letters a-z. Contains pluralizations.

### Contents
- **wordlist.txt** : 63325 words. Contains all words as described above.
- **wordlist-3-16.txt** : 63239 words. Contains wordlist.txt filtered for words of length 3 through 16 (inclusive).

### How the files were generated
Starting with `/usr/share/dict/words`, I used `grep` to filter out words I did not want to include. I removed all words containing uppercase letters, apostrophes, and the letters **Å**, **ê**, and **ö**. 

For the letter **é** I made (hopefully) tasteful substitutions or removals, based subjectively on how frequently the word is used in English. For example, I substituted "café" for "cafe", but chose to remove the word "outré".
