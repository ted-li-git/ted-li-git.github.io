# 接上一篇关于deepseek的文章
在上一篇关于deepseek的文章里提到过本地部署，但有些人的电脑性能不行（就比如我，连个独立显卡都没有）本地部署的是蒸馏版，但蒸馏版，可想而知，是没有满血版好的。所以今天LJT就带你使用硅基流动和cherry studio实现deepseek-r1满血版+个人知识库。
# 准备工作
一台电脑（性能不是特别差就行，可以上网），一双手。
# cherry studio
官网：https://cherry-ai.com
安装完后打开就是这个样子
![Image](https://github.com/user-attachments/assets/cedc9f43-b743-4a34-9873-506ea7ac2c5f)
# 硅基流动
官网：https://cloud.siliconflow.cn/models
# 具体步骤-聊天
登录/注册后找到左下角的API密钥
![Image](https://github.com/user-attachments/assets/3e550e12-9e13-4e93-ae5f-42f7397e36b3)
创建一个API密钥，然后复制
打开cherry studio
![Image](https://github.com/user-attachments/assets/df4666c8-f19f-4f1f-b951-79763d154038)
输入API密钥
到主页默认助手，选择模型，这里deepseek可以选择deepseek-r1，deepseek-v3，我们一般选r1，然后就可以开始聊天了
# 搭建个人知识库
![Image](https://github.com/user-attachments/assets/c7efc17a-6a4b-43cc-b64f-931d395459db)
选择
![Image](https://github.com/user-attachments/assets/2285035a-a507-4bfb-bf2e-964958b07521)
这个图标，点击就来到了知识库界面，创建完知识库就可以上传文件了（注：如果不是单纯的文档，比如python文件就需要转成文档，比如word文档）
如果在问deepseek问题时要调用知识库文件，就点击文本框下面的这个图标
![Image](https://github.com/user-attachments/assets/6d3ec67c-0017-43a7-9314-2cbeb5bba0e8)
# 结语
非常好用（硅基流动是有token限制的哦！）