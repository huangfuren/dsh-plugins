# DSH Plugins

我的 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)（DSH）插件统一索引。

## 插件列表

| 插件 | 版本 | 分类 | 说明 | 社区收录 |
|---|---|---|---|---|
| [dsh-localsend](https://github.com/huangfuren/dsh-localsend) | 0.4.0 | 工具与能力 | 局域网文件/文件夹传输；可生成临时 HTTP 下载链接，接收方无需安装软件；新增 SMB 推送，直接写入目标机共享目录 | 已收录（[PR #4676](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/4676)，2026-09-11 合并） |
| [dsh-outline](https://github.com/huangfuren/dsh-outline) | 0.8.0 | 文档与知识库 | 对话中搜索、读取并安全读写 Outline 知识库，写操作受白名单保护，可存本地 Markdown（原名 dsh-outline-auto） | 已收录 |
| dsh-sync | 0.2.1 | 工具与能力 | 整机搬家：导出 settings / 凭据（可选 AES-256-GCM 加密）/ 全部 profile 声明文件 / 所有 `link:` 插件源码为可移植 bundle。新机无需先装 dsh-sync、也无需相同路径——包内自带 `apply.ps1` / `apply.sh` / 一键向导与零依赖小工具：sha256 校验、预演、覆盖前备份、失败自动回滚；源机严格只读 | 未提交（尚未建 GitHub 仓库，本地 0.2.1） |
| [dsh-bg-plugin](https://github.com/huangfuren/dsh-bg-plugin) | 1.0.0 | 主题与外观 | 全窗口背景图，含总开关与透明度/亮度/遮罩/模糊/位置/填充调节；含 `dsh-bg`（宿主端）与 `dsh-client-bg`（客户端）两个包 | 未提交（已取代 dsh-bg2，后者 2026-09-17 移除） |
| [dsh-client-ui-balance](https://github.com/huangfuren/dsh-client-ui-balance) | 0.3.0 | 用量与计费 | 会话头部实时余额胶囊，轮询 `llm.balance`，可展开详情面板 | 未提交 |
| [dsh-conversation](https://github.com/huangfuren/dsh-conversation) | 1.1.0 | 工具与能力 | 会话大纲面板：历史提问（带序号与时间）+ 助手回复的 Markdown 标题树，含层级滑块、搜索、收藏、复制、点击定位与阅读位置跟随（已并合 dsh-outline；原名 dsh-client-hqst） | 未提交 |
| [dsh-client-ui-aqua](https://github.com/WYH66666666/DSH-Transparent-UI-Plugin) | 1.0.8 | 主题与外观 | 高自由度玻璃主题：模糊、磨砂、流体/壁纸背景、统一圆角与动效（第三方插件） | 未提交（第三方，本地镜像） |

## 安装

```sh
dsh plugin --profile web add huangfuren/dsh-localsend
dsh plugin --profile web add huangfuren/dsh-outline
dsh plugin --profile web add huangfuren/dsh-conversation
dsh plugin --profile web add huangfuren/dsh-bg-plugin
dsh plugin --profile web add huangfuren/dsh-client-ui-balance
```

`dsh-sync` 尚未发布到 GitHub，只能在本机以 `link:` 方式装在 profile 里。

## 机器可读清单

见 [plugins.json](./plugins.json)。

## 社区收录

插件提交至 [awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) 社区列表，收录后可在 dsh-market 中搜到。
