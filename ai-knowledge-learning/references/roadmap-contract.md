# Learning Roadmap Contract

Use this reference when producing a substantial route or validating mastery. It is a contract for useful outputs, not a fixed syllabus: adapt branches to the materials and learner.

## Roadmap structure

```text
Learner outcome
  -> source inventory and boundaries
  -> whole-system map
  -> prerequisite concepts and workflows
  -> representative cases
  -> practical application
  -> multi-dimensional validation
```

For each stage, state:

| Field | Required content |
|---|---|
| Purpose | Why this stage comes here and what problem it solves |
| Read | Exact local file + heading/line, or direct authoritative source |
| Learn | A small set of concepts and relationships, not a term dump |
| Example/practice | A concrete task that makes the concepts observable |
| Output | What the learner should be able to explain, map, decide, or create |
| Gate | Observable evidence to proceed; do not use a trivial recall question as the sole gate |
| Lookup-only | Large indices, enums, archives, or implementation details not worth memorizing |

Include cross-links where topics interact. Make the main path visible separately from optional reference branches. If the user requests a flowchart/XMind, keep the numbered stage order visible and attach source names to stages so the map remains actionable.

## Evidence labels

- **Source fact:** directly stated in the provided document/data or visible in cited code.
- **Teaching paraphrase:** simplified wording preserving the source meaning.
- **Inference:** a conclusion drawn by connecting sources; say what supports it.
- **Unverified:** missing source data, runtime behavior, version confirmation, or test evidence.

Link citations as close as practical to the claim. For local files, use clickable absolute-path links and heading/line where available. For external sources, use direct source URLs and pin a commit when the task needs reproducibility. Do not cite a title or index as proof of details it only points toward.

## Learning and verification

Adapt depth to learner preference. A broad-first learner receives the full map before a detail lesson. A confused learner gets fewer concepts per explanation, with plain language, terminology labels, one concrete example, and source links. A learner asking for an all-at-once summary gets that summary; do not force interactive questions.

When verifying practical understanding, combine several dimensions and increase difficulty:

1. **Concept boundaries:** distinguish neighboring terms that are often conflated.
2. **Process tracing:** follow inputs through a real workflow and identify where state changes.
3. **Relationship reasoning:** connect documents/systems and explain ownership or timing.
4. **Tradeoffs:** predict benefits, costs, failure cases, and downstream effects.
5. **Evidence use:** find supporting sources and mark inference or missing runtime proof.
6. **Application:** produce a case analysis, design, decision, or other artifact aligned to the learner's goal.

Use more than one prompt/task. Diagnose omissions and term confusions without treating every imperfect phrase as lack of understanding. Conclude separately on curriculum coverage, demonstrated competence, and unresolved evidence.

## Reuse boundary

The method is reusable across domains: inventory sources, map prerequisites and relationships, order a route, teach with traceable evidence, and verify application. The content taxonomy, evidence standard, tools, and test rubric are domain-specific and must be rebuilt from the new corpus rather than copied from a prior course.
