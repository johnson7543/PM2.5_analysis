# PM2.5_analysis
### PM2.5 analysis using pandas and plotly.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/johnson7543/PM2.5_analysis/main?filepath=PM2.5.ipynb)

### 取得近10年台中市PM2.5日平均值

1.使用巢狀迴圈讀檔案，跑10個年份(2011~2020)的資料夾和每個資料夾裡面的所有csv檔。<br>
2.每次讀檔時都會進行資料整理，篩選出台中市的測站數值，並將不需要的欄位移除、格式化型別、處理無效內容。<br>
3.處理完後會將每個測站的數值平均，加到新的欄位"PM2.5平均"，並且只保留這個欄位。<br>
4.新增一些存放年、月、日等時間的欄位，以便計算日平均、月平均、年平均，和之後畫圖所用。<br>
5.將日期相同的分為一組，即可算出日平均。<br>
6.將月份相同的分為一組，即可算出月平均。<br>
7.將年份相同的分為一組，即可算出年平均。<br>
