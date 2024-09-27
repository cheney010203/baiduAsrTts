
# 请耐心看完下面50行内容，帮你解决
-   1. demo不会使用
-  2. demo测试通过后集成出错
-  3. 出错后如何寻求帮助解决问题

**测试前需要在AuthUtil中填入自己的鉴权信息(appId、apiKey、secretKey)**

**上线产品鉴权信息保存参考AuthUtil说明**

>!!! 点击开始录音按钮前，请先看界面上的说明文字 !!!
# 1 帮助文档

使用Android Studio 最新版本，FILE->OPEN 选本目录 即可打开项目， 提示升级gradle，请不要升级，选择“Don't remind me again for this project”。

[SDK帮助文档](http://ai.baidu.com/docs#/ASR-Android-SDK/top)

请测通DEMO后，了解SDK的调用流程后集成。

[集成文档](http://ai.baidu.com/docs#/ASR-Android-SDK/top#集成指南部分)

图文集成教程及demo代码说明： demo的doc_integration_DOCUMENT目录


# 2 库文件路径：
> jar ：core/libs 目录下

> so：core/src/main/jniLibs 目录

# 3 报错排查流程：
- 1 测试demo有无问题，如demo一运行就有问题，请立即反馈

- 2 如demo运行无问题，请查看集成文档及图文集成教程，对比d-emo集成。
- 3 按照集成文档集成后依旧有问题，集成下demo中的AutoCheck类
- 4 如果依旧有问题，新建一个helloworld集成sdk，实践排查集成步骤。

> 文档和demo都未提及的功能，如纯离线，商务合作及新功能需求  在ai.baidu.com 右侧点击“商务合作”


# 4 问题反馈：
## 4.1反馈途径
- 1. QQ群： 在ai.baidu.com 底部可以找到QQ群号
- 2. [论坛](https://ai.baidu.com/forum/topic/list/166)
- 3. 工单： 您新建应用的网站里发送工单
- 4. 商务合作及新功能，需在ai.baidu.com 右侧点击“商务合作


## 4.2 BUG反馈格式：

- 1. 现象描述
   调用我们的xxx方法之后，报错。
- 2. 输入参数：
  （DEMO中含有“反馈”两个字的日志）
- 3. 输出结果：

- 4 .用户日志：
  先清空日志，之后调用我们的某个方法结束。请提供给我们之中的完整日志。

- 5 .手机信息：
   手机型号， android版本号等信息

# 5 DEMO 改进建议及文档建议：

1. QQ群： ai.baidu.com 底部可以找到QQ群号。 在QQ群中@测试。
2. aip-bot.baidu.com 使用关键字查询
