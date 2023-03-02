# ------------------------------------------------
# Classification
# ------------------------------------------------
## Train Female(แบ่งตามอายุของเพศหญิง)
 - รอบที่ 1 ([F1 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/F1_Train_Freeze_250.ipynb))
 - รอบที่ 2 ([F2 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/F2_Train_Freeze_250.ipynb))  
 - รอบที่ 3 ([F3 Unfreeze 500](https://github.com/Wanita-8943/Main_Project/blob/main/F3_Train_Unfreez_500.ipynb))
 
## Predict Female(แบ่งตามอายุของเพศหญิง)
 - รอบที่ 1 ([17.47%](https://github.com/Wanita-8943/Main_Project/blob/main/F1_Predict_Freeze.ipynb))
 - รอบที่ 2 ([18.11%](https://github.com/Wanita-8943/Main_Project/blob/main/F2_Predict_Freeze.ipynb))  
 - รอบที่ 3 ([18.53%](https://github.com/Wanita-8943/Main_Project/blob/main/F3_Predict_Unfreeze_500.ipynb))
   
 ## Train Male(แบ่งตามอายุของเพศชาย)
 - รอบที่ 1 ([M1 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/M1_Train_Freeze.ipynb))
 - รอบที่ 2 ([M2 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/M2_Train_Freeze.ipynb))  
 - รอบที่ 3 ([M3 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/M3_Train_Freeze.ipynb))
 - รอบที่ 4 ([M4 Unfreeze 500](https://github.com/Wanita-8943/Main_Project/blob/main/M4_Train_Unfreez_500.ipynb))

 ## Predict Male(แบ่งตามอายุของเพศชาย)
 - รอบที่ 1 ([17.10%](https://github.com/Wanita-8943/Main_Project/blob/main/M1_Predict_Freeze.ipynb))
 - รอบที่ 2 ([16.21%](https://github.com/Wanita-8943/Main_Project/blob/main/M2_Predict_Freeze.ipynb))  
 - รอบที่ 3 ([17.89%](https://github.com/Wanita-8943/Main_Project/blob/main/M3_Predict_Freeze.ipynb))
 - รอบที่ 4 ([16.63%](https://github.com/Wanita-8943/Main_Project/blob/main/M4_Predict_Unfreeze_500.ipynb))
 
## Train Gender(แบ่งตามเพศชายและเพศหญิง)
 - รอบที่ 1 ([G1 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/G1_Train_Freeze.ipynb))
 - รอบที่ 2 ([G2 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/G2_Train_Freeze.ipynb))  
 - รอบที่ 3 ([G3 Unfreeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/G3_Train_Unfreeze_250.ipynb))
 - รอบที่ 3 ([G3 Unfreeze 500](https://github.com/Wanita-8943/Main_Project/blob/main/G3_Train_Unfreeze_500.ipynb))
 
 ## Predict Gender(แบ่งตามเพศชายและเพศหญิง)
 - รอบที่ 1 ([69.95%](https://github.com/Wanita-8943/Main_Project/blob/main/G1_Predict_Freeze.ipynb))
 - รอบที่ 2 ([68.32%](https://github.com/Wanita-8943/Main_Project/blob/main/G2_Predict_Freeze.ipynb))  
 - รอบที่ 3 250 ([68.63%](https://github.com/Wanita-8943/Main_Project/blob/main/G3_Predict_Unfreeze_250.ipynb))
 - รอบที่ 3 500 ([68.32%](https://github.com/Wanita-8943/Main_Project/blob/main/G3_Predict_Unfreeze_500.ipynb))


# ------------------------------------------------
# Regression
# ------------------------------------------------
# All Age Parameter 
 - learning_rate=1e-4
 - epoch 250
 - batch_size = 16
 - width = 150
 - height = 150
 - epochs = 250
 - NUM_TRAIN = 2850
 - NUM_TEST = 950
 - dropout_rate = 0.2
 - input_shape = (height, width, 3)
## Train All(ทุกอายุและทุกเพศ) 
 - รอบที่ 1 ([Re All1 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/A1_Train_Freeze.ipynb))
 - รอบที่ 2 ([Re All2 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/A2_Train_Freeze.ipynb))  
 - รอบที่ 3 ([Re All3 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/A3_Train_Freeze.ipynb))
 - รอบที่ 4 ([Re All4 Unfreeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/A4_Train_Unfreez.ipynb))
 - รอบที่ 5 ([Re All5 Unfreeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/A5_Train_Unfreez.ipynb))

## Predict All(ทุกอายุและทุกเพศ)
 - รอบที่ 1 ([5.26%](https://github.com/Wanita-8943/Main_Project/blob/main/A1_Predict_Freeze.ipynb))
   - MSE: 31.0
   - MAE: 4.7894736842105265
 - รอบที่ 2 ([5.26%](https://github.com/Wanita-8943/Main_Project/blob/main/A2_Predict_Freeze.ipynb))  
   - MSE: 30.0
   - MAE: 4.7368421052631575
 - รอบที่ 3 ([5.26%](https://github.com/Wanita-8943/Main_Project/blob/main/A3_Predict_Freeze.ipynb))
   - MSE: 30.0
   - MAE: 4.7368421052631575
 - รอบที่ 4 ([19.89%](https://github.com/Wanita-8943/Main_Project/blob/main/A4_Predict_Unfreeze.ipynb))
   - MSE: 5.893684210526316
   - MAE: 1.7968421052631578
 - รอบที่ 5 ([23%](https://github.com/Wanita-8943/Main_Project/blob/main/A5_Predict_Unfreeze.ipynb))
   - MSE: 5.096842105263158
   - MAE: 1.6189473684210527
   
