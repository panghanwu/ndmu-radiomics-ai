# 乳房攝影自動 BI-RADS 輔助判讀

> 本週必做：把下面三行填掉。**三行就好，不要寫成正式文件。**
> 判準只有一個：把這個資料夾丟給同學，他不問你任何問題就跑得起來。

**環境怎麼裝**：`pip install -r requirements.txt`

**資料放哪**：資料存放於地端，不公開；路徑設定於 `.env`，真實資料與 `.env` 不進 Git

**程式什麼順序跑**：`notebooks/01_preprocess_mammo.ipynb` → `02_extract_features.ipynb` → `03_model.ipynb`

---

以下是選填的，**W18 驗收前**再補就好：

- 種子：`set_seed(3345678)`，sklearn 的 `random_state` 一律用 `RANDOM_STATE`
- 環境紀錄：`results/YYYYMMDD_env.json`