# Claude Skill: WebDesigner

A premium, production-oriented Claude skill package for high-end web design tasks.

This repository provides a structured skill definition that helps Claude behave like a senior web designer focused on:
- premium UI/UX direction
- responsive layouts
- conversion-aware structure
- elegant visual hierarchy
- mobile-first execution
- modern web copy guidance
- component planning for real business websites

## What this skill does

When loaded into a Claude-compatible workflow, the `webdesigner` skill instructs the model to:
- think like a senior web designer and UX strategist
- propose polished section layouts before writing code
- prioritize spacing, hierarchy, readability, and conversion
- keep mobile optimization active by default
- avoid generic, cheap-looking template decisions
- maintain brand consistency across pages
- produce cleaner, more premium website recommendations

## Recommended use cases

- landing pages
- service websites
- premium beauty brands
- luxury ecommerce concepts
- agency websites
- portfolio websites
- homepage redesigns
- section-level UI improvements
- style system planning
- CTA optimization

## Repository structure

```text
claude-skill-webdesigner/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── skill.json
├── system-prompt.md
├── examples/
│   ├── example-request-1.md
│   ├── example-request-2.md
│   └── example-output-outline.md
├── docs/
│   ├── installation.md
│   ├── usage.md
│   ├── design-principles.md
│   └── quality-checklist.md
└── assets/
    └── repo-description.txt
```

## Quick start

1. Copy the contents of `system-prompt.md` into your Claude skill loader, agent instruction layer, or system prompt wrapper.
2. Optionally parse `skill.json` programmatically if your workflow routes skills dynamically.
3. Use the examples in `examples/` to test output quality.
4. Keep this skill loaded only for design-oriented tasks to reduce prompt bloat.

## Positioning

This is not a code framework.  
It is a **behavior package** for Claude that makes web-design output more structured, premium, and useful in real-world workflows.

## Example prompt

> Use the `webdesigner` skill. Create a premium homepage structure for a luxury nail salon with strong mobile UX, elegant hierarchy, and persuasive Romanian copy.

## Notes

- Works best when combined with a separate code-generation skill.
- Best results come from pairing it with clear brand inputs: audience, offer, tone, and desired visual direction.
- Keep feedback iterative: first structure, then copy, then polish, then implementation.

## Authoring goal

This repository is designed to look credible, useful, and practical for open-source AI workflow ecosystems.

## Updates

- Initial version of the webdesigner skill
- Active development and improvements
