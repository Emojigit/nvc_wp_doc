# 如何存取維基百科
本文簡述如何存取維基百科，以及其他維基媒體項目。
## 基本資訊
維基百科的域名爲[wikipedia.org](https://wikipedia.org)，當中中文維基百科爲[zh.wikipedia.org](https://zh.wikipedia.org)。

維基媒體計劃擁有六個伺服器，三個在美國，其他分別於荷蘭、新加坡以及法國。
## 繞過網絡審查
維基百科目前在中國內地被封鎖，手段包括[DNS汙染][#解決DNS汙染：修改Host檔案]、IP封鎖以及[深度包檢測](https://zh.wikipedia.org/wiki/%E6%B7%B1%E5%BA%A6%E5%8C%85%E6%A3%80%E6%B5%8B)。
### 解決DNS汙染：修改Host檔案
防火長城會僞造DNS回應，可以透過以下方式繞過：
#### 修改Hosts檔案
[獲取Hosts檔案資料](https://api.thost3.de/ui/wm-hosts.html)，然後附加到本機Hosts檔案後。如果無法操作，請聯繫系統管理員或嘗試使用其他方法。
* Windows: `%WINDIR%\System32\drivers\etc\hosts`
* Unix和Linux: `/etc/hosts`
#### DNS over HTTPS
另一個方法是[DNS over HTTPS](https://zh.wikipedia.org/wiki/DNS_over_HTTPS)，爲使用HTTPS加密DNS請求的方法，防止域名請求竊聽和被修改。Chromium（含Chrome、Edge）以及Firefox對此有原生支援。
