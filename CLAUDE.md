# CLAUDE.md — AI Assistant Guide for TemperaryT/TemperaryT

## Repository Overview

This is a **personal GitHub profile repository** for Donald Thompson. It contains a single `README.md` that serves as a professional introduction and portfolio statement. There is no application code, build system, or test suite.

## Repository Structure

```
TemperaryT/
└── README.md   # Personal profile / portfolio page (25 lines)
```

## Purpose

This repository's `README.md` is displayed on Donald Thompson's GitHub profile page. It communicates:

- Professional background (20-year military career transitioning to technology)
- Current learning focus (C++, Python data structures, Google Data Analytics Certification)
- Career goals (MLOps, graduate studies in Data Science)
- Hobbies (Unreal Engine, Blender)
- Contact information

## Development Conventions

Since this is a profile-only repository, "development" means editing the README.md:

- **Format**: GitHub Flavored Markdown (GFM)
- **Emoji**: Used for section headers to improve visual scannability — maintain this style
- **Sections**: Keep the existing section hierarchy (Current Focus, Professional Background, Goals, Hobbies, Reading List, Contact)
- **Tone**: Professional but personal; first-person, mission-driven language that reflects a military-to-tech background

## Editing Guidelines for AI Assistants

1. **Only file to edit**: `README.md` — do not create application code, configs, or extra files unless explicitly requested
2. **Preserve the voice**: Donald's writing style is disciplined and direct; maintain this tone
3. **Update reading lists and certifications** when asked — these change frequently as learning progresses
4. **No build steps**: There is nothing to compile, test, or deploy
5. **Branch**: Feature work should happen on `claude/add-claude-documentation-P0UY3`; stable content lives on `master`/`main`

## Git Workflow

```bash
# Clone and work on feature branch
git checkout claude/add-claude-documentation-P0UY3

# Make changes, then commit
git add README.md
git commit -m "Update README: <brief description>"

# Push
git push -u origin claude/add-claude-documentation-P0UY3
```

## Key Facts

| Item | Detail |
|---|---|
| Owner | Donald Thompson |
| Contact | donald.thompson.careers@gmail.com |
| Primary file | `README.md` |
| Language | Markdown |
| Framework | None |
| Tests | None |
| CI/CD | None |
| Default branch | `main` (remote), `master` (local) |

## What NOT to Do

- Do not add package.json, requirements.txt, or any dependency files unless explicitly requested
- Do not add CI/CD workflows unless explicitly requested
- Do not restructure the README sections without instruction — the current layout is intentional
- Do not remove the emoji headers; they are part of the established style
