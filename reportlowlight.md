# 指令名稱：reportlowlight

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢\[影像驗證組\]的lowlight report數據，可知道進測的最終版本，其低照不同亮度的解析、FPS和Bitrate。 | 3 | 影像驗證組在 "\\\dqa03\IQ\_Testdata\03\_Project\Low Light Compare Test Data.xls" | 針對「型號」欄位找尋，符合所有「搜尋條件」的「交集」結果。 |

---

規則一：VIVOTEK產品輸入型號的前六碼即可。例如：SD9364-EHL。

```
reportlowlight SD9364
```

規則二：目前Jarvis版本，無法支援「聯集」（同時比較兩台）的搜尋條件。

```
reportlowlight ip9171 ip9181

There are no searching results.
```

## 使用情境

> 查詢\[影像驗證組\]的IP9181專案中，其Low Light解析、FPS和Bitrate為何？

```
reportlowlight ip9181
```

> 查詢\[影像驗證組\]的IP9181專案使用的Sensor、Lens以及MMI規格。

```
reportlowlight ip9181
```



