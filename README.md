This is a python implementation of TextRank for keyword and sentence extraction as done in http://acl.ldc.upenn.edu/acl2004/emnlp/pdf/Mihalcea.pdf. However, this implementation uses Levenshtein Distance as the relation between text units.

 - 100 word summary
 - Number of keywords extracted is relative to the size of the text (a third of the number of nodes in the graph)
 - Adjacent keywords in the text are concatenated into keyphrases

Dependencies
============
Networkx - http://networkx.github.io/download.html
NLTK 3.0 - http://nltk.org/install.html
Numpy - http://sourceforge.net/projects/numpy/files/


