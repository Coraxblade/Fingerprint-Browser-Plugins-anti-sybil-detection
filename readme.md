# **Shadow Mask** #
**Fingerprint browser plugin** 

----------

Makes your Chrome become a Fingerprint Browser

Random fingerprint | Automatically bind proxy | Separate Cookies and Cache

Anti sybil detection


## How to use: ##

1.Download all files(include folders)

2.Prepare your own proxies

3.Fill proxies in the config.ini file according to the format

(IP proxies need username and password)

example:

    [IP Proxy]
    Proxy1 = 42.xx.xx.xx:5560:username:password

    [Http Proxy]
    proxy1 = https://xxx.xx.xx.xx:4433


4.You can add more useragent by yourself

example:

    [useragent]
    angent1 = Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/68.0.3440.106 Safari/537.36
    angent2 = Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/67.0.3396.99 Safari/537.36

5.running the shadow mask.exe

- choice the mode(IP proxy or HTTP proxy,Choose according to your agent type)
- the program will check the number of the proxies and return how many browser windows you can lanuch.
- you need input the start and end number of the browser.
> for example:
> start browser No.3,the start number is 3  and end number is 3 too.
> start browser No.1 to No.10. the start number is 1  and end number is 10.ten browser will launched one by one


6.When the Browsers are running,don`t shutdown the program.


7.when you finish your job and want to launch new browser,press enter to continue.



Requirements:
Windows 10
Chrome with ChromeDriver
> Program will auto check and update the ChromeDriver version，Manual download is required if automatic update fails


Support:
CoraxBlade@outlook.com





# **Shadow Mask** #
**指紋瀏覽器工具** 

----------

將Chrome變成指紋瀏覽器

隨機指紋|自動綁定代理|Cookies和緩存隔離|反女巫檢測


## 使用方法: ##

1.下載全部文件(包括文件夾及文件)

2.準備好你的代理IP

3.將代理填寫到config.ini文件中，請注意格式
Fill proxies in the config.ini file according to the format

(IP 代理需要同時填入用戶名與密碼)

舉例:

    [IP Proxy]
    Proxy1 = 42.xx.xx.xx:5560:username:password

    [Http Proxy]
    proxy1 = https://xxx.xx.xx.xx:4433


4.你也可以增加自己的useragent，已達到更佳防指紋效果

舉例:

    [useragent]
    angent1 = Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/68.0.3440.106 Safari/537.36
    angent2 = Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/67.0.3396.99 Safari/537.36

5.運行shadow mask.exe

- 選擇模式(IP proxy 或 HTTP proxy模式,根據你填寫的代理種類進行選擇)
- 程式會自動檢測你填寫的代理並返回共有多少個瀏覽器視窗可以被啟動
- 填寫需要啟動的瀏覽器的初始及結束編號
> 舉例:
> 需要啟動3號瀏覽器,初始編號輸入 3  結束編號也輸入 3.
> 需要啟動1號到10號瀏覽器，初始編號輸入 1 結束編號輸入10，10個瀏覽器會依次序啟動


6.當瀏覽器視窗運行時，請不要關閉程式


7.當你結束了在當前瀏覽器的工作並且需要啟動新的瀏覽器，只需要輸入enter即可繼續作業



程式需求：
Windows 10 及以上作業系統
Chrome with ChromeDriver
> 程式會自動檢測ChromeDriver的版本並且進行更新，如果自動更新失敗，則需要手動下載


支援:
CoraxBlade@outlook.com
