# MSGS-1234
Monosemous Synonymy Gold Standard

This gold standard contains 112534 noun-noun-pairs together with a binary indicator whether the nouns can be used synonymously in a strong-from interpretation, i.e. the noun has n meanings that are all shared with the other noun. 

The gold standard does contain polysemous words for negative annotations but all positive examples are monosemous. As a starting points, all 541 nouns of the McRae et al. feature norms were used. The data set was chosen because all words are visually perceivable, the degree of abstraction is low and the words are likely to be monosemous. All nouns in the gold standard can be found on WordNet. 

A positive match between two words was annotated when the terms in question are members of the same synset(s) and are exposed to the synset(s) in question exclusively. The words doorknob and doorhandle, for instance, are both used in one synset (which is their only one) with the explanatory text stating "a knob used to release the catch when opening a door". Therefore, the two concepts are added to the gold standard as a positive example.<br/>
Negative matches were chosen by selecting related nouns according to the word2vec methodology utilizing Google's [publicly available](https://code.google.com/archive/p/word2vec/) pre-trained entity vectors. The criterion for a negative annotation was that the related word does not occur in any synset of the other word. 

All annotations were checked by a second reviewer and only added when consent existed concerning the word pair and its label. In total, there are 360 positive and 874 negative annotations. The chosen structure of the gold standard makes it possible that MSGS-1234 can also be viewed as a regular synonymy gold standard with very strong synonymy ties and can also be used in other contexts.

Feel free to use this gold standard for your research and if you have any questions. 
