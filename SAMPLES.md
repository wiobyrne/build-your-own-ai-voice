# Choosing Your Writing Samples

The samples in your Modelfile are the most important part of the whole system. Rules tell the model what to do. Samples show it what that actually looks like in your writing. If you get the samples right, the model will pick up patterns you didn't even think to name.

This document walks through how to find and select them.

---

## Step 1: Gather your candidates

Pull together 15–20 pieces of your published writing. Blog posts, newsletter issues, essays, long-form social posts — anything you wrote, edited yourself, and stand behind.

You are not looking for your best writing. You are looking for your most *characteristic* writing — pieces that, if a reader knew you well, they would immediately recognize as yours.

Avoid:
- Pieces written in a rush that don't represent your usual patterns
- Collaborative pieces where another voice is mixed in
- Very short pieces (under 300 words) — not enough texture
- Very old pieces if your voice has shifted significantly

---

## Step 2: Read them and take notes

Before picking samples, read the candidates and actively look for patterns. Write down what you notice.

Look for:
- **How you open paragraphs** — do you start with a claim, a scene, a question, a fact?
- **How you handle technical terms** — do you define them, link them, assume them?
- **What analogies you reach for** — physical, natural, historical, pop culture?
- **Your sentence rhythm** — long then short? consistently medium? lots of fragments?
- **What you never do** — things you instinctively avoid that others do freely
- **How you close** — do you return to the opening? zoom out? give a call to action?

The patterns you follow *without thinking* are the most important to name. If you have to deliberate about whether you do something, it's probably not a strong enough pattern to encode.

---

## Step 3: Pick samples that cover different registers

You need 3–5 samples. Each should cover a different mode of writing. If all your samples are the same register, the model will be one-dimensional.

Common registers to cover:

| Register | What it is | Example prompt it prepares the model for |
|----------|-----------|------------------------------------------|
| **Explanatory** | Making something complex accessible | "Explain what a large language model is" |
| **Argumentative** | Taking a position on something contested | "Write an intro arguing for open-source AI" |
| **Narrative / personal** | A story, a struggle, a reflection | "Write about a time a tool failed you" |
| **Practical** | Step-by-step, how something works | "Explain how to set up a local model" |
| **Closing / meaning-making** | Connecting a specific thing to a bigger idea | "Write a closing paragraph on why this matters" |

You don't need all five. Pick the ones that represent how you actually write. If you rarely write personal narrative, don't force a sample into that slot.

---

## Step 4: Select the passages

From each candidate piece, pick a passage of 100–250 words that best represents that register. You are looking for:

- Sentences that feel most like you
- Moments where your characteristic patterns are all present
- Writing you're proud of — not because it's showy, but because it's precise

Copy the passage verbatim. Do not clean it up or improve it for the Modelfile. The model needs to learn from the writing you actually produce, not an idealized version of it.

---

## Step 5: Write the negative example

Find a piece of writing that is the *opposite* of your voice. A paragraph is enough.

Good candidates:
- A marketing email you received
- A press release in your field
- A generic AI-generated blog post
- A corporate memo
- An academic abstract written in impenetrable jargon

The negative example helps the model calibrate. Without it, it only knows what to aim for. With it, it also knows what to avoid.

---

## A note on honesty

The hardest part of this process is reading your own writing without flinching. You will find patterns you didn't intend and habits you don't love. That's the point. The model learns from what you actually wrote, not what you meant to write.

If you find a pattern that surprises you, name it anyway. Encoding it gives you something concrete to change. Ignoring it just means the model will reproduce it faithfully.
