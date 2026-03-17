https://open.feishu.cn

# 1.注册飞书开发平台

# 2.创建企业自建应用

https://open.feishu.cn/app?lang=zh-CN

![image-20260316173916049](./i/image-20260316173916049.png)

![image-20260316174006938](./i/image-20260316174006938.png)



# 3.添加能力：机器人

##### https://open.feishu.cn/app/cli_a93d73e0e338dbca/capability/

![image-20260316174054108](./i/image-20260316174054108.png)

# 4.打开openclaw飞书的配置网址：

https://docs.openclaw.ai/zh-CN/channels/feishu

复制里面的json：

![image-20260316180502205](./i/image-20260316180502205.png)



# 5.飞书 权限管理 批量导入/导入权限-粘贴openclaw里面的json，申请开通

![image-20260316180541589](./i/image-20260316180541589.png)

![image-20260316180646217](./i/image-20260316180646217.png)

![image-20260316180706396](./i/image-20260316180706396.png)

# 4.事件与回调

5.订阅方式->

![image-20260316174706176](./i/image-20260316174706176.png)

凭证与基础信息->里面复制 app secret 和 app id



# openclaw config里面

找到channel ->飞书

粘贴App Secret

![image-20260316181125074](./i/image-20260316181125074.png)

![image-20260316181316956](./i/image-20260316181316956.png)

Open claw.json文件里也能配置：

![image-20260316184422774](./i/image-20260316184422774.png)

### Allowlist（推荐） 指定群才工作

### Open 所有群都可以用机器人但必须 @机器人

### Disabled

# 这里选open，后面选飞书

![image-20260316181610693](./i/image-20260316181610693.png)

◆  Feishu connection mode
│  ● WebSocket (default)
│  ○ Webhook

◆  Which Feishu domain?
│  ● Feishu (feishu.cn) - China
│  ○ Lark (larksuite.com) - International

![image-20260316182039018](./i/image-20260316182039018.png)





输入命令查看是否安装成功，不成功可能是安装文件夹权限问题，查找ai帮你修改权限命令：

# openclaw channels list

查看是否feishu被安装成功



事件与回调 ->订阅方式->长连接 

这里需要先在openclaw config里安装好feishu，并且启动网关openclaw gateway

openclaw gateway启动网关，然后飞书平台 

![image-20260316184117136](./i/image-20260316184117136.png)



# openclaw文档中查找 “添加事件”

![image-20260316184806046](./i/image-20260316184806046.png)

![image-20260316184727334](./i/image-20260316184727334.png)



# 创建版本

![image-20260316185117334](./i/image-20260316185117334.png)

![image-20260316185218835](./i/image-20260316185218835.png)



# 设置配对：

在飞书里面输入你好，他会回复一大堆，复制最下面的命令，在电脑端输入配对

```
openclaw pairing approve feishu RSG5H4BN

```

