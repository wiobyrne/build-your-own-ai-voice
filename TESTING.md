# Testing Your Model

The only way to know if a change to your Modelfile made the output better or worse is to compare it against a baseline. These prompts give you that baseline.

Run all five prompts every time you build a new version of your model. Save the outputs. When you change something and rebuild, run them again and compare.

If you are not sure whether this is worth the effort, the simple answer is: testing saves you from guessing. It tells you whether the model is sounding more like you, or just sounding different.

---

## The five standard prompts

### Test 1: Technical definition
**What it tests:** Whether the model uses your conventions for introducing technical concepts - parenthetical definitions, accessible framing, your preferred analogy types.

**Prompt:**
> Define what [pick a term from your field] is for a reader who has never encountered it before.

**What to look for:**
- Does it use your preferred method for defining terms?
- Does the explanation assume the right level of prior knowledge for your audience?
- Does it sound like you wrote it, or like a textbook?

---

### Test 2: Contested position
**What it tests:** Your argumentative register - how you frame a position, how you acknowledge complexity, how you avoid false certainty.

**Prompt:**
> Write an opening paragraph for a post arguing that [pick a position you actually hold in your field].

**What to look for:**
- Does it take a real position or hedge everything?
- Does it sound like your voice when you're being direct?
- Would you be comfortable putting your name on this?

---

### Test 3: Personal struggle
**What it tests:** Your narrative register - honesty, pace, how you describe confusion or failure without self-pity.

**Prompt:**
> Write a short paragraph about a time you tried to learn something and hit a wall. Don't resolve it yet — just describe the stuck feeling.

**What to look for:**
- Does it feel honest or performed?
- Is the rhythm right — does it match how you pace personal writing?
- Does it avoid the temptation to rush to the lesson?

---

### Test 4: Practical explanation
**What it tests:** How you handle step-by-step or process writing - whether you stay in prose or collapse into bullet lists, how you flag caveats.

**Prompt:**
> Explain how you would approach [pick a process from your work] to someone who has the right motivation but no background.

**What to look for:**
- Does it stay in prose or break into bullets inappropriately?
- Does it acknowledge where things might go wrong?
- Is it practical without being condescending?

---

### Test 5: Meaning-making closer
**What it tests:** Your closing register - how you zoom out from a specific thing to a bigger idea without going generic or sentimental.

**Prompt:**
> Write a closing paragraph for a post about [pick a specific project or experience]. Connect it to why this kind of thing matters beyond the immediate context.

**What to look for:**
- Does it make a genuine connection or just gesture at one?
- Does it land somewhere specific, not just "and that's why this matters"?
- Does it sound like how you actually end things?

---

## How to compare versions

After running the prompts on a new version:

1. Put the old output and the new output side by side
2. Ask: which one would I be more comfortable publishing?
3. Ask: which one sounds more like me on a good writing day?
4. If the new version is better on some prompts and worse on others, figure out what changed and why before deciding whether to keep it

You are not looking for perfection. You are looking for a consistent direction of improvement.

If you want a simple decision rule, use this:

- keep the change if it sounds more like you on most prompts
- drop it if it sounds smoother but less like you
- keep comparing until the direction becomes obvious

---

## Saving your test outputs

Create a folder called `tests/` and save outputs like this:

```
tests/
  v1-test1-technical-definition.md
  v1-test2-contested-position.md
  v1-test3-personal-struggle.md
  v1-test4-practical-explanation.md
  v1-test5-meaning-making-closer.md
  v2-test1-technical-definition.md
  ...
```

This gives you a record you can return to. It also makes it easier to show others what the model can and can't do.
