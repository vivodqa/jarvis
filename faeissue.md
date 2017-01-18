# 指令名稱：faeissue

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢客戶回報問題 | 3 | FAE系統匯出之excel|針對「problem_type, subject, case_number, product_name, case_cause, problem_summary, solution」欄位找尋，符合所有「搜尋條件」的「交集」結果|

---

## 使用情境

> 查詢 FAE 回報「FE8174、function」相關的問題

```
faeissue fe8174 function
```










