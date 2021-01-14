# 易语言SDK

需要配合[gmc](https://github.com/ProtobufBot/Go-Mirai-Client/releases)或[smc](https://github.com/ProtobufBot/spring-Mirai-Client/releases)使用，gmc基于miraigo，smc基于mirai。gmc不需要环境，smc需要jdk。

使用方法：打开gmc或smc，浏览器打开 http://localhost:9000 输入账号密码登陆，在下方处理完验证码后，打开易语言SDK，直接运行。

验证码处理：
- 如果是滑块验证码，请阅读[这个](https://github.com/ProtobufBot/Go-Mirai-Client)。
- 如果是设备锁扫码验证码，在扫码之后也需要提交任意文。
- 图形和短信验证码直接提交 看到/收到 的内容。

编写代码：修改 机器人处理程序集 中的代码。
