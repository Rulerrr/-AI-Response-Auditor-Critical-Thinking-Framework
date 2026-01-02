# LLM Response Auditor: The Critical Thinking Tool

Developed by **Ruslan Krucheniuk** | Málaga, Spain

## What is this?

SaaS LLM (commercial LLM and further just LLM to simplify the text) is like a very smart student who wants to please the teacher (due to the nature of SaaS design). Sometimes, the LLM gives a "safe" or "nice" answer instead of the truth. This is called a "polite hallucination." 

This document is a "lie detector" for LLM. It uses logic and scientific facts to find mistakes in how the LLM thinks. If the LLM is being too diplomatic or using bad logic, this tool will catch it.

---

## How to use it

To audit an LLM response, you have two pragmatic options:

### Option A: The Fast Way (Attach File)
1. Download the [PROMPT.md](./PROMPT.md) file from this repository.
2. Attach (upload) the file to your LLM chat.
3. Send this command: **"Read the attached file and use its framework to audit your previous response."**

### Option B: The Manual Way (Copy-Paste)
1. Open [PROMPT.md](./PROMPT.md) and copy all text.
2. Paste it into the chat.
3. Send this command: **"Apply this framework to your previous answer."**

The LLM will then scan its own text for paradoxes like **Braess** or **Goodhart** and sophisms like the **False Golden Mean** and give you a score from 0 to 10.

---

## What does it check?

The auditor looks for common traps like:

* **The Nice Middle (False Golden Mean):** When the LLM tries to find a middle point between a fact and a lie.
* **The Efficiency Trap (Braess Paradox):** When a "better" road actually creates more traffic jams.
* **The Metric Game (Goodhart's Law):** When the LLM cares more about looking good than being right.
* **Wrong Cause (Post Hoc):** When the LLM thinks that because B happened after A, then A caused B.
* **Survivor Bias:** When the LLM only talks about success and ignores failure.

---

## Why it works

This framework forces the LLM to be "intellectually brutal" with itself. It stops the LLM from being a "pleaser" and turns it into a "logic auditor". It is based on principles from Socrates, Aristotle, and modern systems science.

---

## ⚠️ Professional Warning: The SaaS Reward System

Why is an audit mandatory? Most of SaaS LLMs are engineered with a "pleaser" bias.

* **The Conflict:** Developers optimise these models to be helpful and satisfying to the paying user. This creates a reward system where the SaaS LLM is encouraged to guess your intent and mirror your biases to provide a "pleasant" experience.
* **The Systemic Flaw:** A system designed for user satisfaction is fundamentally incapable of self-detecting hallucinations. It cannot distinguish between a factually sound response and a "pleasing" one if both satisfy the user's implicit bias.
* **The Solution:** Treat the LLM as a sophist, not an oracle. This Auditor framework acts as a manual override, forcing the model into an "intellectually brutal" state that the commercial reward system usually suppresses.

**If you don't audit the logic path, you are not testing the LLM; you are simply consuming its hallucinations.**

---

## License

This project uses the **MIT License**. You are free to share it, but please keep the author's name.

**Author:** Ruslan Krucheniuk
**Location:** Málaga, Spain
**Year:** 2026

*Stop believing everything the machine says. Start auditing.*
