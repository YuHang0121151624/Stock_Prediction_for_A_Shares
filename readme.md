# Stock Prediction for A-Shares       
## 1引言      
### 1.1编写目的      
实现一个基于Windows系统对于A股的股票预测软件。用户通过输入指定的股票代码，即可得到对于该股票的收益预测。
### 1.2项目背景      
量化分析是金融和人工智能的交叉领域，有着广阔的前景。专业的量化分析人员能够利用金融知识和计算机技术分析行情，从而协助他们做出更有利的判断。
## 2项目介绍       
### 2.1项目目标       
项目目标是实现一个对于中国A股的股票预测软件，为用户提供必要的界面，用户选取股票后给出未来一周的涨幅预测。
### 2.2项目适用用户        
该项目适用于寻求股票参考信息的用户，用户可以通过软件给出的预测适当调整投资策略。
## 3模块功能       
### 3.1数据获取模块        
用户给出指定股票的代码后软件需要得到相应数据，如任意天的开盘价、收盘价、最高价、最低价、成交量，以及基本面信息等。
### 3.2#股票预测模块        
依据获取的数据建立RNN模型，并给出最终的预测。
### 3.3图形界面        
给出必要的用户界面，使得用户能够输入股票代码。
