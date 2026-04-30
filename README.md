# Wandering Witch Characters Skill

A Codex-compatible skill containing distilled character cards from a local Wandering Witch / Majo no Tabitabi book corpus.

This repository contains high-level characterization notes, not raw book text. It is intended for character-consistent writing, roleplay, analysis, remixing, and narrative planning.

## Contents

- `SKILL.md`: the skill entry point and workflow.
- `agents/openai.yaml`: Codex UI metadata.
- `references/character-index.md`: aliases, coverage notes, and card index.
- `references/characters/`: individual distilled character cards.

## Characters

The current cards cover:

- Elaina / 伊蕾娜
- Saya / 沙耶
- Fran / 芙兰
- Sheila / 席拉
- Amnesia / 艾姆妮西亚
- Avilia / 艾维莉亚
- Mina / 美奈
- Nike / Victorica / 妮可 / 薇多利加
- Liliel / 莉莉艾尔
- Annelotte / 安妮洛特
- Priscilla / 普莉希拉
- Matryoshika / 玛特丽希卡
- Selena / 瑟琳娜
- Vivian / 薇薇安
- Mirarose / 米菈罗赛

## Install

Clone or copy this folder into a Codex skill location, then restart Codex so it reloads skill metadata.

Typical locations:

```text
$CODEX_HOME/skills/wandering-witch-characters
~/.codex/skills/wandering-witch-characters
```

Use it explicitly with:

```text
$wandering-witch-characters
```

or ask naturally for Wandering Witch character-consistent writing.

## Design

The skill follows the Agent Skills pattern:

- `SKILL.md` stays small and procedural.
- Detailed character data lives in `references/` and is loaded only when relevant.
- Each character card is a distilled behavioral model with sections for core identity, abilities, decision algorithm, voice, relationships, and boundaries.

## Copyright

This repository does not include the source books. The cards are distilled notes from user-provided local files and should be used for high-level characterization only. Do not use this skill to reproduce chapters, long scenes, or distinctive passages from copyrighted works.

## License

MIT.
