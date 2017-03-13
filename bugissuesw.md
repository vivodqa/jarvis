# 指令名稱：bugissuesw

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 在軟體驗證組中找尋符合條件的bug issue | 3 | DQA redmine | 針對「subject, description, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之 軟體驗證組bug |

---

使用情境

> 查詢軟體驗證組主旨及內容有「CPU」的 bug

```
 bugissuesw CPU
```

> 查詢軟體驗證組 Status 為「New」且 Project 為「EZConnect」的 bug

```
 bugissuesw new ezconnect
```

> 查詢軟體驗證組「FAE」回報且 customer type 為「Distributor」 的 bug

```
 bugissuesw fae distributor
```

> 查詢軟體驗證組 Project 為「iViewer」且主旨內容含「crash」的 bug

```
 bugissuesw iviewer crash
```

> 查詢軟體驗證組 Project 為「VAST」且測試 camera 為「IP9181」的 bug

```
 bugissuesw VAST ip9181
```



