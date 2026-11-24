---
name: yt-survival
description: >-
  Write a short-form Roblox "survival escalation" voiceover script in Arabic
  (the "If you're lost in the forest, what do you do?" format, like In This
  Town shorts). Use for "اكتب لي سكربت بقاء", "لو ضعت في ...", Roblox shorts
  scripts, or any scenario that escalates shelter -> weakness -> fix. Halal
  content only.
---

# yt-survival

The format: a survival question, then a chain of **fix -> weakness -> better fix**. Every sentence
opens a new question, so the viewer keeps watching to see the next hole get patched.

Read `~/.claude/youtube/voice.md` first, especially the **Halal filter** section. If the scenario
or any line breaks it, change it silently to a permitted version and say what you changed.

## Input

One scenario: forest, desert, island, abandoned city, snowstorm, night in the mountains, flood.
If the user gives none, offer three and pick the strongest.

## The chain

1. **Hook (first 2 seconds).** The question, in one line. "لو ضعت في الغابة، وش تسوي؟"
2. **Fix 1.** "أول شيء، تبني ملجأ." Name one concrete thing, shown on screen.
3. **Praise + weakness.** "جميل، الحين عندك ملجأ... لكنه ما يحميك من [X]." X must be a real,
   visible threat in the Roblox scene (rain, cold, wolves, flood, dark).
4. **Fix 2** that patches X. Then praise, then weakness Y. Repeat.
5. **Length.** 5 to 7 rounds for a 30 to 45 second Short. Each round is 2 short sentences.
6. **Ending.** Do not end on a lecture. End on the final fortified state plus one cliffhanger
   line: "بس السؤال... وش اللي جاي؟" so the loop or the next part pulls.

## Voiceover rules

- Arabic, white dialect (understood in the Gulf and beyond). Short spoken sentences, no فصحى stiffness.
- Max about 12 words per sentence. One idea per sentence.
- Say the weakness BEFORE the fix, never both in one breath. The gap is the hook.
- No invented statistics. No claims the footage cannot show.
- No music cue is required. If the user wants sound, use effects or a vocals-only nasheed, never instruments.
- Mark `[SHOW: ...]` beside each line for what the screen shows, so the edit matches the words.

## Output

```
HOOK:   ...
1  VO: ...        [SHOW: ...]
   VO: ...
2  ...
END:    ...
```

Also hand back: three alternative hooks, and a title of at most 40 characters.

## The gate

Nothing here publishes. The last line of every run is the question: **ship it, or change it?**
