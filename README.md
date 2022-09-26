# 自动领取支付宝红包（ios）搭建教程
1.下载Alipay.html 

2.用支付宝扫一扫下面二维码获取你自己的shareId

![share.png](https://vip2.loli.io/2022/09/26/LtVNHdh5A16aFOu.png)

3.token 需要在支付宝赚钱红包页面点击分享，然后分享至钉钉，这个时候，二维码就会被保存，然后用微信扫码，
出来就是一个token，将这个token的 19 开头前面的删除，剩下的就是我们需要的token。

![需要在支付宝赚钱红包页面点击分享.png](https://vip2.loli.io/2022/09/26/H1PUsYuizWpF6Jg.png)

4.修改源代码中的shareId和token 如图灰色选中部分
 
 ![需要在支付宝赚钱红包页面点击分享3.png](https://vip2.loli.io/2022/09/26/Vt95PQgsEyWpxLH.png)

5.将修改好后的源码保存为html格式再上传到你网站服务器或腾讯云cos对象存储中即可

![需要在支付宝赚钱红包页面点击分享2.png](https://vip2.loli.io/2022/09/26/KjX2dIHDkrOBgFN.png)

微信扫一扫查看示例：

![扫描领红包.png](https://vip2.loli.io/2022/09/26/ybmzdwR9G5Ma4Xx.png)
