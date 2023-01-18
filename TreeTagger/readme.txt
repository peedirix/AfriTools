=== AfriTools: POS tagging and lemmatization ===

This folder contains a TreeTagger model (parameter file) trained on the Taalkommissie corpus (about 56M tokens), while for lexicalized words limiting the tags to a manually checked lexicon of about 283K tokens.

It will need TreeTagger (Schmid, 1994) to do the actual tagging. TreeTagger can be found on:
https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/
You should the combined base and normalization lexicons in the lexicon directory as 'Auxiliary lexicon'. Also use the build-in tokenization options and use hyphen heuristics. However, before running the tagger, you should run the tokenizer script in the tokenizer folder with the --multiword option in order to introduce the necessary multi-words.


The tag set used is a slightly simplified form of Pilon (2005). A description will be added in a separated file.

A reference to cite this work will be added.

References:

Peter Dirix (2023). "The need for a larger Afrikaans treebank." In: Ian Bekker and Theresa Biberauer (eds.), "Ex Africa semper aliquid novi: Linguistic shorts in honour of Andries Coetzee on his 50th birthday", Stellenbosch Papers in Linguistics Plus (2023, to appear).
Suléne Pilon (2005). "Outomatiese Afrikaanse woordsoortetikettering." Master's thesis, North-West University, Potchefstroom.
Helmut Schmid (1994), "Probabilistic Part-of-Speech Tagging Using Decision Trees." In: Proceedings of International Conference on New Methods in Language Processing, Manchester, UK.


