# Turbofan-Jet-Engine-Life-Cycle-Prediction
## This repo is under construction   
* **AIM:** This project aims to predict turbofan jet engines remaining life cycles based on current sensor performance.
* **Techstack:** Colab,Python(pandas,numpy,matplotlib,seaborn,sklearn,tensorflow),Long-Short-Term-Memory(LSTM) Architecture.
* **Dataset:** [NASA Turbofan Jet Engine Data Set](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps)
  
## Stage 1: EDA and Model training
1. Update : Normalized the data.  Next Step : Creating data sequences.
2. Update : Model training,Comparison and Evaluation based on splitted test data. Next Step: Evaluation of the model on official NASA RUL file.
3. Final: Model Evaluated on the real world Nasa dataset containg real observations on ject engines, key performance observations:
``` text
Official Test MAE: 14.168800354003906
Official Test MSE: 367.11590576171875
Official Test RMSE: 19.160268937614596
Official Test R2: 0.7874096035957336
```
4. model and MinMaxScaler object saved and downloaded.
5. Ready for further development.
