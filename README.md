# agent-startup-kit

AI coding workflows and reusable skills for shipping SaaS fast.

Stop rebuilding the same auth, billing, landing, and deployment flows from scratch.

Use reusable workflows for Claude Code and VS Code, then ship faster with a more consistent process.

[Quickstart guide](./QUICKSTART.md)

Docs: [Quickstart](./QUICKSTART.md) · [Skills](./skills/README.md) · [Examples](./examples/README.md) · [Adapters](./adapters/README.md) · [Templates](./templates/README.md)

## Quick use

1. Open your project in Claude Code or VS Code.
2. Choose one skill:
   - `ship-auth`
   - `ship-billing`
   - `ship-landing`
3. Read the matching `skill.md` and `checklist.md`.
4. Review the matching before/after example in `examples/`.
5. Make changes in small steps.

## Why this project exists

Indie hackers and small engineering teams often repeat the same setup work again and again:
- authentication
- billing
- landing pages
- project structure
- workflow documentation
- review checklists

agent-startup-kit turns these repeated tasks into reusable AI coding workflows.

## Included skills

### ship-auth
Authentication workflow support for:
- sign up
- sign in
- forgot password
- email verification
- protected pages

### ship-billing
Billing workflow support for:
- pricing page
- checkout flow
- subscription status
- webhook handling
- success and cancel pages

### ship-landing
Landing page workflow support for:
- hero section
- feature section
- FAQ section
- CTA section
- SEO metadata

## Supported tools

### Current
- Claude Code
- VS Code

### Planned
- MCP

## Repository structure

- adapters/claude-code/
- adapters/vscode/
- skills/ship-auth/
- skills/ship-billing/
- skills/ship-landing/
- templates/nextjs-saas-starter/

## How to use

1. Open your project in Claude Code or VS Code.
2. Review the existing project structure first.
3. Choose one skill based on your current task.
4. Use the matching `skill.md` as working instructions.
5. Use the matching `checklist.md` to review the result.
6. Make changes in small steps.

## Included support files

Each skill currently includes:
- `README.md`
- `skill.md`
- `checklist.md`

This keeps each workflow simple, reusable, and easy to review.

## Current template target

- `templates/nextjs-saas-starter/`

This template path is intended as the baseline demo target for the included skills.

## Current adapters

- `adapters/claude-code/README.md`
- `adapters/vscode/README.md`

These explain how to use the skills inside each AI coding workflow.

## Examples

Current before/after example docs:
- `examples/before-after-auth/README.md`
- `examples/before-after-billing/README.md`
- `examples/before-after-landing/README.md`

These help users quickly understand what each skill is expected to change before reading the full skill files.

## Roadmap

### v1
- ship-auth
- ship-billing
- ship-landing
- Claude Code adapter
- VS Code adapter
- Next.js SaaS starter template

### Next
- ship-seo-blog
- ship-analytics
- ship-deploy
- MCP adapter
- more templates
- examples and before/after demos

## Contributing

Contributions are welcome.

Please read `CONTRIBUTING.md` before opening a pull request.

## License

MIT
