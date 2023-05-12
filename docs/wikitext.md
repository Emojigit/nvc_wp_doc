# 維基語法
## 標題
標題的標記方式爲：
```text
== 二級標題 ==
=== 三級標題 ===
==== 四級標題 ====
===== 五級標題 =====
```
理論上存在一級標題（`= 一級標題 =`），但是儘量避免，如需要改變標題應該使用`{{DISPLAYTITLE}}`[魔術字](#魔術字)。
## 列表
列表的標記方式爲：
<div style="display: grid; grid-gap: 10px; grid-template-columns: 50% 50%;">
<div>
```text
* 符號列表
** 符號列表
* 符號列表

# 數字列表
## 數字列表
# 數字列表
```
</div>
<div>
```text
; 定義列表 : 定義
; 定義列表 : 定義

: 縮排
:: 縮排
```
</div>
</div>
## 粗斜體
```text
'''粗體：三個單引號'''
''斜體：兩個單引號''
'''''粗斜體：五個單引號'''''
```
## 連結
<div style="display: grid; grid-gap: 10px; grid-template-columns: 50% 50%;">
<div>
<h3>外部連結</h3>
```text
https://zh.wikipedia.org 裸連結
[https://zh.wikipedia.org 帶有描述的連結]
[https://zh.wikipedia.org] 自動編號的連結
```
</div>
<div>
<h3>內部連結</h3>
```text
[[同一個維基百科的條目]]
又或者[[:en:Article on English Wikipedia]]
```
</div>
</div>

##
