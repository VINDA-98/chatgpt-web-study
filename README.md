# ChatGPT Web 学习版

简体中文 · [English](README.en.md)

这是基于 [Chanzhaoyu/chatgpt-web](https://github.com/Chanzhaoyu/chatgpt-web) 的 2023 年学习副本，用来了解 Vue 聊天界面怎样保存会话、渲染消息，以及怎样与独立的 Node.js 服务通信。这个仓库主要调整了默认头像、关于页，以及前后端的包配置。

![聊天界面截图](docs/c1.png)

## 从哪里看代码

| 位置 | 内容 |
| --- | --- |
| [聊天界面](src/views/chat/) | Vue 3 聊天页面、消息组件和会话侧栏 |
| [前端状态](src/store/) | Pinia 状态、聊天记录和界面设置 |
| [服务端](service/src/) | 基于 Express 的路由、中间件和模型请求封装 |
| [本仓库的改动](https://github.com/VINDA-98/chatgpt-test/compare/76cef65...9891d62) | 与保留的上游提交对比，便于核对修改范围 |

当时的环境、构建和 Docker 说明见[历史文档](https://github.com/VINDA-98/chatgpt-test/blob/9891d6245cc9f63fd27e320e344ac9240f2b5d9c/README.md)。这些说明对应旧版依赖和服务接口，当前运行情况待验证。

## 署名与许可

原项目由 ChenZhaoYu 和上游贡献者开发。沿用上游的 [MIT 许可](license)，截图也来自原项目。
