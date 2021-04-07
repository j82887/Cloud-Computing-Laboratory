# Cloud Computing Laboratory
 
| 週 | 日期 | 課程實作內容 | 課程原理內容 | 備註 |
| :----: | :----: | :---- | :---- | :---- | 
| 1 | 2/24 | Google Colab 與 Python安裝 | -- | 自學：Python基礎 | 
| 2 | 3/03 | 3D列印基礎教學 | -- | -- |
| 3 | 3/10 | 車牌辨識：影像標柱與影像增量 | 機器學習與深度學習概要| -- |
| 4 | 3/17 | 車牌辨識：Haar分類器 | 機器學習：線性與邏輯回歸 | -- |
| 5 | 3/24 | 車牌辨識：CNN分類器 | 深度學習：多層感知器與卷積神經網路 | -- |
| 6 | 3/31 | 車牌辨識：實際應用 | 分類模型的驗證指標 | -- |
| 7 | 4/07 | 人臉辨識模型應用 | 資料前處理-不均勻類別 | -- |
| 8 | 4/14 | 表情辨識模型應用 | 資料前處理-特徵縮放與獨熱編碼 | -- |
| 9 | 4/21 | 農業黃豆瑕疵檢測 | 超參數搜索 | -- |
| 10 | 4/28 | 人工智慧相關應用 | 目標檢測模型與驗證指標 | 期中週 |
| 11 | 5/05 | 3D列印進階教學I | -- | 教學意見問卷 |
| 12 | 5/12 | 3D列印進階教學II | -- | -- |
| 13 | 5/19 | Jetbot 基本介紹與實作 | -- | -- |
| 14 | 5/26 | 製作 App 基本介紹及手機遙控小車 | -- | -- |
| 15 | 6/02 | 建立用於追蹤之簡單模型、加入傳感器及 Arduino | -- | -- |
| 16 | 6/09 | 多功能整合 | -- | -- |
| 17 | 6/16 | **期末報告** | -- | 期末週 |

### 1. 以上為暫時課程規劃，可能會受進度或其他因素而有更動
### 2. 每週點名單會更新至 Checkroll and Group Discussion 資料夾中
### 3. 每週的程式碼會放置每週的日期資料夾中

---
# 每週進度
### 2021.03.10
#### 安裝上：
- [x] Anaconda安裝Python與建立環境
- [x] 使用命令提示字元(CMD)輸入pip指令來安裝套件
- [x] Jupyter notebook 自動補語法
- [x] 安裝OpenCV的Haar分類器與使用其標註器

#### 程式上：
- [x] 判斷資料夾是否存在，刪除資料夾以及創建資料夾 (os, shuitl)
- [x] 讀取資料夾中的(影像)檔案名稱 (glob)
- [x] 讀取影像、更改影像大小與儲存影像 (PIL)

#### 原理上：
- [x] 人工智慧的任務
- [x] 人工智慧的學習方法：非監督、監督式與強化學習
- [x] 資料格式
- [x] AI相關的軟體工程師

### 2021.03.17
#### 程式上：
- [x] 讀取與建立txt檔案，並寫入新內容與儲存、關閉檔案
- [x] 分割字串
- [x] 擷取影像 (PIL)
- [x] 如何訓練Haar分類器（OpenCV）

### 2021.03.24
#### 程式上：
- [x] 使用Haar分類器（OpenCV）
- [x] 二值化影像與輪廓偵測（OpenCV）
- [x] 讀取鳶尾花資料集（Sklearn）

#### 原理上：
- [x] 線性回歸
- [x] 邏輯回歸

### 2021.03.31
#### 程式上:
- [x] 邏輯回歸（Sklearn）

#### 原理上：
- [x] 多層感知器
- [x] 卷積神經網路
- [x] 分類模型的驗證指標

### 2021.04.07
#### 程式上:
- [ ] 卷積神經網路（Tensorflow and Kears）

---
# 教材錯誤更正：
### 車牌辨識系統
1. 第三頁：在調整正樣本的影像與標注檔案中，變數n未定義，已更正為`n = data[1]`
2. 第四頁：在影像增量中，移除左上角圖 if條件式內的newx, newy定義太過於複雜，已更正為`newx = int((x-reduceW)*multi)`與`newy = int((y-reduceH)*multi)`
3. 第九頁：在車牌號碼各別擷取中的：B將二值化的影像進行輪廓偵測，參數`cv2.RETR_EXTERNAL`更正為`cv2.RETR_TREE`

---
# 課後詢問：
### 1. 聯絡地點：理工二館 A202
### 2. 聯絡信件：j82887@gmail.com
### 3. Google表單：https://forms.gle/T78yvzipNS6Uu6hi9
