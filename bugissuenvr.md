
---

# 指令名稱：bugissuenvr

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 在網路儲存驗證組中找尋符合條件的bug issue | 3 | DQA redmine | 針對「subject, description, id, status, tracker, custom fields, project目錄」欄位找尋，符合所有「搜尋條件」的「交集」之 網路儲存驗證組bug |

---

## 使用情境

> 查詢網路儲存驗證組發過有關「空白」的 bug

```
bugissuenvr 空白
```

> 查詢網路儲存驗證組發過有關「bugissuenvr、藍色、ND」的 bug

```
bugissuenvr 藍色 ND
```

---

bugissuenvr指令的資料，是根據NVR小組在DQA Redmine的bug list\([http://dqa02/projects/dqa-test-3-bug](http://dqa02/projects/dqa-test-3-bug)\)內所蒐尋到的 bug issue，在搜尋處打上 " bugissuenvr   想要搜尋的關鍵字 "，每個關鍵字必須以空格格開，其空格數不影響搜尋結果，英文字母的大小寫也不影響搜尋之結果\(如下圖\)

![](/assets/bugissuenvr1.png)

使用者只能打入1-3個關鍵字，若沒有打入任何關鍵字，系統會告知Keyword number is too short，若打入超過3個關鍵字，系統則會告知Keyword number is too long。在打入關鍵字後， jarvis會根據符合所有關鍵字之交集，顯現出結果 ，若此搜尋是有效的搜尋， jarvis 會顯現出 link 字樣，點選字樣會跳出連結，若是無效的搜尋，jarvis則會顯現出There are no searching results.，代表使用者所輸入的關鍵字或是關鍵字之交集沒有出現在 bug issue 中。

---

以下進行示範：

此範例想要查詢 NVR 的 bug list 中，包含 ND9541p 和 camera這兩個關鍵字的bug，在搜尋處打上 " bugissuenvr nd9541p camera "\(如下圖\)，並按下 Enter鍵

![](/assets/bugissuenvr2.png)

jarvis會在3秒內回覆搜尋之結果\(如下圖\)

![](/assets/bugissuenvr4.png)

點選 Link 連結查看搜尋結果![](/assets/bugissuenvr5.png)









