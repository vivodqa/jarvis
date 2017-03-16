# 指令名稱：reportrelated

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢軟體驗證組report搭配測試資訊 | 3 | 軟體驗證組在testrail 的report | 針對「report\_name, report\_description」欄位找尋，符合所有「搜尋條件」的「交集」結果 |

---

## 使用情境

> 查詢軟體驗證組有關 iViewer2 iOS 版本 3.6.101 的測試結果

```
reportrelated iOS iViewer2 3.6.101
```

> 查詢軟體驗證組有關 iViewer2 android 版本搭配 VAST 的測試結果

```
reportrelated iViewer android VAST
```

> 查詢軟體驗證組有關 EZConnect 搭配 NVR 的測試結果 \(ex. ND9541\)

```
reportrelated EZConnect ND9541
```

> 查詢軟體驗證組有關 EZConnect 版本 2.1.4 搭配 Camera 的測試結果

```
reportrelated EZConnect 2.1.4 camera
```

> 查詢軟體驗證組有關 VAST 版本 1.12.1.5 搭配 OS 的測試結果

```
reportrelated VAST 1.12.1.5 OS
```



