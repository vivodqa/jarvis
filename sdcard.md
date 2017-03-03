# 指令名稱：sdcard

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢SD卡測過哪些機種 | 3 | QMD KM上SD card compatibility test | 針對「camerabrand, cameramodel, sdcardbrand, sdcardmodel」欄位找尋，符合所有「搜尋條件」的「交集」結果 |

---

## 使用情境

**查詢特定型號的 Camera 測試特定品牌的 SD 卡紀錄 \(例如：SD9364 與 transcend\)**

![](/assets/輸入視窗.jpg)

輸入

```
sdcard sd9364 Transcend
```

獲得查詢結果，點選Link

![](/assets/sdcard_sd9364_Transcend.jpg)

查看查詢結果![](/assets/sdcard_sd9364_Transcend_check.jpg)

**查詢特定型號的 Camera 測試過哪些品牌的 SD 卡紀錄 \(例如：sd9364\)**

![](/assets/輸入視窗.jpg)

輸入

```
sdcard sd9364
```

獲得查詢結果，點選Link

![](/assets/sdcard_sd9364.jpg)

查看查詢結果![](/assets/sdcard_sd9364_check.jpg)

**查詢特定品牌的 SD 卡測試過哪些 Camera 的紀錄 \(例如：sandisk、transcend\)**

![](/assets/輸入視窗.jpg)

輸入

```
sdcard sandisk
```

獲得查詢結果，點選Link

![](/assets/sdcard%20sandisk.jpg)

查看查詢結果![](/assets/sdcard%20sandisk_check.jpg)

