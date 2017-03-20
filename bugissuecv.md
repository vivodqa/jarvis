# 指令名稱：bugissuecv

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 在韌體驗證組中找尋符合條件的bug issue | 3 | DQA redmine | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之 韌體驗證組bug |

---

## 使用情境

> 查詢韌體驗證組發過有關「VAST」的 bug

```
bugissuecv VAST
```

> 查詢韌體驗證組發過有關「延遲、lag」的 bug

```
bugissuecv 延遲 lag
```

> 查詢韌體驗證組發過有關「MS8392 壓力測試」的Bug

```
bugissuecv MS8392 壓力測試
```

> 查詢韌體驗證組發過有關「IB8377 與 WDR 功能」的Bug

```
bugissuecv IB8377 WDR
```

> 查詢韌體驗證組發過有關「IP816A 與 Firefox 瀏覽器」的Bug

```
bugissuecv IP816A 瀏覽器 Firefox
```

> 查詢韌體驗證組發過有關「CC8160 與 Flip Mirror」的Bug

```
bugissuecv CC8160 flip mirror
```

## 使用限制

1. 使用者只能夠輸入1~3組關鍵字。
2. 關鍵字必須用空白來區格。
3. 在不同專案的Bug建議輸入專案名稱來區隔，以便搜尋到更精確的結果。



