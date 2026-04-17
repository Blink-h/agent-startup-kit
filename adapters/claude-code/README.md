# Claude Code adapter

This adapter explains how to use agent-startup-kit skills inside Claude Code.

## Supported skills
- ship-auth
- ship-billing
- ship-landing

## Recommended workflow
1. Open your project in Claude Code.
2. Review the existing project structure first.
3. Choose one skill based on the task.
4. Paste the skill instructions into the working context.
5. Ask Claude Code to inspect before changing files.
6. Generate changes in small steps.
7. Review the result with the matching checklist.

## Notes
- Prefer one skill at a time.
- Keep project-specific secrets out of prompts.
- Clearly mark missing environment variables or manual setup steps.
