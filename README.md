# 魔女之旅角色 Skill

这是一个 Agent Skill / Codex Skill，内容来自本地《魔女之旅》书籍语料的角色蒸馏结果。

仓库只包含高层角色模型和写作约束，不包含原书文本。适合用来做角色一致性的写作、角色扮演、剧情分析、二创辅助和人物关系校准。

## 内容

- `SKILL.md`：skill 入口和使用流程。
- `references/character-index.md`：角色别名、覆盖情况和索引。
- `references/characters/`：每个角色的蒸馏卡片。

## 已覆盖角色

当前包含：

- 伊蕾娜 / Elaina
- 沙耶 / Saya
- 芙兰 / Fran
- 席拉 / Sheila
- 艾姆妮西亚 / Amnesia
- 艾维莉亚 / Avilia
- 美奈 / Mina
- 妮可 / 薇多利加 / Nike / Victorica
- 莉莉艾尔 / Liliel
- 安妮洛特 / Annelotte
- 普莉希拉 / Priscilla
- 玛特丽希卡 / Matryoshika
- 瑟琳娜 / Selena
- 薇薇安 / Vivian
- 米菈罗赛 / Mirarose

## 安装

把这个目录 clone 或复制到 Codex 的 skill 目录，然后重启 Codex，让它重新加载 skill 元数据。

常见位置：

```text
$CODEX_HOME/skills/wandering-witch-characters
~/.codex/skills/wandering-witch-characters
```

显式调用：

```text
$wandering-witch-characters
```

也可以直接自然语言要求“按魔女之旅角色一致性写作”。

## 设计

这个 skill 按 Agent Skills 的方式组织：

- `SKILL.md` 只保留触发描述和核心流程。
- 详细角色资料放在 `references/`，需要时再加载。
- 每张角色卡都按“核心、能力、行动算法、语气、关系锚点、使用边界”组织。

## 版权说明

本仓库不包含原书文件。这里的角色卡是从用户本地提供的书籍文件中蒸馏出的高层笔记，只用于角色理解和创作辅助。不要用它复现受版权保护的章节、长场景或具有高度识别性的原文段落。

## 许可证

MIT.
