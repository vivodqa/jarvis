# 指令名稱：reportlight

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢影像驗證組的lowlight report數據 | 3 | 影像驗證組在dqa03上的lowlight report | 針對「camera_brand, camera_model」欄位找尋，符合所有「搜尋條件」的「交集」結果|

---

## 使用情境

> 查詢影像驗證組有關 Axis Q1615 camera 的 lowlight測試結果

```
reportlowlight axis Q1615
```



