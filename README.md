## Project Introduction

This is the `jupyter lab` project of `Fair-NE`, a fair peer recommender based on DeBayes by Buyl and De Bie (2020). There are two notebook files: `preprocessing` and `network_embeddings`. The `preprocessing` file constructs edges from students' posts and replies. There was also some visualization on students' traffic in that notebook. `network_embeddings` is the main file that trains and evaluates the models: FairNE, FairWalk, and Node2Vec. Fair-NE allows researchers to debias the peer recommender system by specifying multiple categorical demographic variables such as nationality, gender, and race. The model learns to adjust its internal embedding system to recommend peers without being influenced by students’ demographics.


Buyl, M., & De Bie, T. (2020, November). Debayes: a bayesian method for debiasing network embeddings. In International Conference on Machine Learning (pp. 1220-1229). PMLR.