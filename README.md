# Cloud Computing Laboratory
 
| 週 | 日期 | 課程實作內容 | 課程原理內容 | 備註 |
| :----: | :----: | :----: | :----: | 
| 1 | 2月24日 | Google Colab 與 Python安裝 | -- | 自學：Python基礎教學 | 
| 2 | 3月3日 | 車牌辨識：影像標柱與影像增量 | 人工智慧、機器學習與深度學習概要 | -- |
| 3 | 3月10日 | 車牌辨識：Haar分類器 | 機器學習：線性回歸與邏輯回歸 | -- |
| 4 | 3月17日 | 車牌辨識：CNN分類器 | 深度學習：多層感知器與卷積神經網路 | -- |
| 5 | 3月24日 | 車牌辨識：實際應用 | 分類的驗證指標 | -- |

## 連結網址
1. Google Colab: https://colab.research.google.com/notebooks/intro.ipynb#recent=true
2. Kaggle: https://www.kaggle.com/
3. Anaconda: https://www.anaconda.com/

## 備註
### 本機jupyter notebook自動補上語法
* 安装 nbextensions
`pip install jupyter_contrib_nbextensions`

`jupyter contrib nbextension install --user`

* 安裝 nbextensions_configurator
`pip install jupyter_nbextensions_configurator`

`jupyter nbextensions_configurator enable --user`

* 如果提示缺少依賴項（套件），就使用pip安裝對應依賴項（套件）即可。
* 最後重新啟動jupyter，在彈出的Home裡面中，能看到增加了Nbextensions標籤頁，在這勾選Hinterland即啟動語法自動補全

### Python安裝3.6環境
`conda create -n py36 python=3.6 anaconda`
