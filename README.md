# My Skills

**我的 Claude Code Skills 合集。**

## 这是什么？

这里收集了我从书籍、方法论中提炼出来的 Claude Code Skills。每个 skill 都是一个可交互、可复用的工具，帮助你把"读过的方法论"变成"能用的工具"。

## Skills 列表

| Skill | 来源书籍 | 功能 |
|-------|---------|------|
| [book-to-skill](skills/book-to-skill) | 多本书籍的方法论 | 把书籍转化为 Claude Code Skills |
| [system-trap-detector](skills/system-trap-detector) | 《系统之美》 | 识别 8 大系统陷阱，提供破解策略 |
| [specific-knowledge-finder](skills/specific-knowledge-finder) | 《纳瓦尔宝典》 | 帮助找到你的专长和可产品化方向 |

## 如何使用这些 Skills？

### 安装方法

**方法一：复制到 Claude Code skills 目录**

```bash
# 克隆仓库
git clone https://github.com/你的用户名/my-skills.git

# 复制你想要的 skill 到你的 skills 目录
cp -r my-skills/skills/book-to-skill ~/.claude/skills/
cp -r my-skills/skills/system-trap-detector ~/.claude/skills/
cp -r my-skills/skills/specific-knowledge-finder ~/.claude/skills/
```

**方法二：复制整个仓库**

```bash
# 复制所有 skills
cp -r my-skills/skills/* ~/.claude/skills/
```

### 在 Claude Code 中使用

安装后，在 Claude Code 中直接调用：

```
/book-to-skill 原子习惯
/system-trap-detector
/specific-knowledge-finder
```

## 为什么做这个？

我读过很多方法论书籍，但常常遇到一个问题：

> "这方法太棒了！"
> （合上书）
> "所以...我什么时候用？怎么用？"

这些 skill 就是为了解决这个问题——把抽象的方法论变成具体的工具。

**核心理念：**

每个 skill 都有**使用样例**，让没读过书的人也能理解它的价值：

```
❌ 泛泛场景："想提升产品竞争力"
✅ 真实痛点："我每天工作12小时，产出却和同事差不多"
```

好的使用样例让用户觉得"这说的就是我"。

## 仓库结构

```
my-skills/
├── README.md                           # 你正在看的文件
└── skills/
    ├── book-to-skill/                  # 从书籍创建 skill 的工具
    │   ├── README.md
    │   ├── SKILL.md
    │   └── references/
    ├── system-trap-detector/           # 系统陷阱识别器
    │   ├── SKILL.md
    │   └── references/
    └── specific-knowledge-finder/      # 专长发现器
        ├── SKILL.md
        └── references/
```

## 贡献

欢迎贡献新的 skill 或改进现有的！

1. Fork 本仓库
2. 添加你的 skill 到 `skills/` 目录
3. 提交 Pull Request

## License

MIT License
