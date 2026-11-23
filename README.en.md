# ChatGPT Web Study Copy

[简体中文](README.md) · English

A 2023 study copy of [Chanzhaoyu/chatgpt-web](https://github.com/Chanzhaoyu/chatgpt-web) for exploring how a Vue chat UI stores sessions, renders messages and talks to a separate Node.js service. This copy changes the default avatar, the About panel and frontend and backend package configuration.

![Chat interface screenshot](docs/c1.png)

## Where to start

| Source | What to look for |
| --- | --- |
| [Chat UI](src/views/chat/) | Vue 3 chat page, message components and the session sidebar |
| [Frontend state](src/store/) | Pinia state for chat history and interface settings |
| [Backend](service/src/) | Express routes, middleware and the model request wrapper |
| [Changes in this copy](https://github.com/VINDA-98/chatgpt-web-study/compare/76cef65...9891d62) | Comparison with the upstream commit retained in this repository |

See the [historical documentation](https://github.com/VINDA-98/chatgpt-web-study/blob/9891d6245cc9f63fd27e320e344ac9240f2b5d9c/README.en.md) for the original environment, build and Docker instructions. Those instructions describe older dependencies and service APIs. Compatibility with current services has yet to be verified.

## Credits and license

The original project was developed by ChenZhaoYu and upstream contributors. This copy retains the upstream [MIT license](license). The screenshot is from the original project.
