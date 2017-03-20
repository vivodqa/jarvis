# 指令名稱：bugissuecv

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 在韌體驗證組中找尋符合條件的bug issue | 3 | DQA redmine | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之 韌體驗證組bug |

---

## 使用情境

#### 情境一：查詢 \[特定功能\] 相關 Bug

> 查詢韌體驗證組發過有關「VAST」的 Bug

```
bugissuecv VAST
```

> 查詢韌體驗證組發過有關「延遲、lag」的 Bug

```
bugissuecv 延遲 lag
```

> 查詢韌體驗證組發過有關「Motion、閃一下、壓力測試」的 Bug

```
bugissuecv Motion 閃一下 壓力測試
```

#### 

#### 情境二：查詢 \[專案\] \[特定功能\] 相關 Bug

> 查詢韌體驗證組發過有關「MS8392 壓力測試」的 Bug

```
bugissuecv MS8392 壓力測試
```

> 查詢韌體驗證組發過有關「IB8377 與 WDR 功能」的 Bug

```
bugissuecv IB8377 WDR
```

> 查詢韌體驗證組發過有關「IP816A 與 Firefox 瀏覽器」的 Bug

```
bugissuecv IP816A 瀏覽器 Firefox
```

> 查詢韌體驗證組發過有關「CC8160 與 Flip Mirror 」的 Bug

```
bugissuecv CC8160 flip mirror
```

#### 

#### 情境三：查詢 \[專案\] \[特定 Status\] 相關 Bug

> 查詢韌體驗證組發過有關「MS8391 狀態為 Limitation」的 Bug

```
bugissuecv MS8391 Limitation
```

> 查詢韌體驗證組發過有關「FD8166A-S 狀態為 New」的 Bug

```
bugissuecv FD8166A-S New
```

#### 

#### 情境四：查詢 \[專案\] \[FW version\] 相關 Bug

> 查詢韌體驗證組發過有關「IP816A 0200c」的 Bug

```
bugissuecv IP816A 0200c
```

#### 

#### 情境五：查詢 \[Common Bug\]

> 查詢韌體驗證組發過有關「Rossini 機種與 reboot 相關的 common bug」

```
bugissuecv Rossini common reboot
```

## 

---

## 指令使用說明

1. 使用者只能夠輸入1~3組關鍵字。
2. 關鍵字必須用空白來區格。
3. 不同專案的 Bug 建議輸入專案名稱來區隔，以便搜尋到更精確的結果。
4. 若輸入多個字串：Bugissuecv SD card，目前 bugissue 的搜尋機制會將查詢的字串判別為「SD」和「card」分開查詢。

---

## 提示訊息

1. There are no searching results. &gt;&gt; 找不到對應的搜尋結果，沒有對應的結果或是檢查是否輸入錯誤。
2. Syntax error: Keyword number is too long. &gt;&gt; 輸入3個以上的關鍵字，目前僅支援1~3個關鍵字。



