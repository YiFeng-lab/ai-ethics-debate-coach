# AI Ethics Debate Coach

**Generative AI literacy · Conversation design · Structured debate**

[Product case →](https://yifeng-lab.github.io/ai-ethics-debate-coach/) · [Try the coach →](https://yifeng-lab.github.io/ai-ethics-debate-coach/debate.html) · [Original demo →](https://jarosenblum.github.io/Odin/yi-1.html)

## Product goal

Help learners practice reasoning about AI ethics and governance by defending a position, examining counterarguments and reflecting on how their thinking changes.

The coach uses a debate-first, Socratic approach. Its prompt design targets **four to five rounds**, ending with reflection rather than an indefinitely extended argument.

## My contribution

- Defined the debate coach’s role, tasks, requirements and instructions using an RTRI structure.
- Designed the conversation progression: initial claim → challenge → justification → ethical / policy trade-offs → reflection.
- Selected knowledge-base materials on AI governance and generative AI literacy.
- Iterated personality and interaction rules in response to early qualitative observations of rigid or confrontational replies.
- Connected the tool with a learning-activity plan and a web embed.

## Design materials

| File | What it shows |
| --- | --- |
| [PROMPT.md](PROMPT.md) | Role, task, requirements and instructions supplied for the agent |
| [DESIGN.md](DESIGN.md) | Problem framing, knowledge choices, iteration and product trade-offs |
| [EVALUATION.md](EVALUATION.md) | Proposed checks; this is a plan, not completed benchmark results |
| [Linked lesson plan](https://docs.google.com/document/d/1NeaM5EjIYPxuGoMmmTevyBwGYawtsf-4zVGdTja0Mg4/edit?usp=sharing) | Creator-provided teaching activity document |

## Implementation & evidence

The chatbot is hosted on **Odin AI**. This repository contains a static product-case page, an embed wrapper and design documentation; it does not implement a new model backend.

The creator describes a RAG-based design using an AI Ethics Debate Bot knowledge document and Bozkurt’s generative AI literacy work. The knowledge documents, retrieval configuration and retrieval logs have not been supplied in this repository.

“Fine tuning” in the source reflection is documented here as **prompt, personality and rule iteration**. No model-weight training evidence or quantitative user-impact results are supplied.

## Run locally

Open `index.html` for the product case and `debate.html` for the embed. The live chat depends on Odin AI availability and project access. The external links remain available if embedding does not work.

The supplied embed was checked against the existing `jarosenblum/Odin/yi-1.html` source. The lesson-plan link is preserved; its document body has not yet been inspected for this portfolio edition.
