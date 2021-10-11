巴哈姆特動漫新番觀看分析
===


# Introduction
爬取巴哈姆特的動畫瘋網站資訊，可以快速統計觀看次數(繪製呈長條圖)以及動畫相關資訊，並透過視覺化界面來呈現。

# Detail

爬取依照人氣排列之新番動漫URL。

根據視覺化界面所點選之動畫，爬取所有標籤，並統計觀看製作圖表，以便了解觀看趨勢。

以tkinter來撰寫視覺化界面，透過listbox讓使用者選取目前新番，可以快速取得新番各項資訊，當每次要分析和觀看熱門動畫、已出集數、評分……就不用再一一點選頁面去搜尋。

針對站方正在統計觀看數據時的情況給予使用者提醒。
# Demo
動畫瘋網頁

![](https://i.imgur.com/lQEC4xm.png)

內容詳細資訊

![](https://i.imgur.com/kectYpv.png)

視覺化界面

![](https://i.imgur.com/O74Uv2Z.png)

統計觀看數中

![](https://i.imgur.com/9bIa8x2.png)


# Requirement
    bs4
    matplotlib
    PIL

# Package
    bahamut_views
        │  icon.ico        圖標
        │  loading.png     統計中圖片
        │  main.py         主要GUI程式
        │  views.png       繪出每節觀看人數
        │  web_scraping.py 爬蟲程式
# Problems
1.有些站方還在統計，會導致程式出錯


# Solve
1.使用統計中圖示來告訴使用者