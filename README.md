# Coach's AI Starter Kit — Skills

Two installable Claude skills from the Coach's AI Starter Kit by [Orin Learning Intelligence](https://orinlearning.com). They hand the busywork around a coaching session to AI so the coach can give the human part their full attention.

## The skills

**`session-prep`** — Turn cold prep into five minutes. Takes a coach's notes from recent sessions with one client and returns a tight brief: live threads, what's shifted, three questions to open with, and what the coach might be avoiding.

**`between-session-synth`** — Turn a messy session into a clean record and a warm follow-up. Takes raw session notes and returns two blocks: a private summary for the coach's records and a short client follow-up written in the coach's voice.

Both are pure time-savers. They don't track growth across a program or build an evidence portfolio over time. That work is what Orin does.

## Context files

The skills are sharper when they can read a coach's context files. They look for these in the project or working files and ask for them if missing:

- `session-prep` loads `about-me.md` and `how-i-coach.md`
- `between-session-synth` loads `how-i-coach.md` and `my-voice.md`

Build those four files once using the prompts in the starter kit, keep them in a Claude Project, and every skill reads them automatically.

## Install

**From a packaged file:** open a `.skill` file in `dist/` (Claude shows a "Save skill" button), or upload the zip in Claude's skill settings.

**From source:** each skill is a folder with a `SKILL.md`. Add the folder to your skills directory, or zip it and upload.

## Repo layout

```
coach-ai-skills/
├── README.md
├── session-prep/
│   └── SKILL.md
├── between-session-synth/
│   └── SKILL.md
└── dist/
    ├── session-prep.skill
    └── between-session-synth.skill
```
