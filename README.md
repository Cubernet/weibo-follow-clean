weibo-follow-clean
===
## 简单粗暴的微博粉丝清理

> python3 weibo.py

因为登录需要验证码 + 个人能力问题没有集成登录功能，需要手动填写cookie
  ←  于是反正执行的时候会提示填写的

![](https://github.com/TimeCompass/weibo-follow-clean/blob/master/img/cookie.png)
SUB="你需要复制的内容";
在 = 和 ; 之间

同样的理由需要填写用户的数字ID
  ←  于是反正执行的时候会提示填写的

![](https://github.com/TimeCompass/weibo-follow-clean/blob/master/img/id.png)
没错就是那串数字

  ←  所以反正你直接在脚本里改掉注释掉提示也一样

默认只分析最后（页面显示是最前）的十页粉丝，这是一个MAGIC NUMBER，不要问我为什么。

P.S. 谁写个js油猴脚本吼不吼啊，求造福大众。