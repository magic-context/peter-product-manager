# Project Structure Template

Use this template when creating a new project. Copy this folder structure to your `projects/` directory.

## Complete Project Structure

```
project-name/
├── overview.md                           # Project overview (use product_overview.md template)
│
├── phases/
│   └── phase-1-name/
│       ├── overview.md                   # Phase goals, timeline, success criteria
│       └── sprints/
│           └── sprint-01/
│               ├── plan.md               # Sprint plan (use sprint_plan.md template)
│               ├── progress.md           # Sprint tracking (use sprint_details.md template)
│               └── user-stories/
│                   └── us-001-story-name.md  # Story details (use user_story_details.md template)
│
└── documents/
    ├── prd.md                            # Product Requirements Document
    ├── technical-spec.md                 # Technical specifications
    └── user-research.md                  # Research findings
```

## Step-by-Step Setup

### 1. Create Project Folder
```bash
mkdir -p projects/your-project-name
```

### 2. Create Overview
Copy `templates/product_overview.md` to `projects/your-project-name/overview.md` and fill it in.

### 3. Add First Phase
```bash
mkdir -p projects/your-project-name/phases/phase-1-discovery
```

Create `overview.md` in the phase folder:

```markdown
# Phase: Discovery

**Status:** Active
**Timeline:** [Start] to [End]

## Goals
1. [Goal 1]
2. [Goal 2]

## Success Criteria
- [ ] [Criteria 1]
- [ ] [Criteria 2]
```

### 4. Add First Sprint
```bash
mkdir -p projects/your-project-name/phases/phase-1-discovery/sprints/sprint-01/user-stories
```

- Copy `templates/sprint_plan.md` → `plan.md`
- Copy `templates/sprint_details.md` → `progress.md`

### 5. Add User Stories
For each story in the sprint:
- Copy `templates/user_story_details.md` → `user-stories/us-001-story-name.md`

### 6. Add Documents Folder
```bash
mkdir -p projects/your-project-name/documents
```

Add PRDs, specs, research as needed.

## Naming Conventions

| Item | Convention | Example |
|------|-----------|---------|
| Project folder | lowercase-with-dashes | `user-authentication` |
| Phase folder | phase-#-name | `phase-1-discovery` |
| Sprint folder | sprint-## | `sprint-01` |
| User story file | us-###-description.md | `us-001-user-login.md` |
| Documents | descriptive-name.md | `prd-auth-v1.md` |

## Minimum Viable Project

At minimum, every project needs:
- [ ] `overview.md` - What is this project and why?
- [ ] At least one phase folder
- [ ] At least one sprint with plan and stories
- [ ] Success criteria defined

## Complete Project Checklist

- [ ] Overview with goals, users, success metrics
- [ ] Phases defined with milestones
- [ ] Current sprint has plan and committed stories
- [ ] User stories have acceptance criteria
- [ ] Key documents stored in documents/
- [ ] Decision rationale captured

---

*This template ensures consistency across all your projects.*
