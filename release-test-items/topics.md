## 測試 Topics 頁面

### go to  `/keystone/topics` 

---

#### 測試 Search 功能：
1. 在 Search 的輸入框中，輸入文字`covid-19` 
2. 確認畫面中的 Topics 列表中，列出的文章的`專題名稱（英文）`包含`covid-19`字串。

---

#### 測試 Columns 功能
點選 Columns 按鈕後，會出現多個欄位，包含：
1. `專題名稱`
2. `標題`
3. `標題版型`
4. `副標題`
5. `小標`
6. `狀態`
7. `發佈日期`
8. `簡介`
9. `製作人員名單`
10. `相關文章`
11. `相關文章版型`
12. `文章區背景色`
13. `首圖`
14. `首圖（Portrait）`
15. `置頂影片`
16. `分享標題`
17. `分享說明`
18. `分享縮圖`

其中 `專題名稱`和`發佈日期`預設是打勾的狀態，而其他則是尚未打勾的狀態。

##### 列表裡列出`作者`欄位
1. 打勾`標題`
2. 按下 Apply 按鈕
3. 檢查列表中，是否出現`標題`欄位
4. 若出現，代表正常，反之則否

---

#### 測試 Filter 功能：
點選 Filter 按鈕，會出現多個欄位，包含：
1. `專題名稱`
2. `標題`
3. `標題版型`
4. `副標題`
5. `小標`
6. `狀態`
7. `發佈日期`
8. `簡介`
9. `製作人員名單`
10. `相關文章`
11. `相關文章版型`
12. `文章區背景色`
13. `首圖`
14. `首圖（Portrait）`
15. `置頂影片`
16. `分享標題`
17. `分享說明`
18. `分享縮圖`

##### 列表 filtered by `標題`
1. 點選`專題名稱`
2. 選擇`Matches`選項
3. 選擇`Contains`選項
4. 在輸入框中，輸入文字`香港`
5. 按下 Apply 按鈕
6. 列表會被過濾，只秀出`專題名稱`中包含`香港`字串的資料列

##### 列表 filtered by `發佈日期`
1. 點選`發佈日期`
2. 選擇 `Matches` 選項
3. 選擇 `After` 選項
4. 在日期表裡選擇欲查詢的發佈日期。舉例而言，在日期表裡挑選2020年7月1日 
5. 按下 Apply 按鈕
6. 列表會被過濾，只秀出`發佈日期`在`2020-07-01`**之後**的文章

---

#### 新增 Topic
1. 點選 `+ Create Topic` 按鈕
2. 在第一個輸入框中輸入`test-topic`
3. 在第二個輸入框中輸入`測試專題名稱`
4. 按下 Create 按鈕
5. 畫面會出現 `New Topic test-topic created.`

--- 

#### 更新 Topic
1. 根據「[新增 Topic](#新增-topic)」，產生一筆測試專題資料
2. 專題名稱：維持`測試專題名稱`
2. 標題: 輸入`測試專題標題`
3. 副標題：輸入`測試專題副標題`
4. 小標：輸入`測試專題小標`
5. 狀態: 維持`Draft`
6. 簡介：輸入`Mini Reporter從《報導者》素來關注的議題出發，針對科學、社會、人文各方面的專業知識及背景，進行短篇報導，你可以這樣使用它：
等車、等人、午休空檔，花60秒學一個知識。
做為閱讀《報導者》專題延伸的「腦力補充」。
當成推薦給還不習慣閱讀《報導者》長文的親友「伴手禮」。
和《報導者》記者一起共筆，歡迎舉手發問。
請大家一起響應「真知識抗假訊息」的運動。
針對《報導者》過去的專題報導或深度文章，有任何想知道的相關小知識，歡迎來信：contact@twreporter.org提問，請在主旨註明【我要提問Mini Reporter】，我們會選擇合適的題目解答。（也請體諒我們人力有限，問題若未經採用即不回覆喔。）  `
7. 製作人員名單：輸入`文｜編輯部
封面插畫｜黃禹禛
內頁插畫｜一百隻熊`
8. 相關文章：選擇`mini-reporter-space-taiwan-distance-karman-line`, `mini-reporter-how-to-deal-with-homophobia`
9. 點選置底的`Save`按鈕
10. 畫面會出現 `Your changes have been saved`

---

#### 刪除 Topic
1. 根據「[新增 Topic](#新增-topic)」，產生測試專題資料
2. 到 Topics 列表頁 (`/keystone/topics`)
3. 找到`專題名稱（英文）`是`test-topic`的資料列
4. 點選資料列前的垃圾桶 icon
5. 點選`Delete`按鈕
6. 確認列表中，沒有`專題名稱（英文）`是`test-topic`的資料列

---
