# DSH Plugins

我的 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)（DSH）插件统一索引。

## 插件列表

| 插件 | 版本 | 分类 | 说明 | 社区收录 |
|---|---|---|---|---|
| [dsh-localsend](https://github.com/huangfuren/dsh-localsend) | 0.2.0 | 工具与能力 | 局域网文件/文件夹传输；可生成临时 HTTP 下载链接，接收方无需安装软件 | [PR #4676](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/4676) 审核中 |
| [dsh-outline-auto](https://github.com/huangfuren/dsh-outline-auto) | 0.5.0 | 文档与知识库 | 对话中搜索、读取并安全读写 Outline 知识库，写操作受白名单保护，可存本地 Markdown | 已收录 |
| [dsh-bg-plugin](https://github.com/huangfuren/dsh-bg-plugin) | 1.0.0 | 主题与外观 | 全窗口背景图，含总开关、参数调节与主题 token 覆盖 | 已补 `dsh.bundle` manifest |
| [dsh-client-ui-balance](https://github.com/huangfuren/dsh-client-ui-balance) | 0.1.0-rc.5 | 用量与计费 | 会话头部实时余额胶囊，轮询 `llm.balance`，可展开详情面板 | 未提交（已补 `dsh.bundle`，待过 1 天门槛） |
| [dsh-bg2](https://github.com/huangfuren/dsh-bg2) | 2.0.0 | 主题与外观 | 全窗口背景宿主端 v2：`$DSH_HOME/background` 持久存储、上传/文件/RPC 路由、配置持久化与旧版迁移 | 待补 `dsh.bundle` manifest |
| [dsh-client-hqst](https://github.com/huangfuren/dsh-client-hqst) | 1.0.0 | 工具与能力 | 会话历史提问侧栏：点击任意提问跳转并短暂高亮 | 待提交 |
| [dsh-client-ui-aqua](https://github.com/WYH66666666/DSH-Transparent-UI-Plugin) | 1.3.0 | 主题与外观 | 高自由度玻璃主题：模糊、磨砂、流体/壁纸背景、统一圆角与动效 | 待提交 |

## 安装

```sh
dsh plugin --profile web add huangfuren/dsh-localsend
```

## 机器可读清单

见 [plugins.json](./plugins.json)。

## 社区收录

插件提交至 [awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) 社区列表，收录后可在 dsh-market 中搜到。
