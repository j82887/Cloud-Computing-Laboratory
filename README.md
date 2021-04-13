# Cloud Computing Laboratory
 
| 週 | 日期 | 課程實作內容 | 課程原理內容 | 備註 |
| :----: | :----: | :---- | :---- | :---- | 
| 1 | 2/24 | Google Colab 與 Python安裝 | -- | 自學：Python基礎 [[PDF]](https://github.com/j82887/Cloud-Computing-Laboratory/raw/main/02_2021_0303/%E5%AF%A6%E4%BD%9C_%E7%AC%AC%E4%B8%80%E9%80%B1_20210303_%E7%A8%8B%E5%BC%8F%E5%9F%BA%E7%A4%8E%20Python.pdf) | 
| 2 | 3/03 | 3D列印基礎教學 | -- | -- |
| 3 | 3/10 | 車牌辨識：影像標柱與增量 | 機器與深度學習概要| -- |
| 4 | 3/17 | 車牌辨識：Haar分類器 | 線性與邏輯回歸 | -- |
| 5 | 3/24 | 車牌辨識：資料集合併 | 多層感知器 | -- |
| 6 | 3/31 | 車牌辨識：資料前處理 | 卷積神經網路 | -- |
| 7 | 4/07 | 車牌辨識：CNN分類器 | 驗證指標 | -- |
| 8 | 4/14 | 車牌辨識：實際應用 | 特徵縮放與獨熱編碼 | -- |
| 9 | 4/21 | 人臉辨識模型應用 | 不均勻類別 | -- |
| 10 | 4/28 | 表情辨識模型應用 | 超參數搜索 | 期中週 |
| 11 | 5/05 | 3D列印進階教學I | -- | 教學意見問卷 |
| 12 | 5/12 | 3D列印進階教學II | -- | -- |
| 13 | 5/19 | Jetbot 基本介紹與實作 | -- | -- |
| 14 | 5/26 | 製作App及手機遙控小車 | -- | -- |
| 15 | 6/02 | 建立追蹤模型、加入傳感器及 Arduino | -- | -- |
| 16 | 6/09 | 多功能整合 | -- | -- |
| 17 | 6/16 | **期末報告** | -- | 期末週 |

### 1. 以上為暫時課程規劃，可能會受進度或其他因素而有更動
### 2. 每週點名單會更新至 Checkroll and Group Discussion 資料夾中
### 3. 每週的程式碼會放置每週的日期資料夾中

---
# 每週進度
### 2021.03.10
- [x] 安裝上: Anaconda安裝Python與建立環境
- [x] 安裝上: 使用命令提示字元(CMD)輸入pip指令來安裝套件
- [x] 安裝上: Jupyter notebook 自動補語法
- [x] 安裝上: 安裝OpenCV的Haar分類器與使用其標註器
- [x] 程式上: 判斷資料夾是否存在，刪除資料夾以及創建資料夾 (os, shuitl)
- [x] 程式上: 讀取資料夾中的(影像)檔案名稱 (glob)
- [x] 程式上: 讀取影像、更改影像大小與儲存影像 (PIL)
- [x] 原理上: 人工智慧的任務
- [x] 原理上: 人工智慧的學習方法：非監督、監督式與強化學習
- [x] 原理上: 資料格式
- [x] 原理上: AI相關的軟體工程師

### 2021.03.17
- [x] 程式上: 讀取與建立txt檔案，並寫入新內容與儲存、關閉檔案
- [x] 程式上: 分割字串
- [x] 程式上: 擷取影像 (PIL)
- [x] 程式上: 如何訓練Haar分類器（OpenCV）

### 2021.03.24
- [x] 程式上: 使用Haar分類器（OpenCV）
- [x] 程式上: 二值化影像與輪廓偵測（OpenCV）
- [x] 程式上: 讀取鳶尾花資料集（Sklearn）
- [x] 原理上: 線性回歸
- [x] 原理上: 邏輯回歸

### 2021.03.31
- [x] 程式上: 邏輯回歸（Sklearn）
- [x] 原理上: 多層感知器
- [x] 原理上: 卷積神經網路
- [x] 原理上: 分類模型的驗證指標

### 2021.04.07
- [x] 程式上: 卷積神經網路（Tensorflow and Keras）
- [x] 程式上: 資料前處理 - 獨熱編碼
- [x] 原理上: 資料前處理 - 特徵縮放與獨熱編碼

### 2021.04.14
- [ ] 程式上: 車牌辨識系統合併
- [ ] 原理上: 資料前處理 - 不均勻類別問題

---
# 教材錯誤更正：
### 車牌辨識系統
1. 第三頁：在調整正樣本的影像與標注檔案中，變數n未定義，已更正為`n = data[1]`
2. 第四頁：在影像增量中，移除左上角圖 if條件式內的newx, newy定義太過於複雜，已更正為`newx = int((x-reduceW)*multi)`與`newy = int((y-reduceH)*multi)`
3. 第九頁：在車牌號碼各別擷取中的：B將二值化的影像進行輪廓偵測，參數`cv2.RETR_EXTERNAL`更正為`cv2.RETR_TREE`

---
# 課後詢問：
### 1. 聯絡地點：理工二館 A202
### 2. 聯絡郵件：j82887@gmail.com
### 3. Google表單：https://forms.gle/T78yvzipNS6Uu6hi9
