# @gonzih/skills-teacher

Teacher and educator skills for Claude Code (OpenClaw/Clawdbot).

## Skills Included

| Skill | Description |
|-------|-------------|
| `lesson-plan` | Create detailed lesson plans aligned to learning objectives |
| `parent-newsletter` | Write engaging classroom newsletters for parents |
| `iep-summary` | Write clear IEP goal summaries for parents and staff |
| `assessment-rubric` | Create assessment rubrics for any assignment type |

## Installation

### Via npm

```bash
npm install @gonzih/skills-teacher
```

Then copy the skill folders to your skills directory:

```bash
# Global installation
cp -r node_modules/@gonzih/skills-teacher/skills/* ~/.openclaw/skills/

# Project-level installation
cp -r node_modules/@gonzih/skills-teacher/skills/* ./skills/
```

### Via ClawdHub CLI

```bash
npx clawdhub@latest install lesson-plan
npx clawdhub@latest install parent-newsletter
npx clawdhub@latest install iep-summary
npx clawdhub@latest install assessment-rubric
```

### Manual Installation

Copy the skill folder(s) to one of these locations:

| Location | Path |
|----------|------|
| Global | `~/.openclaw/skills/` |
| Workspace | `<project>/skills/` |

## Skill Details

### lesson-plan
Creates detailed, standards-aligned lesson plans for any subject and grade level. Includes learning objectives, instructional sequence, differentiation strategies, and assessment.

### parent-newsletter
Writes warm, informative classroom newsletters for families. Covers recent learning highlights, upcoming events, at-home tips, and reminders.

### iep-summary
Translates technical IEP goal language into clear, accessible summaries for parents and general education staff. Strengths-based and family-friendly.

### assessment-rubric
Builds analytic rubrics for any assignment type — essays, projects, presentations, lab reports, and more. Includes performance level descriptors and scoring guides.

## License

MIT
