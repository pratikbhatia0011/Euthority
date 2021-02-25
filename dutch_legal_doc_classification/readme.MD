This task was classification of Dutch legal documents into 8 categories, essentially a multi-label multi-class problem.
Out of 8 categories, one is 'No_EU_law' - implying the document isn't citing any EU law. If the document belonged to 
this category, then all the other classes were not possible.

On the other hand, if the document isn't 'No_EU_law', then it could be any one or more of the other classes 
at the same time.

Due to highly imbalanced and small dataset - direct attempt at multi-label classification failed. 
Hence the problem was approached as a binary classification one for each class which yielded good results.
