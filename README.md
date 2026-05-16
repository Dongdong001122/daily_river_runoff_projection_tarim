# Tarim River Runoff and Evapotranspiration Projection (21st Century)

This project projects future river runoff and actual evapotranspiration for the seven headwaters of the Tarim River in the 21st century. It supports the research presented in the paper *"Hydrological Response to Glacier Peak Water in the Largest Inland River Basin of China"*, published in the *Journal of Hydrology*.

## Model Scripts

- **`LSTM_ep_daily.ipynb`** / **`LSTM_ep_mon.ipynb`** – Daily and monthly scale projection models using deep learning (LSTM).
- **`XGBoost_daily.ipynb`** / **`XGBoost_monthly.ipynb`** – Projection models using XGBoost.
- **`xlstm_daily.ipynb`** / **`xlstm_monthly.ipynb`** – Projection models using xLSTM.

> We also tested projection models with xLSTM and XGBoost using the same parameters, but neither outperformed our deep learning model.

## Additional Notebooks

Other notebooks in this project are used for:
- Data preprocessing
- Data visualization
- Model evaluation

## Important Notes

- The model performs better when the validation ratio is set to **40%** compared to other splits.
<img width="889" height="290" alt="image" src="https://github.com/user-attachments/assets/688be629-94d2-4ec8-b39a-85d736556ea0" />

- Satisfactory long-term projection performance is achieved **only when river runoff and basin-wide evapotranspiration are projected together** by the model.

## Contact

For questions or inquiries, please contact the first author:  
**[201914030135@stu.sdnu.edu.cn](mailto:201914030135@stu.sdnu.edu.cn)**
