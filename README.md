# Dialogue Datasets

A collection of plain text datasets I have found. You can find a zip of all of them [here](https://drive.google.com/file/d/0BzfmodsY02j7VjJQTmNqMDFvVUE/view?usp=sharing). This contains:

## BNC Corpus
BNCCorpus.txt is the subset of the British National Corpus that is transcribed unscripted spoken dialogue, in plain text.

BNCSplitWordsCorpus.txt is the same except I used [this](http://stackoverflow.com/questions/8870261/how-to-split-text-withouBNCt-spaces-into-list-of-words) to split apart some of the words in the corpus because the original text had a lot of wordsthatwerecombinedlikethis.

I don't claim to have any liscensing/ownership of this, I just made it myself from parsing the raw xml dump so if I'm not allowed to distribute this just let me know and I can take it down.

## Twitter dialogue dataset

I made this one from parsing tweets and their replies. It contains conversations (2 or more tweets), each tweet is on a seperate line and there is three empty lines between each dialouge, and they are sorted by length of dialogue. TwitterConvCorpus.txt contains emojiis and such, TwitterLowerAsciiCorpus.txt contains only dialouges of length 4 or more, converted to lowercase (because most of the text is already lowercase becauce twitter) and all of the non-ascii characters removed.

## Movie Corpus

A collection of movie scripts, I got this from [here](https://github.com/suriyadeepan/practical_seq2seq)
