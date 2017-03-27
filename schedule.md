# 指令名稱：schedule

| 說明 | 條件數 | 來源 | 行為 |
| :--- | :--- | :--- | :--- |
| 查詢DQA已安排的測試進度 | 3 | DQA Redmine/測試時程需求 \(Test Schedule Request \), S/W Test Request, NVR Test Request | 針對「Model name, SOC」欄位找尋，符合所有「搜尋條件」的「交集」結果 |

---

## 使用情境

> 查詢 6B series 的測試進度

```
schedule 6B
```

查詢結果

![](/assets/search_6B.jpg)

查詢 6B series 的測試進度

```
schedule 6B f3 rossini
```

查詢結果

![](/assets/search_6B_f3_rossini.jpg)

