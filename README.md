# Disneyland Review Analysis

Authors: Anthony DeNiro, Rastko Stojsin, Teddy Weaver<br>
Date Published: May 7, 2021

Data Source: https://www.kaggle.com/arushchillar/disneyland-reviews


## About
---
Disney parks offer fun-filled voyages to magical worlds, and with 12 Disney park locations worldwide with each one can offer something unique. Unfortunately, one of our very own team members (Rastko) has never been. He ahs dreamed of one day being able to experience the magicical kingdom. For the children like him that motivates us to deliver insight into the decision of which park to visit, for when the time comes for Rastko to finally step through those glorious Disney gates.

We have analyzed the data to understand which of the three Disneyland locations in the dataset (Calfiornia, Hong Kong, Paris) would be the best to vists and at what time of year. Going a step further, we've performed some NLP to analyze the review text and attempt to predict ratings based on the body of the review.

In the end, we think Rastko and his family would prefer the California park location due to it's consitently high-reviews year round, although rumor as it that there are some amazin fireworks in Paris.

## Files
---
Quick description of each notebook in the repo.

`10-eda.ipynb` -- Exploratory analysis and cleaning of the datset. Use PySpark, Pandas, and MatPlotLib to create visualizations to help us uncover and interpet any patterns or insights.

`20-review-prediction.ipynb` -- Generate a hashed TF-IDF of the review text. This serves as the primary input to predicting the reivew rating (1-5) with a multinomial Logistic Regression, Decision Tree + Random Forest Classifiers, and Naive Bayes Classifier

`30-reivew-prediction-kmeans.ipynb` -- Building on the tree models from the earlier notebook, use tree-based classifiers (Decision Tree, RF) with the derived K-Means Cluster as one of the model features.

`plots` -- Contains a copy of the visulaizaitons created in `10-eda.ipynb`

`documents` -- Copy of the project presentation
