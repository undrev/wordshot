# Contributing

You're encouraged to report the bugs by reporting an issue or translate the game and its vocabularies into your native language by pulling requests.

## Reporting Issues

Game bugs and translation mistakes reports are appreciated. Please, follow the guidelines below.

### Guidelines for issue report

1. Search the issue tracker to see if the bug/mistake has been reported by someone else.
2. Report an issue. Don't forget to include some additional information (WORD SHOT version, Operating System version, steps to reproduce the issue, screen-shots and any other relevant details).

## Pull Requests

Your translations via pull requests are always welcome. Please note, not all pull requests may be accepted by various reasons. If in doubts, opening an issue beforehand allows to discuss the work before it begins, preventing wasted efforts.

By uploading/pulling requests a translation you agree to transfer the work to Undrev for using it free of charge, royalty-free, by any means. You also confirm that the work doesn't violates a law and any other third-party agreements.

### Translation Levels

If you want to add a new language support to the game, there are several levels of integration efforts (from easy to hard):

1. You may just want to translate the game's interface. To do so, translate the single [lng-en.txt](data/lng-en.txt) into your native language. [planned]
2. You may want to add your language to use it in a Word Typing game type. To do so, you need to add a new vocabulary file dic-XX-XX.txt, for example, by translating [dic-en-en.txt](data/dic-en-en.txt) into your native language.
3. You may want to add your language to use in a Word Typing and Word Translating game types. To do so, you need to translate at least 2 vocabulary files (the more language pairs the better): dic-en-XX.txt and dic-XX-en.txt into your native language.

For 2. and 3. a tiny char-XX.txt language letters mapping file is also required to add, [see the example](data/char-ru.txt).

### Guidelines for pull request

1. Create a new branch for each pull request
2. Correct existing translation or add a new one
3. Add your name in the file's header under the "Contributors/credits" ONLY if you want to be added into the game's credits section.
4. Make a single commit per pull request

### Hints & Advices

* The filename convention is as the follows: dic-XX-XX.txt where the XX (from/to) is a 2-symbols language code.

* A "--" is in a line is a comment, see how the file's header section looks like

* The file's header consists of some current vocabulary statistics (words length/counts; words total)

* The vocabulary is just a plain text file with pairs: "word = translation", each on a single line

* The vocabulary file has to be saved in UTF-8 encoding. In the Windows Notepad (Save as... - File type: TXT - Encoding: UTF-8) or in the Notepad++ (Encoding - Encode in UTF-8)

* The vocabulary statistics information gives you a hint, what kind of words need to be added. Keep the vocabulary balanced, if you see 3-length words count is 50 and others are 100+, an addition of more 3-letters words would be a good idea.


