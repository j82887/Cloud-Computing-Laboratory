# 01. Car License Plate
* 影像為教材收集之影像(.jpg)，下載網址可至雲端 [連結](https://drive.google.com/drive/folders/1Rv6aQQ604FMMRQMjEC3YM0WSAkdqCyBf?usp=sharing) 中
* 包含非車牌292張與車牌103張彩色影像

# 02. MNIST Handwritten Digit Database
* 包含著60,000張訓練集與10,000張測試集的灰階影像(array)，每張的大小皆為28x28
* 可安裝Kears後，直接匯入進來：
* `from keras.datasets import mnist`
* `(X_train, Y_train), (X_test, Y_test) = mnist.load_data()`

# 03. AZ Handwritten Alphabets
* 影像集為26個英文字母的影像，下載網址可至Kaggle [連結](https://www.kaggle.com/sachinpatel21/az-handwritten-alphabets-in-csv-format) 中
* 372,451張灰階影像，每張的大小皆為28x28，並以(.csv)半結構化的資料方式儲存
