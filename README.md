# Android Https Test App

本仓库包含一个app:com.example.httpstest, 该app用作https证书校验和证书绑定的验证, 以及对其进行hook解除证书验证和证书绑定的demo

参考文章: [Android HTTPS认证的N种方式和对抗方法总结](https://ch3nye.top/Android-HTTPS%E8%AE%A4%E8%AF%81%E7%9A%84N%E7%A7%8D%E6%96%B9%E5%BC%8F%E5%92%8C%E5%AF%B9%E6%8A%97%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93/)

## 目录结构

- certs 存储证书 域名www.test.com

- https_server.py 启动用于双向认证的https服务器

- 其他目录即 Android APP 开发源码目录




## Ref
- https://ch3nye.top/Android-HTTPS%E8%AE%A4%E8%AF%81%E7%9A%84N%E7%A7%8D%E6%96%B9%E5%BC%8F%E5%92%8C%E5%AF%B9%E6%8A%97%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93/#0x4-ssl-pinning%E4%BB%A3%E7%A0%81%E6%A0%A1%E9%AA%8C
- https://shunix.com/ssl-pinning/
- https://www.cnblogs.com/mqinglang/p/17076516.html
- https://blog.csdn.net/solinger/article/details/105511007
- https://blog.csdn.net/char_star/article/details/106082491
- https://www.lightky.com/backend/2016/09/rsa-pem-format.html
- https://juejin.cn/post/6847902219745181709
