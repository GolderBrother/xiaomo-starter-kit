# 📚 推荐 Skills 安装指南

基于 xiaomo-starter-kit 和已安装的技能整理。

---

## 🌟 已安装的技能

### 📹 视频与转录
- ✅ **video-transcript-downloader** - 下载 YouTube 视频、音频、字幕和文本稿
- ✅ **youtube-watcher** - 获取和阅读 YouTube 视频转录稿（需要安装依赖）

### 📝 文档处理
- ✅ **markdown-converter** - 将 PDF、Word、PPT、Excel 等文档转为 Markdown

### 🌱 个人成长
- ✅ **munger-observer** - 用查理·芒格的多元思维模型审视决策
- ✅ **self-love-confidence** - 建立自信与自爱，记录成就
- ✅ **therapy-mode** - 基于 CBT、ACT、DBT 的心理疏导
- ✅ **weekly-synthesis** - 每周工作与思考总结

### ✍️ 写作优化
- ✅ **de-ai-ify** - 移除 AI 生成文本的常见痕迹
- ✅ **humanizer** - 基于维基百科指南，系统性去除 AI 写作模式

### 📈 营销技能包（21 个子技能）
- ✅ **marketing-skills** - 完整的营销工具集
  - A/B测试、分析追踪、竞品比较、文案编辑
  - 营销文案、邮件序列、表单优化、免费工具策略
  - 产品发布、营销创意、营销心理学、用户引导
  - 页面优化、付费广告、付费墙优化、弹窗优化
  - 定价策略、程序化SEO、推荐计划、结构化标记
  - SEO审计、注册流程优化、社交内容

### ⏰ 提醒与任务
- ✅ **remind-me** - 自然语言设置提醒

### 🌤️ 实用工具
- ✅ **weather** - 天气查询
- ✅ **bitwarden** - 密码管理

### 🔧 开发工具
- ✅ **mcporter** - MCP 服务器管理
- ✅ **skill-creator** - 创建和更新 AgentSkills

### 🏢 腾讯内部工具
- ✅ **gongfeng** - 工蜂代码仓库管理（29 个工具）
- ✅ **tapd** - TAPD 项目管理（49 个工具）
- ✅ **claude-internal** - 内网版 Claude Code

---

## 🎯 推荐安装（待安装）

### 📧 效率工具

#### Google 套件
```bash
clawdhub install gog
```
- Gmail/Calendar/Drive 管理
- 需要 Google OAuth 配置

#### GitHub
```bash
# 内置 skill，需要 gh CLI 登录
gh auth login
```

### 📋 任务管理

#### TODO Tracker
```bash
clawdhub install jdrhyne/todo-tracker
```
- 任务管理，支持优先级和完成状态

#### Things (macOS)
```bash
clawdhub install things-mac
```
- Things 3 任务管理（仅限 macOS）

### 📰 信息获取

#### Reddit
```bash
clawdhub install reddit
```
- 浏览、搜索 Reddit 内容

#### 博客监控
```bash
clawdhub install blogwatcher
```
- 监控 RSS/Atom 订阅源

### 🎨 创意工具

#### OpenAI 图像生成
```bash
clawdhub install openai-image-gen
```
- 批量生成图像

#### 视频帧提取
```bash
clawdhub install video-frames
```
- 从视频中提取帧或短片段

### 🧘 更多个人成长工具

jhillin8 作者的其他优秀技能：
```bash
# 焦虑缓解
clawdhub install jhillin8/anxiety-relief

# 压力缓解
clawdhub install jhillin8/stress-relief

# 习惯追踪
clawdhub install jhillin8/habit-tracker

# 感恩日记
clawdhub install jhillin8/gratitude-journal

# 正念冥想
clawdhub install jhillin8/mindfulness-meditation

# 早晨例程
clawdhub install jhillin8/morning-routine

# 夜间例程
clawdhub install jhillin8/night-routine
```

### 📝 笔记与知识管理

#### Obsidian
```bash
clawdhub install obsidian
```
- Obsidian vault 管理

#### Notion
```bash
clawdhub install notion
```
- Notion 页面和数据库管理

#### Apple Notes
```bash
clawdhub install apple-notes
```
- 通过 memo CLI 管理（仅限 macOS）

---

## 🔍 发现更多技能

### ClawdHub
完整技能列表：https://clawdhub.com

### openclaw-skills 仓库
社区贡献的技能：https://github.com/moltbot/skills

### 搜索技能
```bash
# 列出所有技能
moltbot skills list

# 搜索特定技能
clawdhub search [关键词]
```

---

## 📖 安装说明

### 使用 ClawdHub（推荐）
```bash
# 安装单个技能
clawdhub install [skill-name]

# 安装特定作者的技能
clawdhub install [author]/[skill-name]
```

### 手动安装
```bash
# 1. 克隆 openclaw-skills 仓库
git clone https://github.com/moltbot/skills.git /tmp/openclaw-skills

# 2. 复制技能到 Moltbot 目录
cp -r /tmp/openclaw-skills/skills/[author]/[skill-name] \
  /usr/local/lib/.nvm/versions/node/v22.17.0/lib/node_modules/moltbot/skills/

# 3. 验证安装
moltbot skills list | grep [skill-name]
```

---

## 💡 使用建议

### 每日工作流
1. 使用 **remind-me** 设置当天提醒
2. 使用 **self-love-confidence** 记录成就
3. 使用 **munger-observer** 审视重要决策

### 每周复盘
1. 使用 **weekly-synthesis** 生成周报
2. 回顾 **therapy-mode** 会话笔记
3. 更新 MEMORY.md 长期记忆

### 内容创作
1. 使用 **marketing-skills** 规划营销策略
2. 使用 **de-ai-ify** 和 **humanizer** 优化文案
3. 使用 **video-transcript-downloader** 获取视频素材

---

*定期更新此文件，记录新安装的技能和使用心得。*
