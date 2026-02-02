# 已安装技能清单

*最后更新：2025-02-02*

本文档记录了当前环境中已安装并可用的 Moltbot 技能。

---

## 📊 统计

- **总技能数**: 95 个
- **可用技能**: 42 个 ✓
- **缺失依赖**: 45 个 ✗
- **已禁用**: 8 个 ⏸

---

## ✓ 已就绪的技能（42个）

### 🔐 密码与认证
- **bitwarden** - 密码管理（Bitwarden CLI）

### 📄 文档与转换
- **markdown-converter** - 文档转 Markdown（支持 PDF/Word/Excel/PPT 等）

### ✍️ 写作与编辑
- **de-ai-ify** - 去除 AI 生成文本痕迹
- **humanizer** - 系统化去 AI 味儿（基于维基百科指南）
- **copy-editing** - 营销文案编辑审查
- **copywriting** - 营销文案撰写

### 🎨 设计与可视化
- **Excalidraw Flowchart** - 流程图生成

### 🧠 个人成长
- **munger-observer** - 芒格多元思维模型应用
- **self-love-confidence** - 自信与自爱培养
- **therapy-mode** - 专业心理疏导框架
- **weekly-synthesis** - 每周复盘总结

### 📈 营销技能（21个子技能）
- **ab-test-setup** - A/B 测试设计
- **analytics-tracking** - 分析追踪设置
- **competitor-alternatives** - 竞品对比页面
- **email-sequence** - 邮件序列/滴灌营销
- **form-cro** - 表单转化优化
- **free-tool-strategy** - 免费工具营销策略
- **launch-strategy** - 产品发布策略
- **marketing-ideas** - 营销创意（140+ 方法）
- **marketing-psychology** - 营销心理学（70+ 心智模型）
- **onboarding-cro** - 用户激活优化
- **page-cro** - 页面转化优化
- **paid-ads** - 付费广告投放
- **paywall-upgrade-cro** - 付费墙优化
- **popup-cro** - 弹窗转化优化
- **pricing-strategy** - 定价策略
- **programmatic-seo** - 程序化 SEO
- **referral-program** - 推荐计划
- **schema-markup** - Schema 结构化数据
- **seo-audit** - SEO 审计
- **signup-flow-cro** - 注册流程优化
- **social-content** - 社交媒体内容

### 🛠️ 开发工具
- **mcporter** - MCP 服务管理
- **skill-creator** - 技能创建工具
- **gongfeng** - 工蜂代码管理（29 个工具）
- **tapd** - TAPD 项目管理（49 个工具）

### 🌐 内网工具
- **claude-internal** - 内网版 Claude Code

### 📦 其他实用工具
- **bluebubbles** - BlueBubbles 插件构建
- **remind-me** - 自然语言提醒
- **todo-tracker** - TODO 任务追踪
- **video-transcript-downloader** - 视频/音频/字幕下载
- **weather** - 天气查询

---

## ✗ 缺失依赖的技能（45个）

这些技能已安装但缺少必要的 CLI 工具或依赖：

### 密码与笔记
- 1password, apple-notes, apple-reminders, bear-notes, notion, obsidian

### 消息与社交
- bird (Twitter), imsg (iMessage), wacli (WhatsApp), slack

### 媒体与音频
- blucli (BluOS), camsnap, gifgrep, nano-banana-pro, openai-image-gen
- openai-whisper, openai-whisper-api, sag (ElevenLabs TTS)
- sherpa-onnx-tts, songsee, sonoscli, spotify-player

### 开发工具
- github (gh CLI), coding-agent, nano-pdf, oracle, peekaboo, tmux

### 家居与 IoT
- eightctl (Eight Sleep), openhue (Philips Hue)

### 其他
- blogwatcher, clawdhub, gemini, gog (Google Workspace), goplaces
- himalaya (邮件), local-places, model-usage, morning-email-rollup
- ordercli, session-logs, summarize, things-mac, trello
- video-frames, voice-call, youtube-watcher

---

## ⏸ 已禁用的技能（8个）

内网特定工具，按需启用：

- **fit_devops** - FTP 交付单管理
- **itrpc** - 星斗平台部署管理
- **iwiki** - iWiki 文档管理（27 个工具）
- **launcher** - 游戏构建打包
- **mmec_woa_com** - 应用架构元信息管理
- **dola知识库mcp** - Dola 知识库
- **roger** - Roger 文档管理（19 个工具）
- **sg2api_sfee** - SFee 产品查询
- **公益平台-sre-agent** - SRE Agent（19 个工具）
- **tcamp/live** - 直播与营地管理

---

## 📥 推荐安装

如果想扩展能力，建议安装以下 CLI 工具：

### 高优先级
```bash
# Google Workspace 集成
npm install -g @clawdapp/gog

# GitHub 集成
brew install gh

# 视频处理依赖
npm install -g youtube-watcher

# ElevenLabs 语音合成
npm install -g sag
```

### 中优先级
```bash
# 1Password
brew install 1password-cli

# 邮件管理
brew install himalaya

# Apple Notes
brew install memo-cli

# Things 3
brew install things-cli
```

---

## 🔧 技能管理命令

```bash
# 查看所有技能
moltbot skills list

# 搜索新技能
npx clawdhub search <keyword>

# 安装新技能
npx clawdhub install <skill-name>

# 更新技能
npx clawdhub sync
```

---

## 📝 使用建议

1. **营销工作** → 使用 marketing-skills 系列（21 个子技能）
2. **写作优化** → de-ai-ify, humanizer, copy-editing
3. **个人成长** → munger-observer, therapy-mode, weekly-synthesis
4. **开发工作** → gongfeng, tapd, claude-internal
5. **提醒任务** → remind-me, todo-tracker

---

*此文档由 Moltbot 自动生成，基于 `moltbot skills list` 输出。*
