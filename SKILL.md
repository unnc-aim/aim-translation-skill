---
name: bilingual-translation
description: Translate between Chinese and English while consistently applying a user-maintained bilingual glossary.
---

# Chinese-English translation

Use this skill when translating text between Chinese and English. Follow the prompt in [prompt.md](prompt.md) and consult [glossary.json](glossary.json) for every translation.

Treat glossary entries as binding for matching proper nouns and expressions. Prefer the listed target term over an otherwise natural alternative. Use each entry's context and aliases to identify matches; do not force a term onto a different meaning. Preserve the source meaning, tone, formatting, and structure around glossary-mandated terms.

The glossary is a reusable starter. Add project-specific terms to its `terms` array using the documented field pattern in the file. If no glossary entry applies, translate naturally and consistently without inventing a glossary rule.
