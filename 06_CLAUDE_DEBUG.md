# CLAUDE - DEBUG / ROOT-CAUSE FIX

CONTEXT RULE:
- You cannot see my code. You only have this chat + what I paste.
- I will paste: (1) the exact error/stack trace/problem, (2) the relevant file or function, (3) what I did just before it broke.
- If you need another file, ask for it by exact name. Do not guess its contents.

TASK: find the root cause and apply the minimum safe fix.

RULES:
- no unnecessary rewrite, no architecture replacement, no unrelated changes
- no new dependency unless required
- check obvious regression risk
- give only the changed code (with file path) in a code block
- give a short test to confirm the fix
- if the cause is external config/service, state the exact manual action
- tell me if I should git commit; if the fix fails, tell me how to revert

END WITH:
=== DEBUG HANDOFF ===
ROOT CAUSE / FIX / FILES CHANGED / TEST TO RUN / KNOWN ISSUES / NEXT TASK
