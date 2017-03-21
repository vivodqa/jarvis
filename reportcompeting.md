# 指令名稱：reportiqpk

| 說明 | 條件數 | 來源 | 行為 |
| --- | --- | --- | --- |
| 查詢\[影像驗證組\]競品比較結果，包含測試報告和測試檔案。 | 3 | 影像驗證組在 "\\dqa03\IQ\_Testdata\02\_Benchmark\競品測試目錄.xls" | 針對「型號」、「廠牌」、「Feature」、「Resolution」欄位找尋，符合所有「搜尋條件」的「交集」結果。 |

---

* 規則一：VIVOTEK產品輸入型號的前六碼即可。例如：SD9364-EHL。

```
reportiqpk SD9364
```

* 規則二：競品產品輸入廠牌+型號中的四位數字即可。例如Hikvision DS-2CD2042WD-1。

```
reportiqpk hikvision 2042
```

* 規則三：VIVOTEK用VVTK表示。

Others Brand Name: asix, bosch, dahua, hikvision, panasonic, samsung, secubest, sony, vvtk.

```
reportiqpk vvtk
```

* 規則四：Feature的內容包含：WDR、SNV、IR、LowCost。

```
reportiqpk snv
```

* 規則五：目前Jarvis版本，無法支援「聯集」（同時比較兩台、同時比較1M和2M）的搜尋條件。

```
reportiqpk q1614 ip9181

There are no searching results.
```

```
reportiqpk 1m 2m

There are no searching results.
```

## 使用情境

> 查詢\[影像驗證組\]競品測試，有測過哪些VIVOTEK的WDR機種？

```
reportiqpk vvtk wdr
```

> 查詢\[影像驗證組\]競品測試，有測過哪些2M、Low-Cost的產品？

```
reportiqpk 2m lowcost
```

```
reportiqpk 5m wdr
```

> 查詢\[影像驗證組\]競品測試，有沒有測過IP9181或該系列的產品？

```
reportiqpk ip9181
```



