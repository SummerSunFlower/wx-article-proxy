# WX Article Proxy

通过 Vercel Edge Function 代理访问微信公众号文章，避免服务器IP被微信验证码拦截。

## 部署

点击下方按钮一键部署到你的 Vercel 账号：

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/SummerSunflower/wx-article-proxy)

## 使用

部署后，访问：
```
https://你的域名.vercel.app/api/proxy?url=https://mp.weixin.qq.com/s/xxxxx
```

返回的就是微信公众号文章的完整 HTML。
