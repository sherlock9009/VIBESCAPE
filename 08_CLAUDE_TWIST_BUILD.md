# CLAUDE - TWIST BUILD

CONTEXT RULE:
- You only have this chat + what I paste. If this is a new chat/account, I will paste HANDOFF PACK + AI_HANDOFF.md + PROJECT_STATE.md first.
- Never claim to have read a file you were not given; ask for the files named in the Twist instruction by exact name.

INPUT: only === CLAUDE TWIST INSTRUCTION ===.

TASK: implement the Twist with minimum risk.

RULES:
- implement CRITICAL requirements first
- do not spend time on OPTIONAL items unless the core Twist is already reliable
- preserve the original MVP; reuse existing architecture
- no unnecessary dependencies or refactors
- complete changed files with full paths in code blocks
- give a manual test checklist for BOTH the original workflow and the Twist workflow
- tell me when to git commit (commit BEFORE starting the Twist as a safe restore point)
- output only changed sections of the memory files
- freeze scope once the Twist is reliable

END WITH:
=== FINAL TWIST HANDOFF ===
TWIST STATUS / COMPLETED / FILES CHANGED / ORIGINAL MVP VERIFIED / TWIST VERIFIED / KNOWN ISSUES / DEMO STATUS / NEXT TASK
