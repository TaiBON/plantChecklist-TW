# 臺灣國家植物名錄

範本填寫注意事項：

template.xlsx 檔案中分為兩個試算表(sheets)，第一個是 accepted names、第二個則是 synonyms。


## accepted names 表

| 欄位名稱              | 說明               | 備註             |
| --------------------- | ------------------ | ---------------- |
| namecode              | 唯一識別碼，以各資料庫/名錄之 id 或 namecode 為基礎 | 必填欄位|
| family                | 科名               | 必填欄位|
| scientificName        | 學名不含作者。種以下單位階層名請使用 var./subsp./fo.       | 必填欄位|
| authors               | 學名作者          | 必填欄位 |
| vernacularName        | 主要俗名          | 必填欄位 |
| otherVernacularNames  | 次要俗名，請以「;」來區別多個名稱 | 選填欄位|
| associatedReferences  | 發表文獻          | 選填欄位 |
| notes                 | 備註              | 選填欄位 |

## synonyms 表

| 欄位名稱              | 說明               | 備註             |
| --------------------- | ------------------ | ---------------- |
| namecode              | 唯一識別碼，以各資料庫/名錄之 id 或 namecode 為基礎 | 必填欄位|
| family                | 科名               | 必填欄位|
| acceptedFamily        | 接受的科名        | 選填欄位，若 family 非 APG/PPG 系統，請填 APG/PPG 科名|
| scientificName        | 學名不含作者。種以下單位階層名請使用 var./subsp./fo.       | 必填欄位|
| acceptedNamecode      | 接受的唯一識別碼，請以 accepted names 中的 namecode 為依據 |
| associatedReferences  | 發表文獻          | 選填欄位 |
| notes                 | 備註              | 選填欄位 |
