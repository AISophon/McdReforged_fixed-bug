# McdReforged
与 [BotServer](https://github.com/Minecraft-QQBot/BotServer) 进行对接的 Mcdr 插件。

你可以到 [Releases](https://github.com/Minecraft-QQBot/McdReforged/releases) 下载最新版本 Mcdr 服务器插件。

## 功能

* 可以使用 !!qq 发送 QQ 群消息。

## 安装插件

将下载好的 `QQBot.mcdr` 文拷贝到 MCDR 的 插件文件夹 下，编辑 配置文件夹 `qq_bot` 下的 `config.json` 文件。配置文件内容参考如下：

```json
{
  "name": "服务器名称",
  "port": 8000,
  "token": "令牌"
}
```

其中各个字段的含义如下：

|      字段名       |  类型  |                       含义                       |
| :---------------: | :----: | :----------------------------------------------: |
|       port        |  整数  | 端口号，和服务器配置文件下的 PORT 保持一致即可。 |
|       name        | 字符串 |             服务器名称，中英文都可。             |
|       token       | 字符串 | 口令，和服务器配置文件下的 TOKEN 保持一致即可。  |

当你看到类似 `发送服务器启动消息成功！` 的 Mcdr 日志时，你的 Mcdr 服务器已经成功连接到机器人服务器。若出现错误提示，请确保你的机器人服务器已经开启，或者配置文件的 Port 是否正确。你可以通过 `server` 指令查看服务器是否连接上机器人。

> [!TIP]
> 若插件遇到问题，或有更好的想法，可以加入 QQ 群 [`962802248`](https://qm.qq.com/q/B3kmvJl2xO) 或者提交 Issues 向作者反馈。若你有能力，欢迎为本项目提供代码贡献！
