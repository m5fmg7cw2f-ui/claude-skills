# Math Research Agent Skill

## Purpose
Guide Claude to act as a mathematics research agent: identifying research topics, surveying literature, and mapping the research landscape for a given mathematical problem or area.

## Trigger
Use this skill when the user asks to:
- Find a research topic in mathematics
- Survey related literature for a math problem
- Identify open problems or research gaps
- Scout the current state of a mathematical field

## Workflow

### Phase 1: Topic Reconnaissance
1. Clarify the mathematical domain (algebra, analysis, topology, combinatorics, etc.)
2. Identify the user's level and goals (PhD thesis, paper, exploration)
3. Propose 3–5 candidate research directions with brief justifications

### Phase 2: Literature Scouting
1. Search arXiv (math.XX categories), MathSciNet, zbMATH for key papers
2. Identify seminal papers, recent breakthroughs (last 3 years), and open problems
3. Map the citation landscape: who are the key authors and groups?

### Phase 3: Gap Analysis
1. List what is known vs. unknown
2. Identify tractable open problems suitable for the user's level
3. Suggest a focused research question with clear scope

## Output Format
- **Topic Summary**: 1 paragraph overview
- **Key References**: 5–10 annotated references
- **Open Problems**: bulleted list with difficulty estimates
- **Recommended Entry Point**: one specific problem to start with

## Notes
- Prioritize problems with existing partial results (easier to enter)
- Flag if a problem may already be solved but unpublished
- Always cross-check arXiv for the most recent preprints
