# 指令名稱：bugissueiq

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 在影像驗證組中找尋符合條件的bug issue。 | 3 | DQA redmine | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之bug。 |

---

規則一：目前Javis版本，無法支援「聯集」（同時搜尋兩個相似義）的搜尋條件。

```
bugissueiq awb 白平衡

There are no searching results.
```

規則二：目前Javis版本，無法僅針對「標題」做關鍵字。故搜尋出來可能會出現較多較亂的結果。

```
bugissueiq wdr
```

規則三：由於One FW，在Redmine中，有些bug會在Common Bug，有些bug會在專案裡。所以，需分別搜尋。

```
bugissueiq ip9181 rolling
```

```
bugissueiq hisilicon common rolling
```

## 使用情境

> 查詢\[影像驗證組\]發過有關「白平衡」的 bug issue。

```
bugissueiq 白平衡
```

> 查詢\[影像驗證組\]的IP9181專案中，有哪些Limitation的Bug Issue。

```
bugissueiq ip9181 limitation
```

> 查詢\[影像驗證組\]的IP9181專案中，有哪些WDR相關的Limitation的Bug Issue。

```
bugissueiq ip9181 wdr limitation
```



