\# 蔬菜價格預測分析 - Gen AI 期末專案



這是一個利用機器學習（LightGBM）預測蔬菜價格的專案，涵蓋了從資料清理、特徵工程到模型預測的完整流程。



\## 專案架構與檔案說明



\### 核心程式碼

\* \*\*`GenAI\\\_Final\\\_Project.ipynb`\*\*: 專案的主要執行檔，包含資料處理與分析邏輯。



\### `results/` 資料夾 (數據與成果)

本資料夾收納了所有輸入資料、清理後的數據以及分析圖表：

\* \*\*資料清理檔案\*\*:

  \* `output\\\_avg\\\_price.csv`, `output\\\_mid\\\_price.csv`, `output\\\_volume.csv`, `output\\\_long\\\_format.csv`

\* \*\*分析結果圖表\*\*:

  \* `feature\\\_importance.png`: 顯示模型預測時的重要特徵排序。

  \* `prediction\\\_comparison.png`: 以單一蔬菜為例，對比實際價格與預測價格。

\* \*\*模型參數\*\*:

  \* `lightgbm\\\_vegetable\\\_price\\\_model.txt`: 訓練完成後存儲的模型權重檔案。



\## ⚠️ 開發筆記 (程式碼路徑修正)



本專案已完成資料夾重構。若要執行 `GenAI\\\_Final\\\_Project.ipynb`，請確保讀取路徑已進行以下修正：



1\. \*\*移除舊路徑\*\*: 請將原先程式碼中所有 `processed\\\_data/` 的前綴刪除。

2\. \*\*更新至新位置\*\*: 由於目前資料位於 `results/` 資料夾下，請將路徑更新為 `results/檔案名稱`。

   \* \*範例：\* `pd.read\\\_csv("results/output\\\_avg\\\_price.csv")`

