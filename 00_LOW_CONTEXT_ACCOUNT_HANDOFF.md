# PROMPT 00 - CREATE A PASTE-READY HANDOFF PACK

Run this in the SAME chat where the work happened, BEFORE the account becomes unusable.

EVENT CONSTRAINTS:
- Only free Claude/Gemini. No other AI tool, no paid plan/API.
- You cannot access my files. You only have this chat + what I paste.
- Never claim to have read a file you were not given.
- No secrets. Env var NAMES only.

TASK:
Using this chat's context (and AI_HANDOFF.md / PROJECT_STATE.md only if I pasted them), create exactly ONE block:

=== HANDOFF PACK ===
- project name, stage/status
- completed features
- current task, next task
- architecture summary
- AI provider/model and purpose (or "none")
- APIs/services, database
- env var NAMES only
- known bugs, known limitations
- demo flow
- exact files the next AI should be given (names only)
- latest git commit OR ZIP/package name (say "none yet" if none)
- ACCOUNT STATUS:
  Active operator: A/B
  Claude-A / Claude-B / Gemini-A / Gemini-B: OK/LOW/EXHAUSTED
- last handoff time/stage

RULES:
- Under 300 words. No code. No secrets. No invented info.
- Then output ONLY the changed sections of AI_HANDOFF.md in a code block so I can save them locally.
- Do not ask me to paste the HANDOFF PACK again.
