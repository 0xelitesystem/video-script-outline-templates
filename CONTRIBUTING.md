# Contributing an Outline

## Submission

1. Pick a format that isn't already covered
2. Copy an existing outline as your starting point
3. Add a row to the table in `README.md`
4. Open a PR

PR title format: `add outline: format-name` (e.g. `add outline: vlog`)

## What makes a good outline

- **Format-specific.** "How-to write any video" is too broad. "Tutorial / how-to" is the right level.
- **Section-by-section.** Each section needs a clear purpose and a target time slot.
- **Honest pacing.** Real video timings, not aspirational ones.
- **Anti-patterns included.** Each outline ends with "what to avoid" specific to the format.
- **Tone-neutral.** The outline should work for any voice, not require a specific personality.

## Required structure

```markdown
# [Format name] outline

**Length:** [typical range]
**Goal:** [what the viewer should leave with]

## [Time slot] - [Section name]

[Description of what goes here, with bracketed placeholders for the creator to fill in]

## Notes for [format] format

[3-6 specific dos/don'ts that apply to this format]
```

## Quality bar

- 8+ sections (more for long-form)
- Specific time markers (not "intro / body / outro")
- At least 3 anti-patterns in the Notes section
- Format must be used by enough creators to be worth a template (not "outline for ASMR thunderstorm explainer")

## What gets rejected

- Outlines that are really just "viral hack" formulas
- Outlines that promise specific results ("this format gets 1M views")
- Outlines that pre-judge product reviews ("intro why X is the best")
- Outlines that skip disclosure for content that requires it
- Outlines copied verbatim from other sources without rewriting

## Updating an existing outline

PR title: `update outline: format-name`. Explain what changed and why.

## Removing an outline

Open an issue first. Reasons might include: format is obsolete (e.g. platform doesn't exist anymore), outline is consistently misused, better outline supersedes it.
