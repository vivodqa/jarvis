# 指令名稱：status

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢專案時程和測試進度 | 3 | DQA redmine | 列出bugproject和schedule指令之結果 |

---

## 使用情境

> **查詢 rossini 67 系列測試的狀態，包括bug情況和測試進度**

![](/assets/status-1.png)

輸入

```
status rossini 67
```

Jarvis 回傳結果如下:

![](/assets/status-2.png)

註1: 

\#字號後方的數字代表 bug 數量，共有 Priority 1~4 與 Limitation、Wontfix 

可點選後方的數字進入連結

![](/assets/status-4.png)

點選數字後會新開網頁自動連到 DQA Redmine ![](/assets/status-5.png)

註2:

點選 Link 

![](/assets/status-6.png)

顯示 Jarvis 查詢結果

![](/assets/status-8.png)





