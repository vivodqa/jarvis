# 指令名稱：report

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢report | 3 | DQA各組在testrail, dqa03的report位置 | 針對「report路徑, report名稱, report所屬testrail project」找尋，符合所有「搜尋條件」的「交集」結果 |

---

## 使用情境

> 查詢 “影像驗證組” 有關「FE9381、agc」相關的測試報告

```
report 驗證五組 agc FE9381
```

> 查詢 “網路儲存驗證組” 有關 ND9541 第2.1.0版的測試報告

```
report 驗證三組 ND9541 2.1.0
```

> 查詢 “韌體驗證組” 有關 FE9181 FPS、CPU Loading、CBR、VBR 測試結果的 Performance 測試報告

```
report FE9181 performance
```

> 當不知道有哪些東西可查時，只輸入 report + \[model\]；將會列出該 model 所有在 testrail、dqa03 上的所有測試報告。

```
report FE9181
```



