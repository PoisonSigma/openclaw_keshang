

![image-20260311182132201](./i/image-20260311182132201.png)

模型选择

![image-20260311182203669](./i/image-20260311182203669.png)

![image-20260311184217001](./i/image-20260311184217001.png)

![image-20260311184411439](./i/image-20260311184411439.png)

![image-20260311184559963](./i/image-20260311184559963.png)

- API key **不绑定模型**
- 一个 key **可以调用所有 GLM 模型**

https://bigmodel.cn/finance-center/resource-package/package-mgmt

![image-20260311184946958](./i/image-20260311184946958.png)

![image-20260311185021009](./i/image-20260311185021009.png)



# 配置openclaw

```
openclaw config
```

如果之前配置过，提示配置过：

![image-20260312163659673](./i/image-20260312163659673.png)

这里会显示配置文件的位置：





减少tokens的限制配置：

默认：很大，手动修改成小的1024



# Mac端的默认openclaw目录： 

```
~/.openclaw/
```

# windows的默认openclaw目录

```
C:\Users\你的用户名\.openclaw\workspace
```

# Windows 进入openclaw目录

## CMD

```
cd %USERPROFILE%\.openclaw
```

## PowerShell：

```
cd $env:USERPROFILE\.openclaw
```

# 如果找不到这些目录执行命令

```
openclaw setup
```

![image-20260312171102876](./i/image-20260312171102876.png)



找到子目录里面的.json文件可以配置

![image-20260311190147105](./i/image-20260311190147105.png)

![image-20260311190305540](./i/image-20260311190305540.png)



![image-20260311190607232](./i/image-20260311190607232.png)

![image-20260311190719762](./i/image-20260311190719762.png)

![image-20260311190759007](./i/image-20260311190759007.png)



权限错误：

使用sudo重新设置，需要输入开机密码：

```
sudo openclaw configure
```

![image-20260311191022647](./i/image-20260311191022647.png)

命令行执行：

```
openclaw
```

代表安装成功