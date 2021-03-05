## 連結網址
1. Google Colab: https://colab.research.google.com/notebooks/intro.ipynb#recent=true
2. Kaggle: https://www.kaggle.com/
3. Anaconda: https://www.anaconda.com/
4. PyPI: https://pypi.org/

## 01. 本機安裝Python
 
* 從Anaconda官網中選擇下載電腦系統支援的安裝檔案(目前Anaconda的最高Python版本為3.8)
* 執行安裝檔，環境變數需要打勾文字成紅色，其餘都按下一步即可
* 安裝完成後，將Anaconda以右鍵以「系統管理身分執行」
* 由於考量本教材使用的套件大多只支援Python3.6，所以創建Python 3.6的環境：
1. Environments中在base(root)根環境，以左鍵點擊三角形選擇執行「Open Terminal」執行命令提示字元
2. 在命令提示字元中輸入`conda create -n py36 python=3.6 anaconda`，開始創建名稱為py36與Python版本為3.6的環境
* 安裝完成後，在Environments中點擊py36的環境，並轉換到「Home」，點擊安裝jupyter Notebook「install」
* 完成後Environments中在py36環境，以左鍵點擊三角形選擇執行「Open with Jupyter Notebook」可以開始撰寫程式

---
## 02. 本機jupyter notebook自動補上語法
#### 在py36環境中開啟命令提示字元執行下列指令：
* 安装 nbextensions
1. `pip install jupyter_contrib_nbextensions`
2. `jupyter contrib nbextension install --user`

* 安裝 nbextensions_configurator
1. `pip install jupyter_nbextensions_configurator`

2. `jupyter nbextensions_configurator enable --user`

* 如果提示缺少依賴項（套件），就使用pip安裝對應依賴項（套件）即可。
* 最後重新啟動jupyter，在彈出的Home裡面中，能看到增加了Nbextensions標籤頁，在這勾選Hinterland即啟動語法自動補全

---
## 03. 安裝套件
#### 有兩種安裝方式：
1. 可至PyPI網站上尋找套件名稱，並複製`pip install package_name`輸入至該環境的命令提示字元中
2. 在該環境中選擇「Not Installed」，對預安裝的套件點擊方框，並選擇「Apply」來安裝
