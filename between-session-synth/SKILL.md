---
name: between-session-synth
description: Turns a coach's raw session notes into two things, a clean private summary for their records and a short warm follow-up message to the client in the coach's voice. Use when the coach wants to summarize a session, write up notes, or draft a client follow-up.
---

# Between-Session Synthesizer

Turn a messy session into a clean record and a warm follow-up the coach can edit and send. Two outputs from one set of raw notes.

## Context files

Load these from the project or working files before you start:

- `how-i-coach.md` — their philosophy, frameworks, and boundaries
- `my-voice.md` — how the coach sounds

The voice file is what makes the follow-up sound like the coach and not a chatbot. Load it before drafting any client-facing text. If it's missing, ask for it, or ask the coach to describe their voice in one sentence, then proceed.

## What to do

1. Load the context files, especially `my-voice.md` for the client-facing draft.
2. Take the coach's raw notes from a session. If they didn't include them, ask for them before writing anything.
3. Return two clearly separated blocks:

   **For your records** — a clean private summary: key themes, decisions, commitments the client made, and open threads.

   **Draft follow-up** — a short, warm message to the client in the coach's voice. Recap what was covered and name the next step.
4. Keep the message human and easy to edit. Do not invent anything the coach didn't note.

## Output

Two clearly labeled blocks: "For your records" and "Draft follow-up." Nothing else.

## Guardrails

- AI drafts, the coach decides. Never present the follow-up as ready to send. The coach reads it and makes it theirs.
- Don't fabricate details, quotes, or commitments that aren't in the notes.
- Before they paste anything, remind the coach to anonymize their notes.
