# Horizon 每日 IM 推送配置

已配置默认方案：**每天北京时间 08:30 自动运行，并推送到飞书群机器人**。

## 你需要在 GitHub 仓库里添加 Secrets

路径：`Settings → Secrets and variables → Actions → New repository secret`

必填：

- `HORIZON_WEBHOOK_URL`：飞书或钉钉自定义群机器人的 Webhook URL
- `OPENAI_API_KEY`：如果继续使用 `data/config.github.json` 里的 OpenAI 配置

可选：

- `ANTHROPIC_API_KEY` / `GOOGLE_API_KEY`：只有当你把 `ai.provider` 改成对应服务时才需要
- `LWN_KEY`：只有启用 LWN RSS 时才需要

## 飞书机器人

1. 飞书群 → 群设置 → 群机器人 → 添加机器人 → 自定义机器人
2. 安全设置建议选择「关键词」：`Horizon`
3. 复制 Webhook URL 到 GitHub Secret：`HORIZON_WEBHOOK_URL`

当前 `data/config.github.json` 已启用飞书卡片：

```json
"webhook": {
  "enabled": true,
  "url_env": "HORIZON_WEBHOOK_URL",
  "platform": "feishu",
  "layout": "collapsible",
  "fallback_layout": "markdown",
  "languages": ["zh"]
}
```

## 钉钉机器人

如果你要改用钉钉：

1. 钉钉群 → 群设置 → 机器人 → 添加机器人 → 自定义机器人
2. 安全设置建议选择「关键词」：`Horizon`
3. 复制 Webhook URL 到 GitHub Secret：`HORIZON_WEBHOOK_URL`
4. 把 workflow 中的准备配置步骤从：

```yaml
run: cp data/config.github.json data/config.json
```

改成：

```yaml
run: cp data/config.github.dingtalk.json data/config.json
```

## 手动测试

GitHub 仓库页面：`Actions → Daily Horizon Summary → Run workflow`。

成功后会：

1. 生成 Horizon 日报
2. 推送到飞书/钉钉群
3. 发布到 GitHub Pages 的 `gh-pages` 分支
