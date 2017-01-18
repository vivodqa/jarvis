# 指令名稱：onvif

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢Camera測試過的onvif版本、查詢特定onvif版本測過哪些camera | 3 | QMD KM上VVTK ONVIF approval status | 針對「model, onvif_version, fw_version, comment」欄位找尋，符合所有「搜尋條件」的「交集」結果
|

---

## 使用情境

> 查詢 SD9364 onvif第15.06版測試的情況

```
onvif 15.06 SD9364
```



