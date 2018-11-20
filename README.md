# Interpretable-ML-literature
A collection of interpretable machine learning papers

# Index

1 - Interpretable recommender systems
 * [Building an Interpretable Recommender via Loss-Preserving Transformation](#building-an-interpretable-recommender-via-loss-preserving-transformation)
 * [Scalable and Interpretable Product Recommendations via Overlapping Co-Clustering](#scalable-and-interpretable-product recommendations-via-overlapping-co-clustering)
 * [Latent Factor Interpretations for Collaborative Filtering](#latent-factor-interpretations-for-collaborative-filtering)

# Papers

## [Building an Interpretable Recommender via Loss-Preserving Transformation](https://arxiv.org/abs/1606.05819)
[(PDF)](https://arxiv.org/pdf/1606.05819)

`Authors:Amit Dhurandhar, Sechan Oh, Marek Petrik`


Comments:

Presented at 2016 ICML Workshop on Human Interpretability in Machine Learning (WHI 2016), New York, NY

Subjects:

Machine Learning (stat.ML); Learning (cs.LG)


Cite as:

arXiv:1606.05819 [stat.ML]

 
(or arXiv:1606.05819v1 [stat.ML] for this version)


> Abstract: We propose a method for building an interpretable recommender system for
personalizing online content and promotions. Historical data available for the
system consists of customer features, provided content (promotions), and user
responses. Unlike in a standard multi-class classification setting,
misclassification costs depend on both recommended actions and customers. Our
method transforms such a data set to a new set which can be used with standard
interpretable multi-class classification algorithms. The transformation has the
desirable property that minimizing the standard misclassification penalty in
this new space is equivalent to minimizing the custom cost function.



## [Scalable and interpretable product recommendations via overlapping co-clustering](https://arxiv.org/pdf/1604.02071)
[(PDF)](https://arxiv.org/pdf/1604.02071)

`Authors: Reinhard Heckel, Michail Vlachos, Thomas Parnell,Celestine Duenner`

> Abstract: We consider the problem of generating interpretable recommendations by identifying overlapping co-clusters of clients and products, based only on positive or implicit feedback. Our approach is applicable on very large datasets because it exhibits almost linear complexity in the input examples and the number of co-clusters. We show, both on real industrial data and on publicly available datasets, that the recommendation accuracy of our algorithm is competitive to that of state-of-art matrix factorization techniques. In addition, our technique has the advantage of offering recommendations that are textually and visually interpretable. Finally, we examine how to implement our technique efficiently on Graphical Processing Units (GPUs).


## [Latent Factor Interpretations for Collaborative Filtering](https://arxiv.org/abs/1711.10816)
[(PDF)](https://arxiv.org/pdf/1711.10816)

`Authors: Anupam Datta, Sophia Kovaleva, Piotr Mardziel, Shayak Sen`

> Abstract: Many machine learning systems utilize latent fac- tors as internal representations for making predic- tions. Since these latent factors are largely unin- terpreted, however, predictions made using them are opaque. Collaborative filtering via matrix fac- torization is a prime example of such an algorithm that uses uninterpreted latent features, and yet has seen widespread adoption for many recommenda- tion tasks.
We present Latent Factor Interpretation (LFI), a method for interpreting models by leveraging in- terpretations of latent factors in terms of human- understandable features. The interpretation of latent factors can then replace the uninterpreted latent fac- tors, resulting in a new model that expresses predic- tions in terms of interpretable features. This new model can then be interpreted using recently devel- oped model explanation techniques. In this paper we develop LFI for collaborative filtering based rec- ommender systems.
We illustrate the use of LFI interpretations on the MovieLens dataset, integrating auxiliary features from IMDB and DB tropes, and show that latent factors can be predicted with sufficient accuracy for replicating the predictions of the true model.
