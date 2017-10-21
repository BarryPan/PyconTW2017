# PyconTW2017
This is for my speech in PyconTW 2017.

To understand what I said in PyconTW2017 about text mining, we put our code to GitHub as a reference. If you have any questions, feel free to contact us. We will appreciate to that!

Code demo: https://barrypan.github.io/PyconTW2017/demo

Video link: https://www.youtube.com/watch?v=zgzBxIUZZ2s&list=PLqtzN042Qpffip6u4_WUTRXxFZDgdgrPV&index=22

Slide link: https://www.slideshare.net/ssuserf1b9cf/pythonpycontw2017

## English Abstract
The speech is a guidance for beginners to get involve with the technics of text mining. After the speech, we hope everyone will be able to start your own text mining projects and find some interesting insights behind the data.

In this speech we use data from PTT, one of the most famous Taiwanese forum, to apply text mining techniques in order to find out the best investment strategy. In the end, we can use sentiment analysis to track the opinion from the internet and make an investment strategy with return of 15.5%. 

In the analysis, we first use basic exploratory data analysis skills to understand the pattern in PTT, such as when is the most popular time for users to post. After that, we choose the event of [XPEC Entertainment (3662)](https://en.wikipedia.org/wiki/XPEC_Entertainment) to give a further analyze about the attitude for the PTT users.

After the fundamental analysis, we use Python "word2vec" package to transform articles relating to [Trump](https://en.wikipedia.org/wiki/Donald_Trump), to understand the correlation between American election and Taiwanese stock performance.

In the end, we apply Python "snownlp" package to analyze users' feeling toward [K WAY (5201)](http://www.kway.com.tw/english/Default.htm). Based on the sentimental analysis, we can construct an investment strategy. It turns out has a good performance of 15.5% return during the period between 6/1/2016 and 2/1/2017. 

## Chinese Abstract
為了使「用Python成為網路投資王」聽眾能更快加入使用Python進行文字分析的行列中，我們特別將我們的程式碼整理好後放到GitHub當中提供大家參考
後續如果有任何問題，都可以再與我們聯絡指教，再次謝謝大家來此聆聽，謝謝！

## Important Information
本程式碼使用Python 2.7撰寫，並以mac執行

## data folder
data folder 主要是儲存原始資料

## outcome folder
outcome folder 主要儲存程式跑出來的中繼表格

## demo folder
此次演講主要程式使用Jupyter進行撰寫，原始Jupyter notebook 儲存於demo folder之下
