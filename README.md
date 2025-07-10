Hello! 

The purpose of this repository is to host materials that will help others create predictions of water temperature when no observations are available for their candidate sites. 

predict_watertemp.Rmd includes code to help users train our model to data. 

We include a zip file "enviroDataDemo.csv" which an extensively cleaned dataset of water tempearture estimates from around Victoria, Australia. This forms the training data for our model.

We also include "gauge_405294.csv". This contains only air temperature estimates for this gauge and no water temperature data. 

Our code loads the available data and excludes gauge 405294 (for the purposes of this exercise), then prepares predictors like rolling averages and elevation, scales these predictors and then trains our model on our dataset. Finally, it predicts to our gauge, creating a dataframe with estimates of water temperature. 

For those working in southeastern Australia, we have also included an appendix which includes estimates of water temperature to many sites in the state of Victoria.

We expect updates and work but hopefully this proves useful.

Happy estimating!
