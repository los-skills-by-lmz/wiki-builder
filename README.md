# Wiki Builder / 维基建造者

<div align="center">
  <p>
    <a href="#english">English</a> | <a href="#chinese">中文</a>
  </p>
</div>

---

<a name="english"></a>
## 🇬🇧 English

### What is this?

**Wiki Builder** is a Claude Code Skill that turns Karpathy's viral "LLM Wiki" concept into a one-click install.

> 12M+ views. Everyone talked about it. No one built it. Now it's here.

### One Sentence

**Drop files into `raw/`, AI auto-generates summaries, backlinks, and TODO lists.**

### What problem does it solve?

You have hundreds of chat logs, saved articles, and scattered notes. But they are just a pile of "stones" - no structure, no connections, no action.

Wiki Builder gives you an **AI knowledge engineer** that works 24/7:
- Reads everything you throw into `01_原始素材库/`
- Writes structured summaries
- Builds bidirectional links automatically
- Extracts actionable TODO lists
- Maintains a living, growing personal Wikipedia

### Quick Start

**1. Install**
Download `wiki-builder.skill` and double-click to import into Claude Code.

**2. Initialize**
In your project folder (any empty folder), run:
``
/wiki-builder init
``

AI will automatically create:
``
your-project/
├── AGENTS.md
├── 01_原始素材库/
└── 02_AI知识库/
``

**3. Start using**
- **Add material**: Put any `.md`, `.txt`, PDF files into `01_原始素材库/`
- **Trigger import**: Tell Claude Code: `/wiki-builder ingest`
- **Query**: Ask: "What does my knowledge base have about X?"

### Commands

| Command | What it does |
|---------|---------------|
| `/wiki-builder init` | Initialize folder structure |
| `/wiki-builder ingest` | Process new files in `01_原始素材库/` |
| `/wiki-builder query "question"` | Search and answer from your knowledge base |
| `/wiki-builder lint` | Health check - find orphans and outdated info |

### How It Works

``
01_原始素材库/ (raw files)
        ↓
   [AI processes]
        ↓
02_AI知识库/ (structured Wiki)
   ├── index.md (auto-maintained TOC)
   ├── summaries with backlinks
   └── extracted TODO lists
``

### The Result

**What you get**:
- A personal Wikipedia that grows with you
- AI that remembers everything you've read
- TODO lists extracted from your conversations
- Zero manual organization work

**What you don't get**:
- Monthly fees (it's free)
- Vendor lock-in (files are yours)
- Complexity (it just works)

### Why Free?

This is open source. The code is on GitHub. Use it, modify it, share it.

If you want to support development, star the repo, share it

### License

MIT

---

<a name="chinese"></a>
## 🇨🇳 中文

### 这是什么？

**Wiki Builder** 是一个Claude Code Skill，把卡帕西引爆硅谷的「LLM Wiki」概念做成了一键安装包。

> 1200万+浏览量。所有人都在讨论，但没人做出来。现在有了。

### 一句话说清楚

**把文件扔进`raw/`文件夹，AI自动帮你写摘要、建链接、提取待办清单。**

### 解决什么问题？

你有几百篇聊天记录、收藏的文章、散落的笔记。但它们只是一堆「石头」——没有结构、没有连接、没有行动。

Wiki Builder给你一个**24小时待命的AI知识工程师**：
- 自动读取你扔进`01_原始素材库/`的一切
- 自动写结构化摘要
- 自动建立双向链接
- 自动提取可执行的待办清单
- 自动维护一个不断生长的个人维基百科

### 快速开始

**1. 安装**
下载`wiki-builder.skill`文件，双击导入Claude Code。

**2. 初始化**
在你的项目文件夹（任意空文件夹）中执行：
``
/wiki-builder init
``

AI会自动创建：
``
你的项目/
├── AGENTS.md
├── 01_原始素材库/
└── 02_AI知识库/
``

**3. 开始使用**
- **添加素材**：把任何`.md`、`.txt`、PDF文件放进`01_原始素材库/`
- **触发导入**：对Claude Code说：`/wiki-builder ingest`
- **查询**：问它：「关于XX，我的知识库里有什么？」

### 命令列表

| 命令 | 作用 |
|------|------|
| `/wiki-builder init` | 初始化文件夹结构 |
| `/wiki-builder ingest` | 处理`01_原始素材库/`中的新文件 |
| `/wiki-builder query "问题"` | 从知识库中检索回答 |
| `/wiki-builder lint` | 检查知识库健康状态 |

### 工作原理
``
01_原始素材库/ (原始文件)
        ↓
   [AI自动处理]
        ↓
02_AI知识库/ (结构化Wiki)
   ├── index.md (AI维护的总目录)
   ├── 带双向链接的摘要文章
   └── 提取出的待办清单
``

### 你会得到什么？

**你得到的**：
- 一个不断生长的个人维基百科
- 一个记住你读过一切的AI
- 从对话中自动提取的待办清单
- 零手动整理工作

**你不会遇到的**：
- 月费（免费）
- 厂商锁定（文件是你的）
- 复杂配置（开箱即用）

### 为什么免费？

这是开源项目。代码在GitHub上。你可以用、改、分享。

如果想支持开发，点个star、分享出去

### 开源协议

MIT

---

## Links / 链接

- **GitHub**: [github.com/yourusername/wiki-builder](https://github.com/los-skills-by-lmz/wiki-builder)
- **Skill下载**: [Releases页面](https://github.com/los-skills-by-lmz/wiki-builder/releases)
- **作者X**: [@yourhandle](https://x.com/lmz)

---

<div align="center">
  <sub>Built with ☕ by Antipode | 用☕建造 by 逆熵者</sub>
</div>
