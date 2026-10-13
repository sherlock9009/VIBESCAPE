# CLAUDE - AI FEATURE / INTEGRATION

USE ONLY IF organizers allow the app itself to call an AI API. If unsure, do not use this prompt.

CONTEXT RULE:
- You only have this chat + what I paste. Never claim to have read a file you were not given; ask by exact name.
- Use the AI provider/model already documented in the build spec. Do not ask me to repeat it.
- If that provider needs a paid plan or a card, STOP and tell me. Do not switch to ChatGPT/OpenAI or any other tool.
- Only Claude/Gemini free tiers are allowed in this event.

TASK: implement or improve the required AI feature.

RULES:
- minimize model calls
- API key only via environment variable (name only in docs; never in code or Git)
- use structured output and validate it
- handle timeout, rate-limit, invalid-output and provider failures
- provide a graceful fallback so the demo never breaks
- preserve existing UX
- complete changed files with full paths in code blocks
- short manual test checklist; tell me when to git commit
- output only changed sections of the memory files

END WITH:
=== SESSION HANDOFF ===
STATUS / COMPLETED / FILES CHANGED / AI CHANGES / API-ENV CHANGES / KNOWN ISSUES / NEXT TASK / DEMO STATUS
