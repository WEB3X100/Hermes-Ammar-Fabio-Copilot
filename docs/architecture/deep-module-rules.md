# Deep Module Rules

## Purpose

Deep modules prevent Hermes from drowning in setup examples, screenshots, and old journals.

Hermes should use simple skill interfaces by default and only open detailed implementation files when needed.

## Required Skill Shape

Each skill should look like:

```text
skills/<skill-name>/
  README.md
  SKILL.md
  template.md
  SCORECARD.md
  implementation/
    setup-examples/
    screenshot-notes/
    checklists/
    raw-notes/
```

## Interface Files

Hermes may read these by default:

```text
README.md
SKILL.md
template.md
SCORECARD.md
```

## Implementation Files

Hermes may only read `implementation/` when:

- an AAA setup is actively forming,
- a screenshot requires detailed review,
- an alert failed and needs debugging,
- weekly review asks for pattern analysis,
- or Umair/Ammar explicitly asks.

## Raw Data Rule

Do not commit raw broker exports, account data, or sensitive screenshots.

Use sanitized notes:

```text
Date:
Instrument:
Setup:
Context:
Lesson:
Screenshot path/private reference:
```
