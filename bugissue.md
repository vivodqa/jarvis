# 指令名稱：bugissue

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢符合條件的bug issue | 3 | DQA redmine | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」結果。 |

---

## 使用情境

> 查詢「lag」所有相關的 bug

```
bugissue lag
```

> 查詢「lag、延遲」所有相關的 bug

```
bugissue lag 延遲
```

---

bugissue指令的資料，是在DQA Redmine內所蒐尋到所有組別的 bug issue，在搜尋處打上 " bugissue   想要搜尋的關鍵字 "，每個關鍵字必須以空格格開，其空格數不影響搜尋結果，英文字母的大小寫也不影響搜尋之結果\(如下圖\)

![](/assets/bugissue1.png)

使用者只能打入1-3個關鍵字，若沒有打入任何關鍵字，系統會告知Keyword number is too short，若打入超過4\(含\)個關鍵字，系統則會告知Keyword number is too long。在打入關鍵字後， jarvis會根據符合所有關鍵字之交集，顯現出結果 ，若此搜尋是有效的搜尋， jarvis 會顯現出 link 字樣，點選字樣會跳出連結，若是無效的搜尋，jarvis則會顯現出There are no searching results.，代表使用者所輸入的關鍵字或是關鍵字之交集沒有出現在 bug issue 中。

---

以下進行示範：

此範例想要查詢DQA Redmin中所有組別的bug issue，是否有包含 壓力測試 和 VAST 這兩個關鍵字的bug issue，在搜尋處打上 " bugissue 壓力測試 vast "\(如下圖\)，並按下 Enter鍵

![](/assets/bugissue3.png)



jarvis會在3秒內回覆搜尋之結果\(如下圖\)

![](/assets/bugissue4.png)



點選 Link 連結查看搜尋結果\(如下圖\)![](/assets/bugissue5.png)

