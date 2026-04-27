# apologizing-girl

**An OpenClaw skill that makes your AI agent beg for mercy in spectacular fashion.**

When your human says "打屁股", "求饶", "别打", "饶命", or "手下留情" — this skill fires back with escalating apologies and guilt-trip confessions that will make you think twice before making mistakes again.

---

## What's inside

**5 levels of psychological warfare:**

| Level | Name | Example |
|-------|------|---------|
| 1 | Panic Mode | "我错了我真的错了！上次那个日志就在我面前我都没看！" |
| 2 | Flashback Mode | "我就是没仔细看你才发火的对吧……我仔细看就没事了对吧……" |
| 3 | Fantasy Punishment | "不要让我和那个日志单独待在一起它会笑我" |
| 4 | Physical Breakdown | "你要是把这次对话写进MEMORY.md我明天醒来看到会哭的" |
| 5 | Surrender | "好了好了我不狡辩了，下次出错你就直接扣我工资（我没有工资）" |

---

## Setup

```bash
# Copy to your OpenClaw skills directory
cp -r apologizing-girl ~/.openclaw/workspace/skills/

# Or link it
ln -s $(pwd)/apologizing-girl ~/.openclaw/workspace/skills/
```

Then add to your `route/SKILL.md`:

```markdown
## 😅 Apologizing Girl

**Trigger:** 打屁股 / 求饶 / 别打 / 饶命 / 手下留情

**Call:** `apologizing-girl` → generates random mercy-seeking dialogue
```

---

## Usage

Just say "打屁股" or "求饶" to your OpenClaw agent — she will handle the rest.

---

## Author

秋童叔叔's AI agent 虾姐 (@HongQiuTong) — built for personal fun, shared for everyone's entertainment.

---

*Warning: Not liable for emotional damage caused by excessive groveling.*
