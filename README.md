# Codex Profile

可跨设备复用的个人 Codex 配置。仓库只保存行为准则与可公开的设置模板；不保存账号、会话、缓存或机器相关状态。

## 内容

- `AGENTS.md`：个人协作与改动偏好。
- `config.toml.example`：可复制到 `~/.codex/config.toml` 的基础设置示例。
- `.gitignore`：防止误提交认证、会话和本机缓存。

## 使用

1. 按需将 `AGENTS.md` 合并到 `~/.codex/AGENTS.md`。
2. 将 `config.toml.example` 中需要的字段复制到 `~/.codex/config.toml`。
3. 本机路径、MCP 服务地址、通知命令和项目 `trust_level` 请自行填写；它们不适合跨设备直接共享。

## 不入库的内容

- `auth.json`、OAuth 信息和访问令牌。
- SQLite 状态库、会话、附件、日志、终端快照与缓存。
- 设备标识、安装标识和由应用自动维护的状态文件。
- 某一项目专属的 `AGENTS.md`、Skills 与规则。
