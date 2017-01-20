# 指令名稱：report

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢report | 3 | DQA各組在testrail, dqa03的report位置 | 針對「report路徑, report名稱, report所屬testrail project」找尋，符合所有「搜尋條件」的「交集」結果|

---

## 使用情境

> 查詢影像驗證組有關「FE9381、agc」相關的測試報告

```
report 驗證五組 agc FE9381
```
> 查詢驗證三組有關 ND9541 第2.1.0版的測試報告

```
report 驗證三組 ND9541 2.1.0

```






