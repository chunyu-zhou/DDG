## Mysql数据库表结构字典生成器

- .数据库设计的表或字段注释说明需严格按照“字段名称(注释说明)”格式，如“用户昵称(微信用户昵称)”；这里使用的是“()”而不是“（）”。
- .填写的数据库用户需拥有information_schema数据库读的权限。
- .请填写你的数据库配置信息开始生成字典吧！

## 截图
![Alt text](/public/images/1.png)
![Alt text](/public/images/2.png)

##注意
> - 项目如果部署在Linux服务器，可能会出现使用IP地址数据库时出现连接失败，请禁用
SELinux:
```shell
    /usr/sbin/setenforce 0 立刻关闭 SELINUX
    /usr/sbin/setenforce 1 立刻启用 SELINUX
```

