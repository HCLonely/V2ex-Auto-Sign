<p align="center">
    <a href="https://github.com/Wenmoux"><img alt="Author" src="https://img.shields.io/badge/author-Wenmoux-blueviolet"/></a>
    <img alt="PHP" src="https://img.shields.io/badge/code-javascript-success"/>
    <img src="https://github-visitor-badge.glitch.me/badge?page_id=Wenmoux.V2ex-Auto-Sign"/>
</p>

# <font color="red">遇到签到失败就去v2ex退出账号并重新登陆再抓取ck,并更新cookie！！！</font>


# 说在前边
 > [Github Actions入门教程](http://www.ruanyifeng.com/blog/2019/09/getting-started-with-github-actions.html)

 > [代码仓库](https://github.com/Wenmoux/V2ex-Auto-Sign)
<!--more-->

# 操作步骤
## Step 1 Fork仓库
打开[代码链接](https://github.com/Wenmoux/V2ex-Auto-Sign)并Fork我的仓库
![fork源代码](https://cdn.jsdelivr.net/gh/Wenmoux/wenpic/IMG_20200608_085223.jpg)
##  Step 2 设置Cookie
fork完之后,如图点击<font color="red">Settings</font>
![](https://cdn.jsdelivr.net/gh/Wenmoux/wenpic/IMG_20200608_085340.jpg)

进去之后依次点击<font color="red">Secrets----new secret</font>
点击之后
Name输入V2EXCK value输入你的v2ex cookie
完成后点击add secret 
同理再添加一个qmagapi [获取地址](https://qmsg.zendee.cn)以及sckey(server酱)
Name 是QMSGAPI value是你的api
如果想使用TGbot推送(by @Windyskr )，请添加TGAPI 需要从 @botfather 获取token，和@WooMaiBot 发送/id 获取自己id 通过拼接获取API 举例如下 https://api.telegram.org/bot123456:ABCDEFG（替换为你的token）/sendMessage?chat_id=123456（替换为你的id） 把上面这段全部填入即可
![](https://cdn.jsdelivr.net/gh/Wenmoux/wenpic/IMG_20200629_092046.jpg)
![](https://cdn.jsdelivr.net/gh/Wenmoux/wenpic/IMG_20200629_092209.jpg)
## Step 3 启用Actions
点击Action，再点击**I understand my workflows, go ahead and enable them**  
![](https://cdn.jsdelivr.net/gh/Wenmoux/wenpic/687474703a2f2f74752e79616f68756f2e6d652f696d67732f323032302f30362f333463613136306339373262393932372e706e67.png)
## Step 4 运行结果 
点击Actions-v2ex-auto-sign-build查看
![](https://cdn.jsdelivr.net/gh/Wenmoux/wenpic/7c27953002262d15.png)
![](https://cdn.jsdelivr.net/gh/Wenmoux/wenpic/IMG_20200608_091224.jpg)
![](https://cdn.jsdelivr.net/gh/Wenmoux/wenpic/april_2020-06-29-09-17-02-621.jpg)
## 其它说明
 - 设置好之后要点击Actions启用下
 - 可以自己改定时时间
 - 还没想到 
