# Leveraging Low-Rank Relations Between Surrogate Tasks in Structured Prediction - ICML 2019
We study the interplay between surrogate methods for structured prediction and techniques from multitask learning designed to leverage relationships between surrogate outputs. We propose an efficient algorithm based on trace norm regularization which, differently from previous methods, does not require explicit knowledge of the coding/decoding functions of the surrogate framework. As a result, our algorithm can be applied to the broad class of problems in which the surrogate space is large or even infinite dimensional. We study excess risk bounds for trace norm regularized structured prediction, implying the consistency and learning rates for our estimator. We also identify relevant regimes in which our approach can enjoy better generalization performance than previous methods. Numerical experiments on ranking problems indicate that enforcing low-rank relations among surrogate outputs may indeed provide a significant advantage in practice.


## Requirements


### Installing igraph
We make use of the igraph package for the decoding step of our algorithm. https://igraph.org/python/

```
pip install python-igraph
```

### Citation

```
@inproceedings{luise2019leveraging,
  title={Learning-to-Learn Stochastic Gradient Descent with Biased Regularization},
  author={Luise, Giulia and Stamos, Dimitris and Pontil, Massimiliano and Ciliberto, Carlo},
  booktitle={International Conference on Machine Learning},
  year={2019}
}
```
