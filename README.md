# Build Your Own AI Voice

A plain-language guide for building a local writing assistant that sounds like *you* - not like a generic chatbot.

This repo is the practical companion to a blog series on building `ian-writer`, a custom [Ollama](https://ollama.com) model trained on Ian O'Byrne's writing. The posts explain the thinking. This repo gives you the template, sample selection process, and test prompts you can adapt for your own writer voice.

If you write blogs, newsletters, essays, lesson notes, or public reflections and you keep seeing AI flatten your tone, this project is for you.

---

## What this is

A custom Ollama model built from a detailed system prompt. You give it your writing rules, your patterns, and real samples of your own work. It learns to write in your register, not the default one.

It is a **writer voice tool**, not a ghostwriter. It helps you draft and revise in your own style instead of sounding like a generic assistant.

## What this is not

- A fine-tuned model — the base model's weights don't change
- A RAG system — it can't search your notes or documents
- A general-purpose assistant — it's scoped to your voice

## Why someone would want this

- You already have a recognizable writing voice and want AI to respect it
- You want to speed up drafting without losing your tone
- You keep rewriting AI text because it sounds close, but not quite like you
- You want a local workflow, not a cloud service that learns from your drafts

## What you need

- [Ollama](https://ollama.com) installed and running
- A base model pulled locally, like `mistral`, `llama3`, or `qwen2:14b`
- 4-6 samples of your own writing that feel representative
- A little time to read your own work carefully and notice patterns
- Willingness to be honest about what actually sounds like you

---

## How to use this repo

1. Read `SAMPLES.md` first. Choosing the right samples matters more than polishing the template.
2. Copy `template.modelfile` and rename it, for example `yourname-writer.modelfile`.
3. Fill in each section with your own name, audience, voice rules, and sample passages.
4. Build and run your model:

```bash
ollama pull mistral
ollama create yourname-writer -f yourname-writer.modelfile
ollama run yourname-writer
```

5. Test it using the prompts in `TESTING.md`.
6. Iterate - edit the modelfile, rebuild, test again.

## What good results look like

The best version of this system should:

- Sound like a real person thinking on the page
- Keep your normal sentence rhythm and paragraph flow
- Explain things the way you usually explain them
- Respect the difference between your current voice and older habits
- Help you start faster without sanding off your style

---

## Files

| File | What it is |
|------|-----------|
| `template.modelfile` | The annotated Modelfile template — start here |
| `SAMPLES.md` | How to find and choose your writing samples |
| `TESTING.md` | Standard prompts for evaluating your model |

---

## Further reading

Blog series at [wiobyrne.com](https://wiobyrne.com) - the posts walk through the thinking behind each decision in this template.
