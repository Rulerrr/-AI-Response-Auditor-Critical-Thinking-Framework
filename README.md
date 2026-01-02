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

## The "Personalisation Trap" (Pro Tip)

During my experiments, I discovered a strange paradox: LLMs are often more objective in Guest Mode (Incognito).

* **The Problem:** Personalised profiles push the machine into a "Sycophancy Trap." The LLM tries to be "helpful" by guessing your intent, which leads to logical contamination.
* **The Evidence:** In a personalised chat, the LLM saw one keyword and immediately hallucinated the semantics just to please the user. In Guest Mode, the same LLM correctly identified the lack of context and asked for details.
* **The Strategy:** Use Guest Mode to establish a **Logical Baseline**. In this mode, the LLM usually performs at an 8/10 or 10/10 level by default because it cannot build a bias without your history. 
* **The Auditor's Role:** If you must work in a personalised profile, this Auditor framework becomes a necessary "correction fluid" to scrub away the LLM's biased assumptions and bring the logic back to the Guest Mode standard.

---

## License

This project uses the **MIT License**. You are free to share it, but please keep the author's name.

**Author:** Ruslan Krucheniuk
**Location:** Málaga, Spain
**Year:** 2026

*Stop believing everything the machine says. Start auditing.*
