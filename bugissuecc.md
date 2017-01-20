# 指令名稱：bugissuecc

| 說明 | 條件數 | 來源 | 行為 |
| -| - | - | - |
|  在相容性驗證組中找尋符合條件的bug issue  | 3 | DQA redmine |針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之 相容性驗證組bug|

***
## 使用情境 
>查詢容性驗證組發過有關「reboot」的 bug

```
bugissuecc reboot
```
>查詢容性驗證組發過有關「milestone、PTZ」的 bug

```
bugissuecc milestone PTZ
```





































