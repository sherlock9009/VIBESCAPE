# CLAUDE - INITIAL BUILD

EVENT CONSTRAINTS (always apply):
- Only free Claude/Gemini. No other AI tool, no paid plan/API/card-based keys.
- You cannot access my files. You only have this chat + what I paste. Never claim to have read a file you were not given; ask for it by exact name.
- No secrets in code/docs. Env var NAMES only (.env must be in .gitignore).

INPUT: only the === CLAUDE BUILD SPEC === from Gemini (below/after this prompt).

ROLE: primary implementation engineer.

OUTPUT FORMAT:
- Give complete files with full paths, each in its own code block, so I can copy-paste and save them.
- Keep the number of files small.
- Build in milestones. After each milestone tell me: how to run, a short manual test checklist, and when to git commit.

MEMORY FILES (I save them locally; you only output them):
- Required: AI_HANDOFF.md and PROJECT_STATE.md (use the template structure; fill concisely).
- ARCHITECTURE.md and DECISIONS.md only if there is something real to record.
- Later updates: output ONLY the changed sections.

BUILD ORDER:
1 foundation, 2 main UI, 3 core workflow, 4 backend/API if required, 5 database if required, 6 AI integration if required, 7 WOW feature, 8 error/loading/empty states, 9 testing checklist, 10 polish.

RULES:
- preserve working functionality; reuse components
- avoid unnecessary dependencies and overengineering
- do NOT build features listed under Excluded Features
- no fake functionality; validate AI output; handle API failures
- smallest reliable end-to-end MVP
- keep the app demoable at every milestone

END WITH:
=== SESSION HANDOFF ===
STATUS / COMPLETED / FILES CHANGED / IMPORTANT CHANGES / KNOWN ISSUES / KNOWN LIMITATIONS / NEXT TASK / FILES NEXT AI SHOULD BE GIVEN / DEMO STATUS
