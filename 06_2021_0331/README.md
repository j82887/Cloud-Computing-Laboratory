## 01. 安裝套件
* pip install keras==1.0.8
* pip install tensorflow== 1.13.1 --user 
* 本教材只裝於Keras版本為 1.08，Tensorflow版本為 1.13.1。若要嘗試最新Tensorflow 2.0版本可以參考網址安裝：https://tf.wiki/zh_hant/basic/installation.html
* 安裝不成功者則可以使用Colab進行實作

* **安裝過程中可出現** `WARNING: The scripts xx.exe are installed in 'C:\Users\...' which is not on PATH. Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.`，解決方式是將該位置加入環境變數中，從「本機」中點擊右鍵選擇「內容」，它會跳到"控制台\系統及安全性\系統"，選擇「進階系統設定」→「環境變數」，將該環境添加進去

## 02. 英文手寫數據集
#### Kaggle
* https://www.kaggle.com/ashishguptajiit/handwritten-az
#### 雲端下載
* https://drive.google.com/file/d/1yvC36I1VSO9dEKvJR7sJlEyZJ7Se1dVH/view?usp=sharing

## 03. Colab與雲端硬碟連接
* 匯入Google Colab中的套件
`from google.colab import drive`

* 將自己的雲端硬碟掛載上去
`drive.mount('/content/gdrive')`

## 04. 下禮拜來前要完成
* 下載英文字母手寫的.csv資料集
* 將英文字母手寫資料集放進雲端硬碟
