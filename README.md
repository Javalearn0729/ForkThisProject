# ForkThisProject

***在V1.0主程式上傳前需要做的事***.   
1.小組成員都在自己的Oracle DB建同名同密碼的帳號.  
2.grant all privileges to userName identified by password;  
3.寫好透過 Datasource 方式串接JDBC連線到資料庫的Servlet程式，然後建個簡單表格做新增刪除的測試. 
4.if (測試ok) { 上傳該servlet程式當V1.0的專案，大家可以下載參考研究一下怎麼去連線DB，然後銜接第一次個人專題的那些方法 }.  
5.寫好抓json資料的方法，思考有沒有辦法批次新增經緯度進這些資料. 
6.if (無法批次新增）{ 尋找特定區域的活動做手動新增，demo時區域搜尋那附近的區 }. 

大家一起來練習用GitHub同步小組程式碼
步驟如下: 
  
1. 創GitHub帳號 & 下載GitHub桌面版  
2. 到主專案的GitHub頁面，右上角Fork點下去，新增主專案到自己的GitHub帳號  
2.1. 主專案是master分支，其他帳號fork之後也會自成一個分支，所以我們六個人共會有七個分支。後面講到的更新，指的是fork到自己帳號內的那份分支，而非master分支。
3. 打開GitHub桌面版，clone自己GitHub帳號的專案到本地電腦 (注意，這邊是clone自己的分支，非master分支，非常容易出錯要小心)  
4. 把自己打好的程式碼丟到Documents\GitHub (window預設路徑)  
5. 打開GitHub桌面版，它會自動偵測新增或修改的檔案，按下commit送出更新到GitHub本地資料庫  
6. GitHub本地資料庫已更新，但雲端還沒，這時候按下右邊的push，把本地資料庫檔案更新到雲端，更新後再打開自己的GitHub就會發現帳號內的專案已更新
  
---------平時大概最常用到的是第5第6步驟，這可以當作是一種個人雲端備份---------  
---------因為每個人都是push到自己fork的分支，檔案不會互相衝突---------  
  
7. 當組內要整合程式碼時，每個組員登入GitHub，選擇GitHub帳號內fork的那份專案，按下pull requests  
8. 管理員的master branch會收到很多pull requests，此時GitHub會自動比對更新檔案是否有蓋到舊的檔，如果有的話可以管理員可以審閱要留哪份，或是直接編輯衝突到的程式碼  
9. 程式碼整合完成後，組員要取得最新版的程式碼，務必做兩件事: 砍掉先前fork到自己GitHub帳號的專案 & 砍掉Documents\GitHub的專案  
10. 接著，同第2步和第3步，重新fork主專案到自己的GitHub帳號，並clone自己GitHub帳號的專案到本地電腦  
  
---------整合程式碼後專案名稱會加V2.0之類的後綴詞，預防和舊檔混淆---------  
