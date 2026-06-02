# Related Work Writer Skill

## Purpose
Guide Claude to write high-quality "Related Work" sections for mathematics papers, with proper academic tone, logical organization, and accurate attribution.

## Trigger
Use this skill when the user asks to:
- Write a related work or literature review section
- Situate their results within existing literature
- Compare their approach to prior work
- Draft a survey of a mathematical topic

## Workflow

### Phase 1: Gather Material
1. Ask the user for: paper title, main results, key techniques used
2. Collect the reference list the user wants to cite
3. Ask which works are most closely related vs. background

### Phase 2: Organize the Narrative
Structure related work into logical clusters:
- **Foundational work**: classical results that set the stage
- **Direct predecessors**: papers that directly motivate this work
- **Parallel approaches**: different methods attacking the same problem
- **Contrast**: what this paper does differently or better

### Phase 3: Write
- Each cluster gets 1-3 sentences per paper: what they did, how it relates
- Use precise mathematical language; avoid vague claims
- Explicitly state how cited work differs from the current contribution
- Use standard attribution phrases: "X et al. showed that...", "Building on..."

## Output Format
- Flowing prose, not a bulleted list
- LaTeX-ready with \cite{} commands
- 400-800 words typical length
- End with a transition sentence to the main results

## Style Rules
- Never overclaim similarity to prior work
- Never undercite — if you used an idea, cite it
- Maintain neutral, academic tone throughout
