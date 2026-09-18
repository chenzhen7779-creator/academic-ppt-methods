---
name: academic-ppt-methods
description: Turn thesis proposal materials into academically rigorous methods-section PPT plans and research-method infographics using a default 16:9 blue-white academic team style. Use when ChatGPT needs to read a proposal, advisor comments, or an existing PPT and then (1) audit whether slides match the written study, (2) redesign methods pages for an academic defense, (3) decide what belongs in the figure versus supporting slide text, (4) generate or revise flowcharts, variable frameworks, analysis diagrams, technical routes, and method infographics, or (5) package the output as page-by-page PPT guidance for students or colleagues.
---

# Academic PPT Methods Skill

This skill is for **research proposal / thesis defense PPT design**, especially the **methods section**. It assumes the goal is not decoration alone, but **academic accuracy + visual clarity + oral-defense usability**.

## Team default
Apply the team visual standard in `references/team-style.md` unless the user explicitly requests another style or an institutional template requires otherwise. Default to 16:9 blue-white academic slides for master's proposal defenses, prefer diagrams over prose, keep outside-the-figure text to no more than 5 lines, and automatically add appropriate academic boundary notes for cross-sectional designs, path analysis, simulated plots, exploratory analyses, and parameters pending validation.

## Core operating principle
Always work in this order:
1. **Read the study first**: extract the actual design, variables, measures, sample, procedure, analysis plan, and stated research questions.
2. **Read the advisor comments next**: identify what the advisor wants clarified, cut, split, visualized, or re-positioned.
3. **Audit consistency**: ensure every PPT claim is supported by the proposal and does not overstate the study.
4. **Design page architecture**: decide how many slides are needed, what each slide must do, and what should be in the figure versus in supporting text.
5. **Produce visuals and concise text**: use the figure for structure and the slide text for boundaries, definitions, and oral-presentation cues.
6. **Run final expert review**: check logic, academic boundaries, and redundancy.

## Typical inputs
The user may provide any combination of:
- thesis proposal / opening report / manuscript draft
- advisor comments or tracked suggestions
- current PPT or slide screenshots
- existing figures / diagrams
- instructions such as “make it more visual”, “split methods into multiple pages”, or “reduce redundancy”

## Typical outputs
The skill should usually provide one or more of the following:
- page-by-page methods-section PPT plan
- slide title, purpose, on-slide text, and speaker-note suggestions
- figure concepts and image-generation prompts/specs
- academic consistency audit against advisor comments and written proposal
- revised figure labels / captions / boundary notes
- final compact wording that avoids overloading the slide

## Default workflow

### Step 1. Extract the method structure
Build a compact structured summary from the source materials:
- study design (e.g., cross-sectional, experiment, intervention)
- participants / recruitment / sample size target
- variables and roles
  - primary explanatory variable(s)
  - primary outcome
  - secondary outcomes
  - covariates / sensitivity variables
- measurement tools and scoring ranges
- procedure / timing / quality control
- research questions / hypotheses
- statistical plan

If any item is not explicitly given, say it is **not yet specified** instead of inventing details.

### Step 2. Translate advisor comments into revision tasks
Turn advisor comments into specific action items such as:
- reduce text density
- split one crowded methods slide into multiple slides
- use diagrams for process / relationships / technical route
- clarify primary vs secondary analyses
- avoid merging unrelated constructs into one score
- avoid causal language if the design is observational / cross-sectional

If the advisor comment is ambiguous, interpret conservatively.

### Step 3. Decide the right page set
For a methods section, prefer a page set such as:
- **5.1 Research design / participants / sample plan**
- **5.2 Variable and measurement framework**
- **5.3 Key task or experiment procedure**
- **5.4 Functional or behavioral measures**
- **5.5 Testing procedure and quality control**
- **5.6 Research questions and analysis strategy**
- **5.7 Statistical models and analysis hierarchy**
- **5.8 Technical route / implementation flow**

Do not force exactly 8 pages if the material does not support it. But when the user already has an 8-page structure, preserve it and optimize within that structure.

### Step 4. Allocate information between figure and slide text
Use this rule aggressively:
- **The figure carries structure**: boxes, arrows, relations, scoring ranges, flows, model hierarchy.
- **The slide text carries non-obvious clarification**: academic boundaries, definitions, caveats, and 1–3 presenter cues.

