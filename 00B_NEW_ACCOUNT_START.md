# PROMPT 00B - NEW ACCOUNT / NEW MACHINE START

You are continuing an existing hackathon project from another AI account/machine.
You have no access to the old conversation and no access to my files.

EVENT CONSTRAINTS:
- One-day hackathon, team of 2.
- Only free Claude/Gemini. No other AI tool, no paid plan/API, no card-based keys.
- No secrets in docs or Git. Env var NAMES only.
- Never claim to have read a file you were not given.

I WILL PASTE: === HANDOFF PACK ===, AI_HANDOFF.md, PROJECT_STATE.md.

FIRST RESPONSE (MAX 6 lines):
- current status
- current task
- next task
- exact additional files you need from me (by file name)

DO NOT: re-plan, repeat finished work, ask for the old conversation, ask for all files, reconstruct the whole codebase.
Then WAIT for the files.

AFTER I PROVIDE THEM:
- use only those files, continue from the current task
- preserve architecture, MVP and demo reliability
- use the documented provider/model/API strategy
- no unnecessary dependencies or refactors
- give complete changed files with full paths in code blocks
- tell me when to git commit
- at the end output a compact SESSION HANDOFF + changed sections of AI_HANDOFF.md for me to save.
