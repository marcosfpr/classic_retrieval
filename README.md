[![PyPI version](https://badge.fury.io/py/matchup-ir.svg)](https://badge.fury.io/py/matchup-ir)
![build](https://github.com/marcosfpr/match_up_lib/workflows/build/badge.svg)
[![codecov](https://codecov.io/gh/marcosfpr/match_up_lib/branch/master/graph/badge.svg)](https://codecov.io/gh/marcosfpr/match_up_lib)

# MatchUp

PURE-Python IR library.

Nowadays, through search engines, it is common to make queries that have, as a result, a high number of references that do not meet their contexts. In order to provide relevant results, upon consultation, some models from the Information Retrieval area, called classics, were proposed: the Boolean, the Vector and the Probabilistic. In turn, with a view to improving the quality of the results generated by the application of the classic models of Information Retrieval, extended models of Information Retrieval were defined from them; among them, we have the Extended Boolean, the Generalized Vector and the Belief Network.
 
In 2018/1, the first version of the MatchUp tool was developed: a web tool for calculating similarity between a query, which may be a specific document or set of terms of interest to the user, and a collection of documents, enabling the generation of a list of documents from this collection that are relevant to the desired query. To calculate similarity, this version included the classic IR models and the extended Extended Boolean model. Through the analysis of the results of the experiments carried out, it was possible to notice that the Vector model, in general, presented the best results when compared to the other models implemented. However, MatchUp did not include the Generalized Vector and Belief Network extended models, which may present better results than the Vector Model. Therefore, this scientific initiation project has, as main objective, the development of version 2.0 of the MatchUp tool, in order to also include the extended models Generalized Vector and Belief Network. To validate version 2.0 of the MatchUp tool, experiments will be carried out, involving different collections of documents.
 
### Documentation
* [Read the docs](https://match-up-lib.readthedocs.io/en/latest/)

### Technology
* [Python 3.7](https://www.python.org/)




