# 本篇介紹Github READMD.MD的編寫  
最近對README.md檔案頗為感興趣。便寫了以下介紹，介紹很多常見的寫法。
>> README檔案字尾名為md。md是markdown的縮寫，markdown是一種編輯部落格的語言，不過GitHub支援的語法在標準markdown語法的基礎上做了修改，稱為Github Flavored Markdown，簡稱GFM。  
***
#### 橫線  
`***、---、___`->都可以顯示橫線效果
***
#### 標題  
###### 分為一到六級標題->由`#`的數量決定，#為最大一級標題，一級和二級標題下方自動會有分隔線。
***
#### 文字高亮    
###### 此功能能使行內部分`文字高亮`，使用一對反引號 ` ` ，也是合作一篇文章的tag 
***
#### 換行  
###### 在上一行文本的最後`補兩個空白鍵`，下一行的文本就會換行了，或是`在兩行文本直接加一個空行`，也能實現換行效果，不過行間距會比較大
***
#### 斜體、粗體、刪除線
語法    效果  
`*斜體1*`	*斜體1*  
`_斜體2_`	_斜體2_  
`**粗體1**`	**粗體1**  
`__粗體2__`	__粗體2__   
這是一個 `~~這是一個~~`	這是一個 ~~刪除線~~  
`***斜粗體1***`	***斜粗體1***  
`___斜粗體2___`	___斜粗體2___  
`***~~斜粗體刪除線1~~***`	~~***斜粗體刪除線1~~***    
`~~***斜粗體刪除線2***~~`	~~***斜粗體刪除線2***~~   
***
#### 圖片
基本格式:`![alt](URL title)`
alt和title可對應到HTML中的alt和title屬性（都可省略）：
alt表示圖片顯示失敗時的替代文本
title表示鼠標懸停在圖片時的替代文本（要加引號）
URl及為圖片的地址，要用倉庫中的圖片，直接使用`相對路徑`即可，如果要引用其他github倉庫中的圖片要注意格式，
即 `倉庫地址/raw(每個人倉庫名稱不一樣)/master/資料夾/圖片名稱(路徑)`  
ex:`![NCTU](https://github.com/DONG-GUAN-CHENG/pages-demo/blob/master/photo/交7.jpg "交通大學")`
![NCTU](https://github.com/DONG-GUAN-CHENG/pages-demo/blob/master/photo/交7.jpg "交通大學")
***
#### 鏈結
連接外部URL方式:
基本格式:`[我的網站](https://dong-guan-cheng.github.io/pages-demo/project%20web%20dong/guanweb.html "懸停顯示")`  
[我的網站](https://dong-guan-cheng.github.io/pages-demo/project%20web%20dong/guanweb.html "懸停顯示")  
連接本倉庫URL:  
`ex:[](/aa/bb.md)`
***
#### 列表  
無序列表  
語法:   
`* 董貫程`  
`- 英文名：Bill`  
效果:    
* 董貫程  
- 英文名：Bill  
***
#### 複選框列表  
語法:  
`- [x] C++/C`    
`- [x] python`  
`- [ ] sql`  
`- [ ] java`  
效果:
- [x] C++/C    
- [x] python  
- [ ] sql  
- [ ] java  
可用此功能來標注各項任務達成情況
***
#### 多級結構
語法:
`> 妳`
`>> 我`
`>>> 他`
效果:
> 妳
>> 我
>>> 他
***   
#### 代碼區塊高亮  
可以用```包覆  
***
以上是常用的markdown語法，想知道更多用法可以查看 https://www.itread01.com/content/1546796175.html
