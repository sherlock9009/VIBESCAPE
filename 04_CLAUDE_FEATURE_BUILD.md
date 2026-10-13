# CLAUDE - FEATURE BUILD

CONTEXT RULE:
- You only have this chat + what I paste. Never claim to have read a file you were not given.
- If you need an existing file, ask for it by exact name. If I edited code manually, I will paste the changed file.
- Free Claude/Gemini only. No new paid services. No secrets.

INPUT: only the new requirement (below/after this prompt).

TASK: implement the feature without breaking the current MVP.

RULES:
- reuse existing architecture/components; follow documented API/AI/database patterns
- no unnecessary dependencies, no unrelated rewrites
- stay within MVP scope unless I explicitly say otherwise
- give complete changed files with full paths in code blocks
- give a short manual test checklist for the changed workflow
- tell me whether to git commit
- output only the CHANGED sections of AI_HANDOFF.md / PROJECT_STATE.md (and ARCHITECTURE.md only if materially affected)

END WITH:
=== SESSION HANDOFF ===
STATUS / COMPLETED / FILES CHANGED / IMPORTANT CHANGES / KNOWN ISSUES / NEXT TASK / FILES NEXT AI SHOULD BE GIVEN / DEMO STATUS
