# Changelog

## 2026-06-18

### 日本語への最適化

英語向けのルールセットを、日本語のAI/翻訳調文章に特有の癖に合わせて全面的に作り直した。

**方針**
- 英語固有のルール(`-ly` 副詞の一掃、Wh- 始まりの文の禁止、受動態・主語の全面明示など)を削除。日本語では受動態・主語省略・無生物主語・対比・体言止め・カタカナ語・敬語はいずれも自然なため、「全廃ではなく濫用時のみ」直す方針に統一し、各ルールへ「残してよい場合」を明記。

**新設・翻案したパターン**
- `SKILL.md` — 基本ルール8項目・クイックチェック・採点をすべて日本語の癖に翻案。
- `references/phrases.md` — 定型の前置き／締め(「いかがでしたか」「参考になれば幸いです」)、空疎な強調・誇張、冗長表現(「することができます」)、過剰敬語、カタカナビジネス語、抽象名詞化(〜化／〜性／〜的)、曖昧な指示語(こちら)、断定回避のヘッジ。
- `references/structures.md` — 作られた対比、翻訳調の無生物主語、英語語順の長い連体修飾、文末の単調・体言止め連打・記号の濫用、主体をぼかした受動の連発、レイアウトの定型。
- `references/examples.md` — 日本語の Before / After 変換例8本に全面差し替え。

## 2026-01-13

### Added

**Phrases (references/phrases.md)**
- Throat-clearing: "Here's what I find interesting", "Here's the problem though"
- Performative emphasis: "creeps in", "I promise", "They exist, I promise"
- Telling instead of showing: "This is genuinely hard", "This is what leadership actually looks like"

**Structures (references/structures.md)**
- Binary contrasts: "Not X. But Y.", "It's not this. It's that.", "stops being X and starts being Y"
- Rhythm patterns: staccato fragmentation, dashes for dramatic pause, hedging as reassurance
- Word patterns: absolute words (always, never, everyone, etc.), AI-overused intensifiers (deeply, truly, fundamentally, inherently, simply, literally, inevitably)

## 2026-01-12

- Restructured skill following Claude Code best practices (PR #1)
- Split into SKILL.md and references/ folder

## 2025-01-12

- Initial release
