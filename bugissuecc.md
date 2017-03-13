# 指令名稱：bugissuecc

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 在相容性驗證組中找尋符合條件的bug issue | 3 | DQA redmine | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之 相容性驗證組bug |

---

## 使用情境

**查詢特定機種的所有相容性相關Bug \(例如：CC8160\)**

![](/assets/輸入視窗.jpg)

輸入

```
bugissuecc cc8160
```

獲得查詢結果，點選Link

![](/assets/bugissuecc_cc8160.jpg)

查看查詢結果

![](/assets/bugissuecc_cc8160_check.jpg)

**查詢特定機種，在相容性測試中，是否有 Milestone 平台的 Bug \(例如：CC8160 milestone\)**

![](/assets/輸入視窗.jpg)

輸入

```
bugissuecc cc8160 milestone
```

獲得查詢結果，點選Link

![](/assets/import.png)

查看查詢結果

![](/assets/bugissuecc_cc8160_milestone_check.jpg)

**查詢特定機種，在相容性測試中，是否有 Milestone 平台上操作 Zoom 的 Bug \(例如：IZ9361 milestone zoom\)**

![](/assets/輸入視窗.jpg)

輸入

```
bugissuecc iz9361 milestone zoom
```

獲得查詢結果，點選Link

![](/assets/bugissuecc iz9361 milestone zoom)

查看查詢結果

![](/assets/bugissuecc iz9361 milestone zoom check)

**查詢相容性測試中，是否有 SD Card 相關的 Bug \(例如：sdcard\)**

![](/assets/輸入視窗.jpg)

輸入

```
bugissuecc sdcard
```

獲得查詢結果，點選Link

![](/assets/bugissuecc sdcard)

查看查詢結果

![](/assets/bugissuecc_sdcard)

