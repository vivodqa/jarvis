# 指令名稱：bugissueiq

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 在DQA Redmine專案Bug Issue，依照Tracker: IQ Bug和IQ Common Bug找尋符合條件的IQ bug issue。 | 3 | DQA Redmine：http://dqa02/projects/dqa-test-1-bug | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之bug。 |

---

規則一：目前Jarvis版本，無法支援「聯集」（同時搜尋兩個相似義）的搜尋條件。

```
bugissueiq awb 白平衡

There are no searching results.
```

規則二：目前Jarvis版本，無法僅針對「標題」做關鍵字。故搜尋出來可能會出現較多較亂的結果。

```
bugissueiq wdr
```

規則三：由於One FW，在Redmine中，有些bug會在Common Bug，有些bug會在專案裡。所以，需分別搜尋。

```
bugissueiq ip9181 rolling
```

```
bugissueiq common rolling
```

```
bugissueiq hisilicon common rolling
```

```
bugissueiq ov4685 common
```

## 使用情境

> 查詢\[影像驗證組\]發過有關「白平衡」的 Bug Issue。

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

> 查詢\[影像驗證組\]的專案進測中，有哪些跟OV4685相關的WDR的Common Bug。

```
bugissueiq ov4685 common wdr
```



