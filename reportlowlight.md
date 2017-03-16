# 指令名稱：reportlowlight

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢\[影像驗證組\]的lowlight report數據，可知道道進測的最終版本，其低照影像品質和Bitrate。 | 3 | 影像驗證組在dqa03上02\_TestReport\03\_Project的lowlight report | 針對「廠牌」、「型號」欄位找尋，符合所有「搜尋條件」的「交集」結果。 |

---

規則一：VIVOTEK產品輸入型號的前六碼即可。例如：SD9364-EHL。

```
reportlowlight SD9364
```

規則二：競品產品輸入廠牌+型號中的四位數字即可。例如Bosch NBN80052-BA。

```
reportlowlight bosch 0052
```

規則三：目前Javis版本，無法支援「聯集」（同時比較兩台）的搜尋條件。

```
reportlowlight ip9171 ip9181     NG!
```

## 使用情境

> 查詢\[影像驗證組\]的IP9181專案中，其Low Light影像品質以及Bitrate為何？

```
reportlowlight ip9181
```

> 查詢\[影像驗證組\]的IP9181專案使用的鏡頭型號以及Low Lex規格。

```
reportlowlight ip9181
```



