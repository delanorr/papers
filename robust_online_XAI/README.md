## Approaches to Robust Online Explanations

### Abstract

Increasing use of black-box models such as Deep Neural Networks (DNNs) in practice prompted search for ways to explain the behavior of these systems. Widely used in this area are model-agnostic local attribution methods like LIME and SHAP. 
They explain model predictions on individual data points by assigning scores to features. It is, however, questionable whether use of local explanation methods is appropriate in an online learning environment. Continuous arrival of novel data, possible noise in the channel and the resulting changes in the model make explanations noisy and vulnerable to concept drift in the data. In this paper we propose various approaches to this problem, including the use of a feature selection framework which keeps track of the explained model distribution, ensemble learning and probabilistic reasoning to increase the robustness of explanations over time. We place emphasis on efficiency and stability as well as local and global faithfulness of explanations. Furthermore, we present a possible way of representing global explanations of data streams as well as evaluation metrics for robustness and local quality of explanations. We evaluate the presented approaches on data sets from two domains and two synthetically generated data sets. Results show that combining global with local explanations improves stability without decreasing the quality of explanations and even though local explainers show comparably high global ranking similarity, stability and efficiency of global explainers is significantly higher.

*Index terms* &mdash; SHAP, LIME, XAI, data streams, robustness, explainable AI, ensemble, evaluation metrics