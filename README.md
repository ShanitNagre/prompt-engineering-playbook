# 🎯 Prompt Engineering Playbook
### For AI PMs in Regulated Industries

> A living library of prompt patterns, anti-patterns, and domain-specific techniques built from shipping AI products across HealthTech and FinTech.

**Author:** Shanit Nagre — AI Product Manager

---

## Contents

| Section | Description |
|---------|-------------|
| `PLAYBOOK.md` | Full pattern library with examples |
| Healthcare Prompts | Claims scrubbing, denial appeals, ERA extraction |
| FinTech Prompts | AML narratives, credit explanations, KYC anomaly detection |
| Anti-Patterns | 5 common prompt mistakes in regulated products |
| Eval Prompts | Judge prompts for scoring model outputs |
| Version Control | How to track prompt changes like code |

---

## Key Patterns

1. **Structured Extraction with Schema Enforcement** — force JSON output for parseable results
2. **Confidence-Gated Output** — built-in human-in-the-loop triggers
3. **Chain-of-Thought for Compliance** — audit trail built into the prompt
4. **Adversarial Validation** — 5 tests to run before any prompt goes to production

---

## Why This Matters

In regulated industries, a bad prompt isn't just a bad user experience — it's a compliance risk. A prompt that hallucinates a denial reason causes incorrect appeals. A prompt that misclassifies risk tier causes regulatory exposure.

This playbook documents the patterns that actually work in production, not in demos.

---

*Part of Shanit Nagre's AI PM portfolio — [shanitnagre.github.io](https://shanitnagre.github.io)*
