# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository Overview

This is a **documentation-only repository** containing a phased ultra-learning roadmap. It tracks a multi-year learning journey spanning software engineering, mathematics, physics, and the development of a gamified learning app.

**Key point**: This repository contains NO code - only markdown documentation outlining study plans, resources, and milestones.

## Repository Structure

- `Readme.md` - The complete 5-phase ultra-learning roadmap with:
  - Book lists and resources for each phase
  - App development milestones
  - Study guide with time management strategies
  - Daily and weekly note templates
- `.markdownlint.json` - Markdown linting configuration

## Documentation Management

### Updating Progress

Progress is tracked via:
- Checkboxes `- [ ]` / `- [x]` for resources and milestones
- HTML progress bars: `<progress id="progressBar" max="22" value="1"></progress>`

When updating progress on resources:
```markdown
<!-- Update checkbox -->
- [x] The Rust Programming Language

<!-- Update progress bar -->
<progress id="progressBar" max="22" value="5"></progress>
```

### Markdown Linting

This repository uses markdownlint with configuration in `.markdownlint.json`:
```bash
# Lint markdown files
markdownlint Readme.md

# Auto-fix issues (if markdownlint-cli2 is installed)
markdownlint --fix Readme.md
```

## Learning Plan Structure

The roadmap follows a **5-phase progression**:

1. **Phase 1**: Foundations (Rust, SE principles, Mental Math, Gamification)
2. **Phase 2**: DSA, System Design, Discrete Math
3. **Phase 3**: Pre-Calculus, Calculus, Software Crafting
4. **Phase 4**: 3D Math, Physics
5. **Phase 5**: Applied Physics, Research Methods

### Study Rules (from Readme.md)

- **3 hours daily** - Split between learning, practice, and review
- **Two resources in parallel** - Alternate days (Mon/Wed/Fri vs Tue/Thu/Sat)
- **Sundays for reflection** - Review and dev-log writing
- **Complete all phase resources before starting milestones**
- **Complete all milestones before advancing to next phase**

### Time Management Patterns

**Practical Resources** (180 min):
- Learn (50 min) → Break (10 min) → Practice (80 min) → Break (10 min) → Review (30 min)

**Theory Resources** (180 min):
- 5 cycles of: Learn (25 min) → Break (5 min)
- Final: Review (25 min)

## Common Tasks

### Adding New Resources

When adding books or courses to a phase:
```markdown
- [ ] Resource Title — Author Name
```

### Adding New Milestones

When defining new app milestones:
```markdown
- [ ] 🎮 Feature description with emoji prefix
```

### Creating Study Notes

Use the provided templates from Readme.md:
- **Daily notes**: Track topic, learnings, problems, solutions, tomorrow's focus
- **Weekly notes**: Reflect on topics, achievements, struggles, breakthroughs, and plan

## Version Control

This repository is version controlled with git. Recent changes focus on:
- Updating the learning roadmap structure
- Adding visual diagrams (Mermaid)
- Refining study methodology
- Tracking progress with indicators

When making changes:
```bash
git add Readme.md
git commit -m "descriptive message about learning plan update"
git push origin master
```
