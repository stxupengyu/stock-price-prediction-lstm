# stock-price-prediction-lstm
使用LSTM模型预测股票收盘价，并且通过网格搜索确定最优超参数，注释拉满。Forecasting stock closing price using LSTM model, step by step.  
其中pca.csv和xgboost.csv分别是经过特征工程处理后的数据集。LSTM分别基于这两种特征工程方法得到的数据集进行预测。  
pca-lstm是基于数据集pca.csv进行lstm预测的过程，search-pca-lstm即是进行网格搜素的过程。xgboost-lstm同理。  
由于数据需要保密，这里给出的数据集均为fake数据集。  
