# Product & conversation design

## Problem framing

The project began as a chatbot that could discuss AI ethics. The creator’s reflection identifies a more specific goal: give learners practice defending reasoning instead of simply receiving an explanation.

The intended experience centers on a claim, a challenge, justification, ethical or policy complexity and reflection.

## Key design decisions

| Decision | Intended benefit | Product trade-off |
| --- | --- | --- |
| Challenge before giving a broad explanation | Encourage users to reason before consuming an answer | Too much opposition can become discouraging |
| Target four to five rounds | Provide progression and a clear endpoint | A fixed budget may not fit every learner or topic |
| End with reflection | Make changes in reasoning explicit | Reflection needs useful prompts, not a generic closing |
| Draw on a curated knowledge base | Ground arguments in a defined content scope | Retrieval relevance and source freshness need evaluation |
| Supportive Socratic tone | Preserve rigor while sustaining engagement | Prompt instructions alone may not ensure consistent tone |

## Knowledge-base rationale

The creator selected an AI Ethics Debate Bot document to organize governance, fairness, bias, misinformation and ethical issues. Policy cases were intended to make abstract questions concrete.

Bozkurt’s work on generative AI literacy was included for its **3W framework: Know What, Know How, Know Why**. These categories provide a conceptual reference for understanding AI, using it and questioning its implications.

The original knowledge files, exact publication reference, chunking settings, retriever configuration and retrieval logs were not supplied. These details remain separate from the product design documented here.

## Iteration described in the creator’s reflection

1. **Information bot → debate coach:** shift the main interaction from explanation to defending a claim.
2. **Unbounded conversation → four-to-five-round target:** introduce a progression that culminates in reflection.
3. **Rigid / confrontational replies → supportive challenge:** adjust personality and rules to retain intellectual pressure without dismissing the learner.
4. **Abstract argument → policy examples:** use source materials to introduce concrete dilemmas and governance trade-offs.

These are qualitative observations and design responses reported by the creator. Sample size, recorded transcripts and measured learning outcomes have not been supplied.

## Portfolio implementation

The public project page organizes the product decisions and links to the live Odin embed, prompt specification, evaluation plan and creator-provided lesson plan. It does not modify the deployed agent or claim an independently built LLM backend.
