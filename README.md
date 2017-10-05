# Ensemble-methods
![](https://github.com/iurigo/Ensemble-methods/blob/master/image.jpg)

The goal of ensemble methods is to combine the predictions of several base estimators built with a given learning algorithm in order to improve generalizability / robustness over a single estimator.
Two families of ensemble methods are usually distinguished:
- In averaging methods, the driving principle is to build several estimators independently and then to average their predictions. On average, the combined estimator is usually better than any of the single base estimator because its variance is reduced.
    #### Examples: Bagging methods, Forests of randomized trees, …
- By contrast, in boosting methods, base estimators are built sequentially and one tries to reduce the bias of the combined estimator. The motivation is to combine several weak models to produce a powerful ensemble.
    #### Examples: AdaBoost, Gradient Tree Boosting, …
