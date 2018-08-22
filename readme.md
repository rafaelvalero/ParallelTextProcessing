I would like to process text in the most parallel possible way.
The library multiprocessing could give some errors, a possible way to overcome them is by using pathos.

Examples of errors and how to install pathos: https://kampta.github.io/Parallel-Processing-in-Python/

For this I provide here two jupyter notebooks:
1. parallelizing_text_processing.ipynb.
2. parallelizing_text_processing_pathos.ipynb . Using pathos.

Althought the results are the some in this case.

References:
 + Related questions online:
     + Parallization using sklearn and tfidfvectorizer: https://stackoverflow.com/questions/28396957/sklearn-tfidf-vectorizer-to-run-as-parallel-jobs   

 +  Really good answer to parallelize using dataframes in python: http://blog.adeel.io/2016/11/06/parallelize-pandas-map-or-apply/
  To re-do it using joblib: https://joblib.readthedocs.io/en/latest/auto_examples/parallel_memmap.html 