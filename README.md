>## This project analyzes a Pokémon dataset using unsupervised and supervised learning techniques. First, KMeans is applied to identify clusters of Pokémon based on their numerical characteristics. Subsequently, the resulting clusters are used as labels to train supervised models such as Random Forest and Logistic Regression, addressing the class imbalance problem through oversampling techniques.

I used a Pokémon dataset obtained from Kaggle, which includes variables such as:
* Physical characteristics: height, weight
* Base experience
* Combat statistics: hp, attack, defense, special_attack, special_defense, speed
* Pokémon types

Among other things. The main intention behind their analysis is to identify if there is a class separability that is not readily apparent, allowing us to determine through predictive models when it is worthwhile to capture one of these creatures, and how to assemble an ideal team according to their attributes.

Key findings:
* Existence of variables with very different scales (especially weight).
* Presence of outliers, mainly associated with rare or legendary Pokémon.
* More homogeneous distributions in battle stats.

In the future, I would like to apply other clustering algorithms (DBSCAN, Hierarchical Clustering).
