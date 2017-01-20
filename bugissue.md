# 指令名稱：bugissue

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢符合條件的bug issue | 3 | DQA redmine | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」結果。 |

---

## 使用情境

> 查詢「lag」所有相關的 bug

```
bugissue lag
```

> 查詢「lag、延遲」所有相關的 bug

```
bugissue lag 延遲
```



