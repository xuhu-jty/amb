# amb

一个 Claude Code 技能：把用户的想法往**速度、高度、深度、广度**上升级，避免模型交出「这类东西的平均样子」。

- `/amb <想法>`：只给升级后的改写稿，不执行；回复「执行」后才动手。
- `/amb-push`：对刚交出的成品追问一轮，指出最平庸的三处并要求推翻重做。
- 直接要作品、方案、研究、代码时：升级后直接做完。

详见 [skills/amb/SKILL.md](skills/amb/SKILL.md)。

## 安装

```
/plugin marketplace add xuhu-jty/amb
/plugin install amb@amb
```

或把 `skills/amb` 复制到 `~/.claude/skills/amb`。
