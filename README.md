# ROAD safety_lstm_project

##LSTM 交通事故発生率予測
-------------------------------------------------------------------------------------------------------------------
地理メッシュ範囲：3061731708-3061731717

Trainデータ：2016.4-2019.3 

Testデータ：2019.4-2019.6

Train_Y:2016.7-2019.3

Trueデータ：2019.7


モデル：
-------------------------------------------------------------------------------------------------------------------
-二つinput層

-4つLSTM層

-三つfully connection層

-三つdropout層

-loss function:　MSE（平均二乗誤差）

モデルのinput:

-三ヶ月分の一時間ごとの月平均事故発生率

-発生率に応じて地理データ

モデルのoutput:

-一ヶ月分の一時間ごとの月平均事故発生率


性能評価
-------------------------------------------------------------------------------------------------------------------
10個場所7月交通事故発生率と予測結果平均mse：0.0035446809601703904（実際値と予測値との誤差の平均値）

10個場所7月交通事故発生率と予測結果平均mae：0.042399175982717016（予測値と正解値の差の絶対値の平均）

10個場所7月交通事故発生率と予測結果平均rmse：0.054711453565276666（平均二乗誤差の平方根）


ipynb開けないなら、https://nbviewer.jupyter.org/　
-------------------------------------------------------------------------------------------------------------------
jupyter nbviewerを試してください。
-------------------------------------------------------------------------------------------------------------------
