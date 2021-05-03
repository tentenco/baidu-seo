# baidu-seo
百度快排 - Baidu SEO

# 什麼是百度發包排名？百度快排（百度快速排名）是什麼？

### 現在的百度發包排名、百度快排（百度快速排名）是什麼？

#### 是否適用於Google？　　
之前和做百度快排的公司里的朋友聊過一次，根據所測試，百度快速排名的原理依然是模擬點擊，只是技術較前幾年提升了許多，沒聽過這種公司做百度快排還有更新的手法，只是現在的百度快排軟體比　　前幾年的百度點擊器優化了太多自然規則，比如控制時間、點擊數量、ip地址盡量區域化、及瀏覽器。還有避免被流量統計軟體計入訪問量等等。值得鼓勵的是這些做快排的公司一直在不斷完善及改進演算法；　　

### 關於發包技術：　　
再次講下，外面流傳的」百度發包」技術，做過測試，並沒有所謂的發包，只是和模擬點擊一樣的東西，或許只是起一個高大上的名字而已。　　據我所知，百度SEO這個熱門詞，目前排前面幾頁的都是快排點擊做上去的，導致很多老站，質量站都排在了後面，所以使用百度快速排名工具，做快排值得一試。

### 關於百度點擊快排是否適用Google
根據多方測試：做百度快排及之前早期百度點擊器都測試過Google，不過，貌似沒成功的，所以感覺Google的技術還是更成熟一點；

