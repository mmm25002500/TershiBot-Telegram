# TershiBot - Telegram
A telegram bot which made by Tershi. 一個由夏特稀製作的Telegram機器人
這是一款使用Python寫的Telegram Bot，這是利用Telepot做成的，目前也正在維護中，也有在定時更新。<br>
目前功能:<br>
用法： /指令 [選項...] [參數...]
/help 顯示幫助
/showmeme 顯示迷因梗圖
/member 顯示群組人數
/admim 顯示管理員
/callme 呼叫夏特稀
/sayhello 說哈摟
/showweb 顯示官網
/count 倒數計時
/wearechina 我們是中國
/sendmsg 次數 訊息 [選項] 傳送訊息 --help可以查看幫助
/calc 數字x 數字y [選項] 計算機 --help可以查看幫助
/time 時間
/ytdl  YouTube影片下載器

## Installation 安裝
### Arch-Linux
Update And Install PKG:``sudo pacman -Syy python3 python3-pip httpd`` <br>
Install Module required:``pip3 install telepot``<br>
Start Apache Service:``sudo systemctl start httpd``<br>
Create A Necessary Folder:``mkdir /srv/http/yt``<br>
Change Owner:``sudo chown USER:USER /srv/http/yt``<br>
### Debian/Ubuntu(Not Ready)
Update And Upgrade:``sudo apt update&&sudo apt upgrade -y``<br>
Install PKG:``sudo apt install httpd python3 python3-pip``<br>
Install Module required:``pip3 install telepot``<br>
Create A Necessary Folder:``sudo mkdir /var/www/html/yt``<br>
Change Owner:``sudo chown USER:USER /var/www/html/yt``<br>
Start Apache Service:``sudo service httpd start``<br>
### Termux(For Android)(Not Ready)
Update And Upgrade:``pkg update&&pkg upgrade``<br>
Install PKG:``pkg install httpd python3 python3-pip``<br>
Install Module required:``pip3 install telepot``<br>
Create A Necessary Folder:``mkdir /var/www/html/yt``<br>
Start Apache Service:``apachectl``<br>
### Run 運行
Clone The Repo:``git clone https://github.com/mmm25002500/TershiBot-Telegram``<br>
Mkdir Necessary Folder:``mkdir TershiBot-Telegram/yt``<br>
Change Local Variables Settings:``vim TershiBot-Telegram/bot.py``<br>
Run as python3:``python3 TershiBot-Telegram/bot.py``<br>

## 心得與建構思路:
這是我在課餘的時候，寫出來的Telegram機器人，這個機器人是我慢慢翻API寫出來的，以後也會有更多功能。
在這個程式中我學到物件導向的應用，也學習到「監聽」語法。

## 關於我們 About Us

[Team Website](www.tershi.ml) <br>
[Team Facebook](https://www.facebook.com/shanling.team/) <br>
[XiaTerShi YouTube](https://www.youtube.com/channel/UCPdpFDFOp3sPbZhRkaQVaQA) <br>
[XiaTerShi FaceBook](https://www.facebook.com/Tershi25648) <br>
[Tershi MailServer](https://mail.tershi.ml) <br>
[Tershi Official WebSite](https://cutespirit.tershi.ml) <br>
[Tershi Gitbook](https://gitbook.tershi.ml) <br>
[Tershi Telegram](https://t.me/TershiXia) <br>
以上關於因為域名為免費域 因此隨時會網域更換！ <br>
Licence:© Tershi 2020 All right reversed 此程式除了「關於」頁面不可重製及發布之外，其餘頁面及功能可進行重製發布。
