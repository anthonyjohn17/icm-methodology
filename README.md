# ICM Methodology

**Interpretable Context Methodology (ICM)** is a filesystem-first approach to AI workflow orchestration using folders, markdown contracts, and staged human review.

This repository captures a practical and conceptual exploration of ICM, centered on the idea that:

> For many sequential, human-reviewed AI workflows, the filesystem can act as the orchestration layer.

Instead of relying on complex multi-agent framework code, ICM organizes workflow stages with folders and markdown files so context, process, and handoffs are explicit and easy to inspect.

## Repository Contents

### Implementation

- `icm-core/` — working ICM implementation with three production-ready workspaces:
  - `workspaces/script-to-animation/` — content idea through script, animation spec, and Remotion code
  - `workspaces/course-deck-production/` — unstructured material (PDFs, notes) into polished slide decks
  - `workspaces/workspace-builder/` — build a new ICM workspace for any domain
  - `_core/` — shared conventions, templates, and placeholder syntax reference

### Research & Reference

- `ICM_conversation.md` — detailed long-form breakdown of ICM concepts, architecture, and implications.
- `docs/File Tree as Agent.md` — exploration of file-tree-first agent design and the context wall problem.
- `src/filetree-agent.html` — interactive visual presentation of the core thesis and ICM paper walkthrough.
- `ICM Paper.pdf` — local copy of the ICM paper referenced throughout the project.

## Why This Project Matters

- Demonstrates architecture thinking for AI systems, not just prompt iteration.
- Focuses on interpretability, portability, and human-in-the-loop workflow design.
- Shows how simple primitives (files/folders) can replace unnecessary orchestration complexity for the right class of tasks.

## Getting Started

```bash
git clone <this-repo>
cd icm-core
# Open in Claude Code, then navigate to a workspace:
cd workspaces/script-to-animation
# Type "setup" to run onboarding
```

See `icm-core/README.md` for full documentation on workspaces, conventions, and how to build your own.

## References

- arXiv abstract: [Interpretable Context Methodology](https://arxiv.org/abs/2603.16021)
- arXiv PDF: [https://arxiv.org/pdf/2603.16021](https://arxiv.org/pdf/2603.16021)
