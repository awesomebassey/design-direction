# Governance

`design-direction` should stay useful because it is curated, not because it accepts every link.

## Principles

- Keep the canonical skill small.
- Put growing knowledge in focused reference files.
- Prefer sourced, practical guidance over taste slogans.
- Keep platform adapters thin so they do not drift.
- Do not copy paid prompts, private materials, or full third-party content.
- Favor open and browseable sources, but document paid access when a source is useful.

## Contribution Paths

Use issues for:

- Suggested references
- Corrections
- Outdated links
- Requests for new prompt modes
- Discussion about controversial guidance

Use pull requests for:

- Adding accepted references
- Fixing source notes
- Improving checklists
- Updating adapters
- Tightening unclear instructions

## Review Roles

Maintainers should review for:

- Practical value to agents
- Correct placement
- Source quality
- Licensing and copying risk
- Whether the change belongs in `skill.md` or a reference file

Community reviewers can comment on:

- Real-world usefulness
- Missing caveats
- Better source categories
- Accessibility, mobile, performance, and design-system concerns

## Versioning

Use lightweight semantic versions once public:

- Patch: corrections, typo fixes, dead links
- Minor: new references, new checklists, new adapters
- Major: changed core design philosophy or incompatible structure

## Deprecation

Do not silently delete useful sources. Mark a source as deprecated when it is unavailable, low quality, misleading, or no longer relevant, then remove it in a later cleanup if no one objects.