![](https://i.imgur.com/KiwlBqu.jpg)

# 百度快排發包演算法:百度快排URL參數及演算法揭秘

到底有沒有[百度發包演算法](https://hypergrowths.com/digital-marketing/seo/baidu-seo/ "查看與 百度發包演算法 相關的文章")，看到很多SEO大哥技術群交流的時候經常提到「**[百度發包快排](http://www.seo.ren/tag/%e7%99%be%e5%ba%a6%e5%8f%91%e5%8c%85%e5%bf%ab%e6%8e%92/ "查看與 百度發包快排 相關的文章")演算法**」，發包真的存在嗎？黑酷老師也和很多做快排的交流過，其實是不存在真正意義的發包，市面主流快排還是以URL參數為主，比如si參數等等，但是，黑酷老師理解的，一般就是post，get等方式將電機參數為數據包發送給百度 伺服器，而理論上[百度發包快排](https://hypergrowths.com/digital-marketing/seo/baidu-seo/ "查看與 百度發包快排 相關的文章")可以實現無排名的新站快速上首頁。

百度發包快排和百度點擊快排類似但發包省略了點擊的步驟，發包快排原理簡單說就是直接打包get點擊參數為數據包后發送給百度 伺服器。而理論上百度發包快排可以實現無排名的新站快速上首頁。從技術角度來講，發布已經不屬於普通SEOer的技能範圍，沒必要研究。發包的門檻很高及需要一些資源對接支持!

發本文主要是因為本SEO部落格轉載**黑酷老師**的《教你判斷做百度SEO快排》這篇文章隨後被沒有敬畏之心的鍵盤俠罵了，雖然我刪除了評論，但不否認我心有芥蒂!現在我來發點我所知道發包快排的一點小東西 百度搜索點擊參數。這個是打包數據的主要數據。

百度發包快排搜索點擊[快排參數](https://hypergrowths.com/digital-marketing/seo/baidu-seo/ "查看與 快排參數 相關的文章")

首先我們參考百度URL：https://bit.ly/3vDfvkQ
我們對百度快排參數url格式整理分析：

* 一、https：SSL證書的加密超文本傳輸協議!

* //www.baidu.com/：百度等搜索引擎域名

* 二、s? s: 這是一種無擴展名的方法實現的。

* 三、ie=utf-8 ie:關鍵字編碼格式默認為：GB2312 簡體中文

* 四、f=8 f: 值有：1，3，8大概還有其他的，臨時發現就這3種。

* 百度[快排參數](https://hypergrowths.com/digital-marketing/seo/baidu-seo/ "查看與 快排參數 相關的文章")值1指的是相干搜索，透露表現用戶選擇了搜索頁面最下面的「相關搜索」中的某個關鍵詞。;

* 百度[快排參數](https://hypergrowths.com/digital-marketing/seo/baidu-seo/ "查看與 快排參數 相關的文章")值3下拉框搜索透露表現用戶輸入肯定的詞語之後出現「聯想詞語」，用戶最終用 滑鼠選擇了某個關鍵詞;或用鍵盤選擇了某個關鍵詞后直接按回車。;

* [百度快排](https://hypergrowths.com/digital-marketing/seo/baidu-seo/ "查看與 百度快排 相關的文章")參數值8用戶自立搜索，透露表現用戶直接點擊「百度一下」按鍵(有bs變數時才出現f=8)

* 五、rsv\_bp=1 rsv\_bp:使用的是百度哪一個搜索框0是首頁輸入;1是頂部搜索輸入;2是底部搜索輸入

* 六、rsv\_idx=2 rsv idx：未知

* 七、tn=baiduhome\_pg tn: 提交搜索請求來源例如：tn=50000021\_hao\_pg用hao123 里的百度搜的

* 八、tn=baidulocal表示百度站內搜索，返回的結果很乾凈，無廣告干擾。當tn= baiduerr 表示這是從錯誤頁搜索跳轉過來的

* 九、wd=百度發包快排 wd:查詢關鍵字 (word) 一般以也會是一串字元例如：%E7%99%BE%E5%BA%A6%E5%8F%91%E5%8C%85%E5%BF%AB%E6%8E%92 如果你用url編碼方式進行解碼你才能看到真實的內容

* 十、rsv\_spt=1 rsv\_spt：表示首頁搜索瀏覽器內核版本類型,1表示新版百度首頁搜索(先要登錄百度帳號)2表示百度即時熱點搜索(先要登錄百度帳號)3表示傳統百度首頁搜索

* 十一、oq=黑帽SEO部落格 oq:上次索引關鍵字 rsv\_pq=9ae87b9e0000af9a rsv\_pq：透露表現用來記錄關鍵詞和上一次搜素的關鍵詞(相關關鍵詞)的

* rsv\_t rsv\_t=64a2xLPgOIqVeiuTYMJ2vghLIMU2amOkhpFAUsNeIXZ6aMAmwitsrebiPa%2BGy1E8WWZa rsv\_t：搜索效果的一種隨機密碼措施

* 十二、rqlang=cn rqlang：跟地域有關cn是代表中國地域

* 十三、rsv\_enter=0 rsv\_enter：未知 rsv\_sug=1 含義 搜索框提示的搜索歷史記錄(Search history) 參數值:0 搜索框提示0條搜索歷史記錄1 搜索框提示1條搜索歷史記錄2 搜索框提示2條搜索歷史記錄

* 十四、inputT=2335 inputT：透露表現的是搜索相應時間，單位是毫秒;

* 十五、rsv\_sug3=1 未知

* 十六、rsv\_sug1=1 搜索框提示次數

* 十七、rsv\_sug7=100 未知

* 十八、rsv\_sug4=1395 未知

* 十九、rev\_ers ers: rsv\_ers xn\* (\*取0或1) 指的是搜尋關鍵字后，翻頁出現對應的相干搜索，從0開始。假如在url里已經是0的話，那對應的相干搜索就從1開始(這個參數還有許多密，這個只是初步測試)

* 二十、rn rn:每頁顯示數目 默認為10 最大50

* 二十一、pn pn:顯示結果頁數默認為0 其他每頁遞增rn 即：rn為20時第1頁 pn=0 第2頁 pn=20 第3頁 pn=40

* 二十二、cl cl： 百度提交的搜索類型(Class),cl=3為網頁搜索，cl=2為百度消息

* 二十三、ct 語言限定。0-所有語言，1-簡體中文網頁，2-繁體中文網頁;其它不確定或者無效或。默認值為0.

* 二十四、si 在限定的域名中搜索,比如想在本站內搜索可使用參數si=www.wlsem.cn,要使這個參數有效必須結合ct參數一起使用;

* 二十五、bs(Before Search) 上一次搜索的關鍵詞;

* 二十六、lm=0 搜索結果時間限制)以天為單位，例如搜索最近一個月的網頁，lm=30.默認值為0,表示沒有時間限制。

* 二十七、ft 搜索的文檔格式，pdf、doc、xls、ppt、rtf等，默認值為空。

* 二十八、q1 包含以下的悉數的關鍵詞

* 二十九、q2 包含以下的完備關鍵詞

* 三十、q3 包含以下任意一個關鍵詞

* 三十一、q4 不包括以下關鍵詞

三十二、q5 搜索內容位置限制.0-所有內容;1-網頁標題(相當於使用'title:'查詢前綴);2-url(相當於使用'inurl:'查詢前綴);其它值等效于0.默認值為0

三十三、q6 搜索內容網站限制.例如q6=www.baidu.com,表示只搜索www.baidu.com的網頁;相當於使用了'site:前綴'.默認值為空

三十四、dq [百度快排](https://hypergrowths.com/digital-marketing/seo/baidu-seo/ "查看與 百度快排 相關的文章")參數不建議使用該參數.查詢內容來原的地區限制.


![](https://i.imgur.com/FKQgVWy.jpg)

## 想了解更多關於百度快排 SEO?
- https://hypergrowths.com/digital-marketing/seo/baidu-seo/
- https://seo.tenten.co/
