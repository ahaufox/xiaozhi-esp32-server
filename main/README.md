本文档是开发类文档，如需部署小智服务端，[点击这里查看部署教程](../README.md#%E4%BD%BF%E7%94%A8%E6%96%B9%E5%BC%8F-)

# 项目目录介绍
当你看到这份文件的时候，这个这个项目还没完善好。我们还有很多东西要做。

如果你会开发，我们非常欢迎您的加入。

```
xiaozhi-esp32-server
  ├─ xiaozhi-server 8000 端口 Python语言开发 负责与esp32通信
  ├─ manager-web 8001 端口 Node.js+Vue开发 负责提供控制台的web界面
  ├─ manager-api 8002 端口 Java语言开发 负责提供控制台的api
```

# xiaozhi-server 接口协议

[虾哥团队通信协议：Websocket 连接](https://ccnphfhqs21z.feishu.cn/wiki/M0XiwldO9iJwHikpXD5cEx71nKh)

# manager-web 、manager-api接口协议

[manager前后端接口协议](https://app.apifox.com/invite/project?token=H_8qhgfjUeaAL0wybghgU)

[前端页面设计图](https://codesign.qq.com/app/s/526108506410828)
3d6bd0e23e0c8fa6a1c09c4feea57711769f1183
8064e84276d809b3a27197d599052e154fdfc277
f8ece2d984307d14620c48b1a4c30c70db702135
2b662d3a14d8eb35777887fdcb7581e509d7ade9
4f3fae81c19730b71c4db02d2685c04c7f1564c6
7b266ad7c071747830a6d028fb4601e6932d9d30
f9472627f471b64da136bdf57377c4bfe74b39c6
16601a67e334f8e183c39be73dd44cef93e9aaf2
69735207e605046478cc494c7954b5ab41a42f5a
git cherry-pick 69735207e605046478cc494c7954b5ab41a42f5a


 git checkout upstream/main -- config.yaml
git remote add upstream https://github.com/ahaufox/xiaozhi-esp32-server.git