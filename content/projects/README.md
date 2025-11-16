# Projects Directory

This folder contains all your active and completed projects.

## Structure

Each project gets its own folder with a standardized structure:

```
projects/
├── project-name/
│   ├── overview.md           # Project goals, users, metrics (use product_overview template)
│   ├── phases/               # Project breakdown into phases
│   │   └── phase-name/
│   │       ├── overview.md   # Phase goals and milestones
│   │       └── sprints/      # Sprints within this phase
│   │           └── sprint-name/
│   │               ├── plan.md       # Sprint plan (use sprint_plan template)
│   │               ├── progress.md   # Sprint tracking (use sprint_details template)
│   │               └── user-stories/ # Individual user stories
│   │                   └── story-name.md
│   └── documents/            # PRDs, specs, research, decisions
│       ├── prd.md
│       ├── technical-spec.md
│       └── research-findings.md
```

## How to Create a New Project

1. Create a folder with project name (use lowercase-with-dashes)
2. Copy `templates/product_overview.md` as `overview.md`
3. Fill in project details
4. Add phases and sprints as you plan them
5. Store supporting documents in `documents/`

## Naming Conventions

- **Project folders**: `project-name` (lowercase, dashes)
- **Phase folders**: `phase-1-planning` or `phase-discovery`
- **Sprint folders**: `sprint-01` or `sprint-authentication`
- **Documents**: Descriptive names like `user-research-oct-2025.md`

## Example

See `_example-project-structure/` for a complete folder structure example.

---

*Your AI assistant will reference this structure to understand your product work and provide contextual assistance.*
