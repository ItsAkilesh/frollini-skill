<!--
File: README.md
Purpose: Overview and install instructions for the frollini writing-quality skill.
Author: Akilesh Srinivasa Kumar
Date: 2026-11-01
-->

# frollini

A Claude skill that makes AI-written prose read like a careful person wrote it: clear, direct, specific, and persuasive.

It gives the model a short workflow (know the reader, lead with the point, write with specifics, edit for plain style, remove AI patterns, verify facts) and a checklist of the patterns that give AI writing away, such as inflated vocabulary, "not just X but Y" contrasts, reflexive groups of three, significance padding, bold-label bullets, and chatbot sign-offs. Reference files cover emails, memos, executive summaries, proposals, slides, interview questions, and persuasion.

## Layout

```
frollini/
  SKILL.md        workflow, AI-pattern checklist, style rules, review guide
  references/     detailed notes, loaded only when needed
```

## Install

```bash
cp -r frollini ~/.claude/skills/frollini
```

Then type `/frollini`, or ask for help writing or editing something and the skill loads on its own.

## Sources

- Wikipedia, "Signs of AI writing" (WikiProject AI Cleanup), licensed CC BY-SA 4.0. Summarized and paraphrased in `references/ai-writing-tells.md`.
- Deborah J. Barrett, *Leadership Communication* (4th ed., McGraw-Hill). Paraphrased chapter notes.
- Lecture material from CMU 17-603, Communications for Software Leaders (Nick Frollini). Paraphrased.

No original slides, textbook pages, or course files are included. Because much of the content comes from copyrighted course material, keep the repository private unless you have permission to share it.
