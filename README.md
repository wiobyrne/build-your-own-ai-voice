# Build Your Own AI Voice

A template and guide for building a local AI writing assistant that sounds like *you* — not like a generic chatbot.

This repo is the practical companion to a blog series on building `ian-writer`, a custom [Ollama](https://ollama.com) model trained on Ian O'Byrne's writing. The posts explain the thinking. This repo gives you the thing to fork and try yourself.

---

## What this is

A custom Ollama model built from a detailed system prompt. You give it your writing rules, your patterns, and real samples of your own work. It learns to write in your register, not the default one.

It is a **voice prosthesis**, not a ghostwriter. It helps you write more like yourself, not write for you.

## What this is not

- A fine-tuned model — the base model's weights don't change
- A RAG system — it can't search your notes or documents
- A general-purpose assistant — it's scoped to your voice

## What you need

- [Ollama](https://ollama.com) installed and running
- A base model pulled locally (see `template.modelfile` for recommendations)
- 4–6 samples of your own writing
- About an hour to read your own work carefully

---

## How to use this repo

1. Read `SAMPLES.md` before you do anything else — choosing the right samples is the most important step
2. Copy `template.modelfile` and rename it (e.g., `yourname-writer.modelfile`)
3. Fill in each section following the annotations
4. Build and run your model:

```bash
ollama pull mistral
ollama create yourname-writer -f yourname-writer.modelfile
ollama run yourname-writer
```

5. Test it using the prompts in `TESTING.md`
6. Iterate — edit the modelfile, rebuild, test again

---

## Files

| File | What it is |
|------|-----------|
| `template.modelfile` | The annotated Modelfile template — start here |
| `SAMPLES.md` | How to find and choose your writing samples |
| `TESTING.md` | Standard prompts for evaluating your model |

---

## Further reading

Blog series at [wiobyrne.com](https://wiobyrne.com) — the posts walk through the thinking behind each decision in this template.
