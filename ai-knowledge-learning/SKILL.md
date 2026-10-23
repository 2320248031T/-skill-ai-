---
name: ai-knowledge-learning
description: Use when a learner has a document corpus, source repository, course, or broad new topic and asks where to start, how materials connect, how to learn it step by step, or how to verify practical understanding.
---

# AI Knowledge Learning

Turn a supplied knowledge corpus into a learner-sized route, then teach from that route with traceable evidence. The reusable method is broad-to-deep, source-aware, and adaptive; the domain's actual dependencies determine the stages.

## Use this skill when

- A learner asks where to begin, how documents relate, or how to learn a domain end to end.
- A learner says the material feels too broad, scattered, technical, or hard to follow.
- A learner wants a roadmap or flowchart (Markdown, Mermaid, XMind, or another requested format).
- A learner wants to check whether they can use the knowledge, not only recite terms.

Do not turn a narrow factual question into a full course. Answer the question at the requested scope and cite the source.

## Workflow

1. **Honor the learning goal and mode.** Reuse preferences already given. If the learner asks for a map first, give the whole map before detail. If they ask for a complete explanation, do not force a quiz or a question-by-question format. Do not inflate a narrow factual question into a course.
2. **Inventory the actual corpus.** Read workspace instructions, navigation files, headings, and relevant passages. Group overview, core teaching, lookup-only, archive, implementation, and runtime-validation materials. Never infer content from filenames alone. For large corpora, map every collection and inspect representative/dependency-critical files; state what was not read individually.
3. **Build a source-grounded knowledge graph.** Identify concepts, prerequisites, dependencies, cross-document relationships, evidence level, and learner outcomes. Separate why/what from how implemented. Do not copy a table of contents as the learning route unless it is pedagogically ordered.
4. **Sequence broad-to-deep stages.** Usually begin with source boundaries and the whole-system picture, then core concepts and relationships, workflows, representative cases, application, and validation. Change order when actual dependencies or learner preferences call for it.
5. **Make each stage actionable.** State its purpose, exact reading links, what to understand, one concrete example/practice, observable output, lookup-only material, and pass criterion. Keep related ideas together and limit new terminology per lesson.
6. **Teach with traceable evidence.** Link factual explanations to exact files/headings/lines or authoritative external sources. Label source facts, teaching paraphrases, inferences, and unverified behavior. If evidence is missing, name what must be checked next.
7. **Adapt from feedback.** When content feels too large, simplify the relationship and example, not the learner's goal. Answer follow-up questions directly, then resume the map. Avoid repetitive binary choices and pointless checks.
8. **Validate application, not recitation.** Increase depth across concept boundaries, workflow tracing, cross-system relationships, tradeoffs, source/evidence use, and a practical artifact. Use multiple checks; report strengths, omissions, confusions, and evidence gaps separately.

## Deliverables

- For a roadmap: provide a flowchart or mind map, stage-by-stage reading links, goals, practice/output, and pass criteria. If XMind is requested, produce an editable `.xmind` plus a readable Markdown companion when useful; verify the archive and, when the app is available, open it and inspect the rendered content.
- For ongoing study: each lesson names its place in the route, teaches the requested scope, gives a concrete example, and cites its source.
- For completion: distinguish “curriculum covered” from “independent application verified.”

Use [references/roadmap-contract.md](references/roadmap-contract.md) for the stage schema, reusable validation rubric, and evidence labels.
