# My Skills

**小红书 @小灯只工作不上班 的 Claude Code Skills 合集**

## Skills目录

| Skill | 一句话介绍 |
|-------|----------|
| [book-to-skill](book-to-skill) |  把一本好书变成 Claude Code Skills |
| [system-trap-detector](system-trap-detector) |  识别系统陷阱，找到破解策略 |
| [specific-knowledge-finder](specific-knowledge-finder) |  找到你的专长和可产品化方向 |

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

## 贡献

欢迎贡献新的 skill 或改进现有的！

## License

MIT License
