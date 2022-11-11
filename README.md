# Semantic Table Retrieval using Keyword and Table Queries

This repository contains resources developed within the following paper:

> S. Zhang and K. Balog. Semantic Table Retrieval using Keyword and Table Queries. In: *ACM Transactions on the Web (TWEB)*, 2021.

This work is an extension of

> S. Zhang and K. Balog. Ad Hoc Table Retrieval using Semantic Similarity. In: Proceedings of the Web Conference 2018 (WWW '18), April 2018.

The keyword table search utilizes the same benchmark as it, and we here supply additional test collection for table search using a table query.


## Test collection

The table corpus is [WikiTables](http://websail-fe.cs.northwestern.edu/TabEL/), which comprises 1.6M tables extracted from Wikipedia. We proproceeed it and make it public downloadable [here](https://drive.google.com/file/d/1rFWPZFT61Gnxdf2k6he72hKc4t7Tz4kr/view?usp=share_link).

The `data/*/queries.txt` file contains the search queries.

The `data/*/qrels.txt` file contains the relevance assessments (in TREC qrels format).  

## Data

We utilize word2vec trained on Google news, and you can find it [here](https://github.com/mmihaltz/word2vec-GoogleNews-vectors). You can find the graph embeddings [here](http://data.dws.informatik.uni-mannheim.de/rdf2vec/).




The evaluation scores are reported using [trec_eval](https://github.com/usnistgov/trec_eval).


## Citation
```
@article{Zhang:2021:STR,
  author = {Zhang, Shuo and Balog, Krisztian},
  title = {Semantic Table Retrieval Using Keyword and Table Queries},
  year = {2021},
  issue_date = {May 2021},
  volume = {15},
  number = {3},
  journal = {ACM Trans. Web},
  articleno = {11},
  numpages = {33}
}


```

## Contact
If you have any questions, please contact Shuo Zhang at imsure318@gmail.com.
