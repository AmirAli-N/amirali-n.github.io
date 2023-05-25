<!---## [Example of MDP Approach to Unified Planting and Harvesting Optimization](https://amirali-n.github.io/Bayer_PlantHarvestMDP/)
Markov decision processes (MDP) can be a powerful tool in modeling system that evolve over time. In this case, this framework is used to model a farm operations management where each field at the farm may be planted and harvested at different time which result in different yields. To optimize the yield at the end of the horizon, various decisions must be made prior to harvesting time with the goal of maximizing the volume harvested. The planting decision also affects the quality of the volume harvested. You can visit my minimal implementation of the MDP approach to this problem in the [project's page](https://github.com/AmirAli-N/MDP-PlantHarvest).--->

## [Feature Selection with Boruta and Importance Analysis with SHAP Values](https://amirali-n.github.io/BorutaFeatureSelectionWithShapAnalysis/)
xgBoost technique can be used to produce feature importances. These importances may be used to select a subset of the more important features given an arbitrary threshold. However, it has been shown that these feature importances are inconsistent with respect to different data sets. Therefore, even by considering an importance threshold, appropriate feature subset selection cannot be achieved. Boruta selection wrapper is an algorithm that test the importance of each feature against a shuffled copy. SHAP values are developed by [Scott Lundberg](https://github.com/slundberg/shap) and are used to derive global and consistent feature importances. You can see my implementation [here](https://amirali-n.github.io/BorutaFeatureSelectionWithShapAnalysis/).

## [Classification with Extreme Gradient Boosting (xgBoost)](https://amirali-n.github.io/ExtremeGradientBoosting/)

Implementation of the xgBoost technique on roadside maintenance data set to identify major factor contributing to the risk of collision for roadside maintenance workers. The data contains more than 2 million work orders from the state of California and describe work zone features, road features, traffic flow and volume and collision characteristics. You can visit the [project's page](https://amirali-n.github.io/ExtremeGradientBoosting/) or see the [entire repository](https://github.com/AmirAli-N/PMRF-DataAnalysis). The project is sponsored by [California Department of Transportation](https://dot.ca.gov/programs/research-innovation-system-information) through [Advanced Highway Maintenance & Construction Technology](http://ahmct.ucdavis.edu/) research center.
