# ExchangeRelayY

这是[ExchangeRelayX](https://github.com/quickbreach/ExchangeRelayX)的一个Patch版本
做了以下的patch：
 - 中文内容无法显示的问题
 - 部分JS缺失问题
 - 查看邮件页面，邮件列表滚动条失效问题
 - 邮件只显示250封的问题
 - 不支持SMBV2.0的问题


## 1.安装
```
pip install -r requirements.txt
```



## 2.使用

```
python exchangeRelayx.py -t http://your-taraget-owa -l 0.0.0.0 -p 8001
```



## 3.认证配置

vim lib/owaServer.py

找到runServer函数，配置user字典。

默认账密是：admin/admin123