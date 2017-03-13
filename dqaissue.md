# 指令名稱：dqaissue

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢符合條件的issue | 3 | DQA redmine | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之 issue |

---

## 使用情境

> 查詢 DQA redmine 有關 lag 和 alarm 交集相關的issue

輸入

```
dqaissue lag alarm
```

![](/assets/2017-03-10_143613.PNG)

獲得查詢結果，點選Link

![](/assets/2017-03-10_145500.PNG)

查看查詢結果

![](/assets/2017-03-10_143919.PNG)

