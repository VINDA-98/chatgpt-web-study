# ChatGPT Web 学习版

简体中文 · [English](README.en.md)

2023 年基于 [Chanzhaoyu/chatgpt-web](https://github.com/Chanzhaoyu/chatgpt-web) 整理的学习副本。代码可用于追踪从 Vue 会话存储、消息渲染到 Node.js 服务的请求链路。这个版本调整了默认头像、关于页和前后端的包配置。

![聊天界面截图](docs/c1.png)

## 从哪里看代码

| 位置 | 内容 |
| --- | --- |
| [聊天界面](src/views/chat/) | Vue 3 聊天页面、消息组件和会话侧栏 |
| [前端状态](src/store/) | Pinia 状态、聊天记录和界面设置 |
| [服务端](service/src/) | 基于 Express 的路由、中间件和模型请求封装 |
| [本仓库的改动](https://github.com/VINDA-98/chatgpt-web-study/compare/76cef65...9891d62) | 与保留的上游提交对比，便于核对修改范围 |

当时的环境、构建和 Docker 说明见[历史文档](https://github.com/VINDA-98/chatgpt-web-study/blob/9891d6245cc9f63fd27e320e344ac9240f2b5d9c/README.md)。这些说明对应旧版依赖和服务接口，当前运行情况待验证。

## 署名与许可

原项目由 ChenZhaoYu 和上游贡献者开发。沿用上游的 [MIT 许可](license)，截图也来自原项目。
