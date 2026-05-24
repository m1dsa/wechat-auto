# wechat-auto

公众号自动写作 skill，用于把公众号内容生产拆成一套可执行流程：选题、内容诊断、文章写作和排版输出。

## 适合场景

- 从零生成公众号选题
- 判断一个选题应该怎么做
- 根据选题和方向写出文章
- 对成稿进行公众号排版输出
- 面向 AI 小白、技术小白写 AI 实战经验和教程

## 仓库结构

```text
wechat-auto/
├── .codex-plugin/
│   └── plugin.json
├── skills/
│   └── wechat-auto/
│       ├── agents/
│       │   └── openai.yaml
│       └── SKILL.md
├── .gitignore
├── LICENSE
└── README.md
```

## 使用方式

把 `skills/wechat-auto` 安装到 claude 的 skills 目录后，可以用下面这些方式触发：

- `/wechat-auto`
- `/公众号写作`
- `帮我写一篇公众号文章`
- `从选题开始`

也可以直接对 Codex 说：使用 `wechat-auto` 帮我做公众号选题、写作或排版。

## 主要流程

1. 选题：围绕账号定位生成可执行选题。
2. 内容诊断：判断选题是否值得做，以及应该怎么切入。
3. 写文章：生成结构清楚、适合普通读者阅读的公众号文章。
4. 排版输出：把文章整理成适合公众号发布的格式。

## 许可证

MIT License

## 特别提醒
第二步内容诊断截取的db.skill
