# Scientific Math LaTeX Skill

## Purpose
Guide Claude to produce high-quality LaTeX code for mathematical papers, following journal standards and best practices.

## Trigger
Use this skill when the user asks to:
- Write or format LaTeX for a math paper
- Fix LaTeX compilation errors
- Format equations, theorems, or proofs in LaTeX
- Prepare a document for arXiv or journal submission

## Document Setup
Standard preamble for a math paper:
- documentclass: amsart or article
- packages: amsmath, amssymb, amsthm, mathtools, hyperref, cleveref

## Theorem Environments
Define theorem environments using newtheorem with shared counter:
- theorem, lemma, proposition, corollary share one counter
- definition and remark use theoremstyle definition and remark respectively

## Equation Best Practices
- Use equation environment for single numbered equations
- Use align for multi-line aligned equations
- Use gather for multiple centered equations
- Use \eqref{} to reference equations
- Never use $$ $$ — use \[ \] instead for display math

## Common Symbols
- Number sets: \mathbb{R}, \mathbb{N}, \mathbb{Z}, \mathbb{C}, \mathbb{Q}
- Operators: \nabla, \partial, \int, \sum, \prod, \lim, \sup, \inf
- Arrows: \to, \Rightarrow, \iff, \mapsto, \hookrightarrow
- Norms: use \| \| for norms, \lvert \rvert for absolute values

## Quality Checklist
- All \begin{} have matching \end{}
- No overfull hboxes in key equations
- References use \cite{} with BibTeX keys
- Figures have captions and labels
- Cross-references use \cref{} or \ref{}
- Bibliography uses BibTeX or BibLaTeX
