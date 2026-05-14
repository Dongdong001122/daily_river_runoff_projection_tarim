This Project is for project the future river runoff and actual evapotranspiration of the 7 head waters of Tarim River in the 21st century.
LSTM_ep_daily.ipynb and LSTM_ep_mon.ipynb are the script for the future projection model with deaap learning model for the daily and monthly scale.
We have also tried the projection models with xlsm and XGBoost with the same parameters, but they failed to perform better than the model with the our deap learning model.

Other notebook in the project is for data preprocessing and visualization.

Note: We found that the model perform better if we set the ratio of validation period with 20% than that with 20%. And only if the river runoff and basinal evapotranspiration are projected by the model together can the model project for the long period with good performance in our study.

For more information, please contact the first author with 201914030135@stu.sdnu.edu.cn.
