# Quickstart

If you want to try this without reading the whole repo first, use this path.

## 1. Install Ollama

Download and start [Ollama](https://ollama.com) if you do not already have it.

## 2. Pick a base model

Start with one of these:

- `mistral` if you want something simple and light
- `llama3` if you want a strong general-purpose base
- `qwen2:14b` if you have more RAM and want stronger style follow-through

## 3. Collect a few writing samples

Choose 4-6 pieces of your own writing that actually sound like you.

Good samples are:

- blog posts
- newsletter issues
- essays
- public reflections

Do not pick your most polished work just because it is polished. Pick work that is representative.

## 4. Fill out the template

Open `template.modelfile` and replace the placeholders with:

- your name
- your topics
- your audience
- your writing rules
- your sample passages
- one negative example

## 5. Build the model

```bash
ollama pull mistral
ollama create yourname-writer -f yourname-writer.modelfile
ollama run yourname-writer
```

## 6. Test it

Run the prompts in `TESTING.md`.

If the model sounds too generic, add better samples.
If it sounds too stiff, loosen the rules and improve the samples.
If it sounds like you but worse, keep refining the sample selection.

## What to remember

- Samples matter more than clever instructions
- Your voice is the goal, not perfection
- Testing is what tells you whether the model is actually improving

