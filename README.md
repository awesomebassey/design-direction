# design-direction

An installable design skill for AI coding agents.

`design-direction` helps agents build better product interfaces by grounding design work in real references, production constraints, motion taste, mobile polish, component-library awareness, and adversarial UI checks.

It is intentionally portable. The canonical skill lives in [`skill.md`](skill.md), with an installable Codex entrypoint in [`SKILL.md`](SKILL.md) and adapters for popular agent environments in [`adapters/`](adapters/).

## What It Helps With

- Turning vague UI requests into a clear design direction
- Choosing appropriate inspiration sources before inventing from memory
- Picking component and motion libraries with restraint
- Designing production screens, not decorative landing-page filler
- Making web apps feel better on mobile
- Testing layouts against messy real-world data
- Reviewing interface quality with concrete fixes

## Install

For any LLM or coding agent, copy or reference [`skill.md`](skill.md) as the primary instruction file.

For Codex-compatible skill installation, use the repository root because it includes [`SKILL.md`](SKILL.md).

Platform-specific entrypoints:

- Codex: [`adapters/codex/SKILL.md`](adapters/codex/SKILL.md)
- Claude: [`adapters/claude/skill.md`](adapters/claude/skill.md)
- Cursor: [`adapters/cursor/rules.md`](adapters/cursor/rules.md)
- OpenAI custom instructions / GPTs: [`adapters/openai/instructions.md`](adapters/openai/instructions.md)
- Gemini: [`adapters/gemini/gemini.md`](adapters/gemini/gemini.md)

## Repository Structure

```text
.
|-- skill.md                  Canonical portable skill
|-- SKILL.md                  Codex-compatible entrypoint
|-- llms.txt                  Agent-readable repo map
|-- prompts/                  Task-specific prompt entrypoints
|-- references/               Growing design library and checklists
|-- adapters/                 Thin wrappers for agent platforms
|-- .github/                  Contribution templates
|-- CONTRIBUTING.md           How to add references and corrections
`-- GOVERNANCE.md             How the library stays curated
```

## Living Library

This skill is meant to improve over time. Additions should be small, sourced, and useful to agents making design decisions.

Good contributions include:

- A reference site with a clear use case
- A design heuristic that prevents a common agent mistake
- A component library with license and framework notes
- A mobile or accessibility edge case
- A motion principle with practical implementation guidance
- A correction to an outdated or inaccurate source

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for the review standard.

## Source Inspiration

This project was inspired by public design-agent workflows and resources shared by designers and builders, including:

- p4n's motion prompt gallery idea
- Emil Kowalski's designer/engineer skills
- Planes and Fluid Functionalism as agent-oriented UI references
- Real-site inspiration galleries such as Recent Design, Siteinspire, Land-book, and Posts Design
- Broader vibe-coding resource maps for components, motion, mobile patterns, and visual references

The repository summarizes principles and links to sources. It does not copy paid content, private materials, or full third-party prompt libraries.

## License

MIT. See [`LICENSE`](LICENSE).
