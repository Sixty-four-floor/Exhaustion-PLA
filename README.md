**Machine learning assisted prediction of disperse dye exhaustion on polylactic acid fiber with interpretable model**

Polylactic acid (PLA) is a promising green alternative for petroleum-based synthetic fibers, but the high-exhaustion dyeing of PLA is still an obstacle to its widespread application in textiles and therefore the development of disperse dye for PLA dyeing has been an urgent focus. Here, the exhaustion database of disperse dyes for PLA fiber from literatures and laboratory experiments was established to develop a machine learning model for predicting the dye exhaustion on PLA fiber, and the model was interpreted by Shapley Additive exPlanations (SHAP) and applied to pre-filtering out candidates with high-exhaustion that collected from literatures. 

The main tasks in this project include:
1. Model selection based on 10-fold stratified CV among RF, GB, XGB, SVM and MLP
2. Feature engineering based on mRMR, hyper-parameter optimization based on grid-search
3. Model evaluation based on 10-fold, 5-fold stratified CV and test set
4. Model interpretation based on SHAP
5. Feature generalizability evaluation based on stratified CV of three dye classes
6. Model application in external dataset and 27 novel yellow dyes

Based on the above tasks, the generalization and applicability of the constructed GB model was verified (all metrics exceed 0.800), and some novel structure-exhaustion relationships were proposed, and three novel yellow dyes that worthy of further application for PLA were screened out. This study provides a convenient way to develop high-performance dyes for new green fibers.
