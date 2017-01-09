# tbroc_gov_tw

## 計畫說明

目前政府推的開放資料因為政策制定的關係，主要是以資料集數量為最重要 KPI。結果就是，雖然目前 data.gov.tw 平台上已經有超過 2 萬筆以上的資料集（還要再加上許多地方政府的資料集），但是這些資料集絕大部分都有著下列的問題 :

- 資料集描述不清楚 - 從資料集的標題到內容的描述，常常都讓人不清楚這個資料集的內容是什麼（例如，資料集如何收集取得，資料建立是為了回應怎樣的需求，和最終產出的資料集內容到底結果為何）
- 資料集欄位說明遺漏或是不清楚 - 有些欄位可以一下就知道其所代表的含意，例如日期等。但是有些欄位內容，因為使用專有的代碼等，讓人完全猜不到這些內容到底在說什麼
- 資料集內容的不一致 - 資料集內容依照資料屬性，如文字，數字，日期等，出現格式或是單位等的不一致狀況




## 計畫執行

1. 資料集整理與優化
  - 資料集分類 (category)
  - 資料集名稱 (name)
  - 資料集描述 (description)
  - 資料集欄位說明 (data schema)
  - 資料集內容標準
1. 資料集匯出
  - 資料集轉 data package format
  - 更新至 github (https://github.com/OpenData-TW/tbroc_gov_tw)
1. 資料集應用與轉換
  - 統計與預算資料 : 建立 [R package](http://kbroman.org/pkg_primer/pages/build.html) ([使用 RStudio](https://support.rstudio.com/hc/en-us/articles/200486488-Developing-Packages-with-RStudio))
  - 地理與圖資資料 : 匯入 OSM 開放街圖
  - 資料集自動視覺化產出 (g0v 專案)

## 資料格式

所有的資料格式將使用 OKFN 的 [Data package](http://frictionlessdata.io/data-packages/) 做彙整

![](https://docs.google.com/drawings/d/19DTSTlxkOdTgieTWhnTNLAZtxn_ie63DV-vEGW_TP_E/pub?w=960&h=720)

## 資料集分類

## 資料連結
- [交通部觀光局開放資料 ](http://data.gov.tw/wise_search?nodetype=metadataset&kw=%E4%BA%A4%E9%80%9A%E9%83%A8%E8%A7%80%E5%85%89%E5%B1%80)
- [交通部觀光局政府資料開放相關資訊](http://admin.taiwan.net.tw/public/public.aspx?no=381)
-

## 授權說明

- 所有資料集皆來自 data.gov.tw 網站，各資料集的授權也依照在 data.gov.tw 網站上的需告（主要為台灣政府開放資料授權第一版）
- 所有 repo 內使用到的第三方著作權則依照其各自授權規範
- 所有 repo 內的程式碼與其他內容與文件，除非特別聲明，皆採用 MIT Licence