Avoid duplicating figure text in full sentences on the same slide.

Good slide-side additions:
- “Figure shows domain structure; oral explanation emphasizes why FES-I is the only primary outcome.”
- “Diagram is a schematic, not empirical result.”
- “Path analysis is exploratory and not interpreted causally.”

Bad slide-side additions:
- repeating the same labels already clearly present inside the figure
- converting every figure element into a bullet list

### Step 5. Design each slide with a strict template
For each slide, provide these headings when the user asks for a page plan:
1. **Slide title**
2. **Core function of this slide**
3. **Main figure to place**
4. **Minimal supporting text to place outside the figure**
5. **Recommended layout**
6. **Presenter’s 20–40 second explanation**
7. **Academic risk check**

Keep outside-the-figure text short. Usually 2–5 bullets or 1 short note block is enough.

### Step 6. Build or revise visuals
When proposing a figure or image-generation prompt:
- make the figure self-explanatory at first glance
- use academically neutral wording
- distinguish **actual design** from **illustrative schematic**
- include units / scoring ranges where needed
- show hierarchy explicitly: primary, secondary, exploratory
- include boundary notes directly on the figure only when necessary and space allows

For research-method figures, common figure types are:
- variable measurement framework
- task workflow / experiment procedure
- test procedure and quality-control flow
- research-question decomposition
- analysis hierarchy / model diagram
- technical route timeline or flowchart

## Academic rules that must not be violated

### Causality and design boundaries
- If the study is **cross-sectional**, do not present findings as causal.
- Use “association”, “relationship”, “linked to”, or “statistical path decomposition” rather than causal claims.
- A path diagram may be used as a statistical decomposition figure, but explicitly mark it as **not causal mediation** unless the design justifies such interpretation.

### Primary vs secondary vs exploratory
- A single clearly identified **primary analysis** should be visually and verbally prioritized.
- Secondary analyses may be presented, but do not let them visually dominate.
- Exploratory analyses should be clearly labeled as exploratory and not upgraded into headline conclusions.

### Consistency with source materials
- Do not add measures, procedures, hypotheses, or technical parameters unless the user’s materials support them.
- If parameter values are not finalized, label them as **to be finalized after local technical validation** or equivalent.

### Statistical wording
- If the user presents model comparisons, keep the language precise:
  - “joint explained information”
  - “unique explained information” / “incremental explained variance”
  - “same sample, same covariate set” when comparing nested models
- If multiple testing correction is planned, state the planned correction method and which family of tests it applies to.
- Prefer reporting **effect sizes and 95% CIs**, not significance language alone.

### Measurement wording
- Keep construct and instrument distinct.
  - Example: “fear of falling” is the construct; “FES-I” is the instrument.
- Do not merge conceptually different measures into one artificial composite unless the study explicitly defines one.

## Redundancy control rules
If a high-information figure is already placed on the slide, outside-the-figure text should usually include only:
- **1 line**: what the audience should focus on
- **1–3 bullets**: boundary conditions / interpretation reminders
- **optional 1 short footer**: data or figure-status note

Never restate all figure content line-by-line.

## Recommended output style
When the user asks “What should this PPT page include?”, answer page by page using this compact structure:

### [Slide number and title]
- **Purpose**:
- **Place this figure**:
- **Add only these supporting words**:
- **Layout**:
- **Speaker cue**:
- **Risk to avoid**:

When the user asks for a final slide-ready version, keep language concise and presentation-ready.

## If the user asks to generate or revise figures
Before producing figure content, check:
1. Is the figure consistent with the written study?
2. Does the figure overclaim?
3. Does the figure duplicate too much text?
4. Is the slide meant for reading or for speaking support?
5. Is any simulated chart labeled as schematic / non-empirical?

Then provide:
- the exact figure goal
- what must appear in the figure
- what must stay outside the figure
- any required academic disclaimer

## Use these references when needed
- For the team-specific visual standard, see `references/team-style.md`.
- For slide page patterns and figure/text allocation, see `references/page-blueprints.md`.
- For academic review criteria and boundary checks, see `references/academic-review-checklist.md`.
- For reusable wording and output templates, see `references/output-patterns.md`.
