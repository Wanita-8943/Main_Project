# ------------------------------------------------
# Classification
# ------------------------------------------------
## Train Female(แบ่งตามอายุของเพศหญิง)
 - รอบที่ 1 ([F1 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/F1_Train_Freeze_250.ipynb))
 - รอบที่ 2 ([F2 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/F2_Train_Freeze_250.ipynb))  
 - รอบที่ 3 ([F3 Unfreeze 500]())
 
## Predict Female(แบ่งตามอายุของเพศหญิง)
 - รอบที่ 1 ([17.47%]())
 - รอบที่ 2 ([18.11%]())  
 - รอบที่ 3 ([]())
   
 ## Train Male(แบ่งตามอายุของเพศชาย)
 - รอบที่ 1 ([M1 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/M1_Train_Freeze.ipynb))
 - รอบที่ 2 ([M2 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/M2_Train_Freeze.ipynb))  
 - รอบที่ 3 ([M3 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/M3_Train_Freeze.ipynb))
 - รอบที่ 4 ([M4 Unfreeze 500]())

 ## Predict Male(แบ่งตามอายุของเพศชาย)
 - รอบที่ 1 ([17.10%]())
 - รอบที่ 2 ([16.21%]())  
 - รอบที่ 3 ([17.89%]())
 - รอบที่ 4 ([]())
 
## Train Gender(แบ่งตามเพศชายและเพศหญิง)
 - รอบที่ 1 ([G1 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/G1_Train_Freeze.ipynb))
 - รอบที่ 2 ([G2 Freeze 250](https://github.com/Wanita-8943/Main_Project/blob/main/G2_Train_Freeze.ipynb))  
 - รอบที่ 3 ([G3 Unfreeze 500]())
 
 ## Predict Gender(แบ่งตามเพศชายและเพศหญิง)
 - รอบที่ 1 ([69.95%]())
 - รอบที่ 2 ([68.32%]())  
 - รอบที่ 3 ([]())

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
 - รอบที่ 1 ([5.26%]())
 - รอบที่ 2 ([5.26%]())  
 - รอบที่ 3 ([5.26%]())
 - รอบที่ 4 ([19.89%]())
 - รอบที่ 5 ([23%]())
