# Academic PPT Methods

A reusable ChatGPT Skill for turning thesis proposal materials into academically rigorous, visually clear methods-section presentations.

## Team edition defaults
- 16:9 blue-white academic style
- optimized for master's thesis proposal defenses
- figure-first design: flowcharts, variable frameworks, path diagrams, analysis hierarchies, technical routes
- outside-the-figure explanatory text limited to 5 lines by default
- automatic boundary notes for cross-sectional studies, path models, simulated figures, exploratory analyses, and parameters pending technical validation
- explicit separation of primary, secondary, and exploratory analyses
- redundancy control: if a figure already explains it, do not repeat it as slide text

## Good inputs
Provide one or more of:
- thesis proposal / opening report
- advisor comments
- current PPT or slide screenshots
- figures or draft diagrams

Then ask for something like:
- “Audit my methods section against my proposal and advisor comments.”
- “Turn this methods section into 8 defense slides.”
- “Redesign these method slides in the team academic style.”
- “Check whether this path diagram overstates causality.”
- “Tell me what belongs inside the figure and what should stay as slide text.”

## Output modes
### Full workflow
Read sources -> audit academic consistency -> design page architecture -> propose figures -> control text density -> final expert review.

### Visual workflow
Take already approved content -> convert it into the team's academic visual language -> remove redundancy -> add required boundary notes.

## Installation
Upload `skill.zip` to ChatGPT Skills.

## Repository structure
- `SKILL.md` - main behavior and workflow
- `references/team-style.md` - team visual standard
- `references/page-blueprints.md` - reusable methods-slide patterns
- `references/academic-review-checklist.md` - academic QA checklist
- `references/output-patterns.md` - standard response formats
- `agents/openai.yaml` - UI metadata
