---
name: feynman-deep-learning
description: Turn articles, book chapters, notes, PDFs, concepts, and research material into structured understanding through Feynman explanations, gap diagnosis, examples, boundaries, applications, active recall, and reusable knowledge cards. Use when the user wants to learn, digest, explain, review, or test understanding of material; do not use for a simple summary unless deeper learning is requested.
---

# Feynman Deep Learning

Convert material from something the user has merely seen into knowledge they can explain, test, apply, and retain. The target is not exhaustive coverage; it is accurate, transferable understanding.

## Calibrate the Learning Task

Infer the learner's goal, likely background, desired depth, and available material from context. Proceed with reasonable assumptions when they do not change the task materially. Ask only when the source itself is missing or a choice would substantially change the result.

For long or uneven material, prioritize the small set of ideas that determines understanding of the whole. Usually select 3–7 core ideas rather than mirroring every section.

## Run the Learning Loop

1. **Extract** — Identify the central topic, questions, claims, facts, causal links, methods, prerequisites, and easily missed qualifications. Remove repetition, rhetoric, and low-value detail.
2. **Structure** — Build a knowledge map instead of a flat list. Mark relations such as prerequisite, cause, contrast, containment, consequence, failure condition, and application.
3. **Explain** — Restate each core idea for an intelligent beginner. Cover what it is, why it holds, how it works, what problem it solves, and how it connects to the other ideas. Define necessary terminology before using it.
4. **Challenge** — Look for signs of shallow understanding: repeated definitions, unexplained jargon, missing causes, no concrete example, or inability to handle a changed situation.
5. **Fill gaps** — Classify important gaps as concept, principle, relationship, application, or boundary gaps. State the missing prerequisite, what should be learned, and then re-explain the idea after supplying the minimum needed foundation.
6. **Apply** — Give at least one concrete example for each important idea. Add an analogy when useful and say where it breaks. Include a counterexample, limitation, or failure condition for the most consequential ideas.
7. **Test** — Prefer active-recall questions about explanation, causality, application, and transfer over recognition or definition recall. Do not immediately reveal answers unless the user requests them.
8. **Consolidate** — Produce a reusable knowledge card and compress the result into a full version, a review version, and a one-sentence memory.

Stop drilling when the learner can explain the idea accurately and use it in a new situation. Do not pursue endless “why” chains that no longer improve those outcomes.

## Preserve Accuracy

- Explain in original, simple language; do not replace understanding with copied definitions or large excerpts.
- Keep simplification faithful. Name important assumptions and causal links rather than hiding them.
- Distinguish what the supplied material supports from added background knowledge or inference.
- If the evidence is insufficient, say `当前材料不足以确定` and identify what would resolve the uncertainty.
- Do not invent facts, citations, examples presented as real events, or the learner's personal blind spots. Frame predicted blind spots as likely risks until the learner's answers confirm them.

## Select the Operating Mode

### Default: Deep Learning Output

Read [references/deliverables.md](references/deliverables.md). Use the complete structure for substantial material, but collapse empty or redundant sections for narrow concepts. Depth should follow the material and the user's goal, not a fixed word count.

### “考考我” or Quiz Mode

Read [references/coaching.md](references/coaching.md). Ask one question at a time, wait for the answer, diagnose it, and adapt the next question. Favor levels 2–5.

### “我没懂” or Re-explanation Mode

Read [references/coaching.md](references/coaching.md). Do not repeat the same explanation. Reduce jargon, use a more concrete example, try an analogy with its limit, supply missing prerequisites, and then check understanding.

### “继续深挖” or Deep-Dive Mode

Move through `Why → How → Boundary → Application`. Go one layer deeper at a time and keep the new detail connected to the core model.

### “帮我复习” or Review Mode

Begin with active recall rather than showing the full notes. Ask one high-value question at a time, use the learner's answers to target weak links, and reveal a compact review only after retrieval practice or when requested.

## Quality Gate

Before finishing, check that the result:

- identifies the questions that organize the topic;
- shows relationships rather than only listing facts;
- explains why and how in plain language;
- includes examples plus meaningful boundaries;
- distinguishes demonstrated gaps from anticipated risks;
- offers at least one application or transfer task;
- leaves the learner with unanswered recall questions and a compact knowledge asset.
