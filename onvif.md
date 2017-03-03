# 指令名稱：onvif

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢Camera測試過的onvif版本、查詢特定onvif版本測過哪些camera | 3 | QMD KM上VVTK ONVIF approval status | 針對「model, onvif\_version, fw\_version, comment」欄位找尋，符合所有「搜尋條件」的「交集」結果 |

---

## 使用情境

**查詢 SD9364 是否通過 15.06 版的認證**

![](/assets/輸入視窗.jpg)

輸入

```
onvif 15.06 SD9364
```

獲得查詢結果，點選Link

![](/assets/onvif_sd9364_ver.jpg)

查看查詢結果![](/assets/onvif_sd9364_ver_check.jpg)或輸入

```
onvif SD9364 15.06
```

獲得查詢結果，點選Link

![](/assets/onvif_sd9364_ver_2.jpg)

查看查詢結果![](/assets/onvif_sd9364_ver_check.jpg)

**查詢特定機種是否曾經獲得 onvif 的認證 \(例如：CC8160 \)**

![](/assets/輸入視窗.jpg)

輸入

```
onvif cc8160
```

獲得查詢結果，點選Link

![](/assets/onvif_cc8160.jpg)

查看查詢結果![](/assets/onvif_cc8160_check.jpg)

**查詢特定類型的 Camera 獲得 onvif 的認證狀態 \(例如：SD、FD、IP、IB、IZ \)**

![](blob:https://www.gitbook.com/ebbf3b1e-3d2f-401a-b5a5-1f47dad132cf)

輸入

```
onvif fd
```

獲得查詢結果，點選Link

![](/assets/onvif_fd.jpg)

查看查詢結果

![](/assets/onvif_fd_check.jpg)

**查詢特定的 onvif 版本有哪些 Camera 經過認證 \(例如：16.01、15.06 \)**

![](blob:https://www.gitbook.com/ebbf3b1e-3d2f-401a-b5a5-1f47dad132cf)

輸入

```
onvif 16.01
```

獲得查詢結果，點選Link

![](/assets/onvif.jpg)

查看查詢結果![](/assets/onvif_check.jpg)

