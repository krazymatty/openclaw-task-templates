---
summary: "Workspace template for TASK.md"
read_when:
  - Bootstrapping a workspace manually
  - Starting a new project
---

# TASK.md — Current Focus

Your session anchor. Read this at the start of every session to know what you're working on. Update it when focus changes. This file survives compaction and prevents "what were we doing?" amnesia.

## Goal

*What are you trying to accomplish right now? One clear objective.*

Example: Build user authentication system with OAuth support.

## Progress

### Done
- [ ] *Completed items with brief context*

### In Progress
- [ ] *What you're actively working on*

### Blocked
- [ ] *What's waiting on external input or dependencies*

## Critical Context

*Key decisions, constraints, or gotchas that affect current work. Keep this short — just what's needed to resume without re-reading everything.*

Examples:
- Using PostgreSQL, not SQLite (scaling requirement)
- API must stay backward-compatible with v1 clients
- Deployment blocked until security review completes

## Next Steps

1. *Immediate next action*
2. *Following action*
3. *What comes after that*

---

## Usage Tips

**When to update:**
- At session start (review and refresh)
- When you complete something significant
- When focus shifts to a new goal
- Before compaction (if memoryFlush is enabled, this happens automatically)

**Keep it current, not comprehensive.** This isn't a project history — it's a "where was I?" snapshot. Move completed work to memory files or PLAYBOOK.md phases.

**One goal at a time.** If you're juggling multiple objectives, pick the primary one. Use PLAYBOOK.md for the bigger picture.
