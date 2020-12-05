# Semantic Table Retrieval using Keyword and Table Queries

This repository contains resources developed within the following paper:

> S. Zhang and K. Balog. Semantic Table Retrieval using Keyword and Table Queries. In: *ACM Transactions on the Web (TWEB)*, 2021.


## Test collection

The table corpus is [WikiTables](http://websail-fe.cs.northwestern.edu/TabEL/), which comprises 1.6M tables extracted from Wikipedia. We proproceeed it and make it public downloadable [here](http://iai.group/downloads/smart_table/WP_tables.zip).

The `data/queries.txt` file contains the search queries. Queries #1-#30 queries constitute *Query subset 1 (QS-1)*, queries #31-#60 constitute *Query subset 2 (QS-2)*.

The `data/qrels.txt` file contains the relevance assessments (in TREC qrels format).  

## Data

We utilize word2vec trained on Google news, and you can find it [here](https://github.com/mmihaltz/word2vec-GoogleNews-vectors). You can find the graph embeddings [here](http://data.dws.informatik.uni-mannheim.de/rdf2vec/).




The evaluation scores are reported using [trec_eval](https://github.com/usnistgov/trec_eval).


## Citation
```
@inproceedings{Zhang:2021:STR,
    author = {Zhang, Shuo and Balog, Krisztian},
    title = {Semantic Table Retrieval using Keyword and Table Queries},
    booktitle = {ACM Transactions on the Web},
    year = {2021},
    pages = {},
}
```

## Contact
If you have any questions, please contact Shuo Zhang at imsure318@gmail.com.
