# 指令名稱：bugissuehw

| 說明 | 條件數 | 來源 | 行為 |
| -| - | - | - |
|  在產品驗證組中找尋符合條件的bug issue  | 3 | DQA redmine |針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之 產品驗證組bug|

***
## 使用情境 
>查詢產品驗證組發過有關「reset」的 bug

```
bugissuehw reset
```
>查詢產品驗證組發過有關「電壓、reset」的 bug

```
bugissuehw 電壓 reset
```





































