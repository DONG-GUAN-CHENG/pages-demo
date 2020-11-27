# 本篇介紹Github READMD.MD的編寫  
最近對它的README.md檔案頗為感興趣。便寫了以下介紹，介紹很多常見的寫法。
>> README檔案字尾名為md。md是markdown的縮寫，markdown是一種編輯部落格的語言，不過GitHub支援的語法在標準markdown語法的基礎上做了修改，稱為Github Flavored Markdown，簡稱GFM。  
***
#### 橫線  
###### `***、---(細線)、___`->都可以顯示橫線效果
---
#### 標題  
###### 分為一到六級標題->由`#`的數量決定，#為最大一級標題，一級和二級標題下方自動會有分隔線。
---
#### 文字高亮    
###### 此功能能使行內部分`文字高亮`，使用一對反引號 ` ` ，也是合作一篇文章的tag 
---
#### 換行  
###### 在上一行文本的最後`補兩個空白鍵`，下一行的文本就會換行了，或是`在兩行文本直接加一個空行`，也能實現換行效果，不過行間距會比較大
---
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
#### 圖片
基本格式:![alt](URL title)  
alt和title可對應到HTML中的alt和title屬性（都可省略）：
alt表示圖片顯示失敗時的替代文本
title表示鼠標懸停在圖片時的替代文本（要加引號）
URl及為圖片的地址，要用倉庫中的圖片，直接使用`相對路徑`即可
ex:
![NCTU](https://www.google.com/imgres?imgurl=https%3A%2F%2Flookaside.fbsbx.com%2Flookaside%2Fcrawler%2Fmedia%2F%3Fmedia_id%3D1662111860505202&imgrefurl=https%3A%2F%2Fwww.facebook.com%2Fnctu.edu.tw%2F&tbnid=L4QmmRCWQvZafM&vet=12ahUKEwjI8cjhm6PtAhVW82EKHZbwA9AQMygCegUIARCnAQ..i&docid=56zhu1Plj4fbdM&w=960&h=640&q=%E4%BA%A4%E9%80%9A%E5%A4%A7%E5%AD%B8&ved=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 "交通大學")
