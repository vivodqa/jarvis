# 指令名稱：dqaissue

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢符合條件的issue | 3 | DQA redmine | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之 issue |

---

## 使用情境

> * 查詢 DQA redmine 有關 lag 和 alarm 交集相關的 issue

輸入

```
dqaissue lag alarm
```

![](/assets/2017-03-10_143613.PNG)

出現查詢結果，開啟 Link

![](/assets/2017-03-13_162901.PNG)

JARVIS 查詢結果：

![](/assets/2017-03-10_143919.PNG)

或輸入

```
dqaissue alarm lag
```

出現查詢結果，開啟 Link

![](/assets/2017-03-13_162921.PNG)

JARVIS 查詢結果：

![](/assets/2017-03-13_162547.PNG)

> * 查詢 DQA redmine 有關版本 2.1.3 和 push 交集相關的 issue

輸入

```
dqaissue 2.1.3 push
```

出現查詢結果，開啟 Link

![](/assets/2017-03-13_171106.PNG)

JARVIS 查詢結果：

![](/assets/2017-03-13_170645.PNG)

或輸入

```
dqaissue push 2.1.3
```

出現查詢結果，開啟 Link

![](/assets/2017-03-13_171114.PNG)

JARVIS 查詢結果：

![](/assets/2017-03-13_170746.PNG)

查詢特定機種的專案狀態為何 \(含歷史所有版本狀態\)

輸入

```
dqaissue [Firmware Release] FD8166
```

![](/assets/2017-03-10_143613.PNG)

出現查詢結果，開啟 Link

![](/assets/dqaissue [Firmware Release] FD8166)

JARVIS 查詢結果：

![](/assets/dqaissue [Firmware Release] FD8166 check)







