# 微信小程序 黑大新生小程序 后端爬虫


>原本涉及登录获取用户成绩，课程表的部分，但是现在学校设置vpn，第三方登录爬虫无法实现，需要学校提供第三方接口。先记录一下这块代码吧。

## Django+requests
不得不说微信小程序真的限制太多，如果用wx.request()网站必须是https，而我们学校依旧是http，我的服务器也懒得部署，用的微信小程序云开发作为中间那环，还学了点nodejs的request那部分（都是泪），微信小程序不可以扫二维码，不可以跳转网页,也不会存储cookie....（摔！）

