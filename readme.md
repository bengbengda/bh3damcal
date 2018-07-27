# 情报姬的第三个微信小程序
> powered by 情报姬微信小程序小组
readme果然还是得自己写一份🤣

## 使用说明
clone该项目到本地,完成任务后push上传就成 咱没那多规范 完成就行
代码规范   等同于前端的~因为小程序也是个h5嘛
## 有些方法要用到微信API
可以看下之前的蛋池小程序代码体会区别
比如 发起服务器请求
```wx.request(OBJECT)```
[微信API]https://developers.weixin.qq.com/miniprogram/dev/api/network-request.html#wxrequestobject
除此之外显示消息提示框什么的也要采用微信API 如果不会亦可从群文件里的UI库获取素材以及查看使用方法
请务必阅读API 还是有些地方和H5开发不一样的。
### 关于开发工具
为了调试方便请使用微信web开发者工具进行编写。在此之前请先注册微信个人开发者拿到appid 对project.config.json内appid里数值修改后即可进入项目进行开发
#### 代码规范

1. 代码缩进统一使用2个空格，[原因](https://github.com/o2team/guide/issues/3)。
