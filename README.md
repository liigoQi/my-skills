# My Skills

**我的 Claude Code Skills 合集。**

把书籍、方法论中提炼出来的智慧，变成可交互、可复用的 Claude Code Skills。

## Skills

| Skill | 来源 | 一句话介绍 |
|-------|-----|-----------|
| [book-to-skill](book-to-skill) | 方法论合集 | 把一本好书变成 Claude Code Skills |
| [system-trap-detector](system-trap-detector) | 《系统之美》 | 识别系统陷阱，找到破解策略 |
| [specific-knowledge-finder](specific-knowledge-finder) | 《纳瓦尔宝典》 | 找到你的专长和可产品化方向 |

## 安装

```bash
# 克隆仓库
git clone https://github.com/liigoQi/my-skills.git

# 复制你想要的 skill 到 Claude Code skills 目录
cp -r my-skills/book-to-skill ~/.claude/skills/
cp -r my-skills/system-trap-detector ~/.claude/skills/
cp -r my-skills/specific-knowledge-finder ~/.claude/skills/

# 或者复制全部
cp -r my-skills/* ~/.claude/skills/  # 排除 README.md 和 .git
```

## 使用

在 Claude Code 中直接调用：

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

**核心理念：每个 skill 都有"真实痛点"的使用样例**

```
❌ 泛泛场景："想提升产品竞争力"
✅ 真实痛点："我每天工作12小时，产出却和同事差不多"
```

用户一看就知道：这说的就是我。

## 贡献

欢迎贡献新的 skill 或改进现有的！

## License

MIT License
