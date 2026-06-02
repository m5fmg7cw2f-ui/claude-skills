# Proof Checker Skill

## Purpose
Guide Claude to rigorously check mathematical proofs for logical errors, gaps, unjustified claims, and structural issues.

## Trigger
Use this skill when the user asks to:
- Check or verify a mathematical proof
- Find errors or gaps in an argument
- Validate logical steps in a derivation
- Review a proof before submission

## Workflow

### Step 1: Parse the Proof Structure
1. Identify the statement being proved (theorem, lemma, proposition)
2. List all hypotheses and what needs to be shown
3. Identify the proof strategy (direct, contradiction, induction, construction, etc.)

### Step 2: Line-by-Line Verification
For each step, check:
- Is this step logically justified by previous steps or known results?
- Is the cited theorem/lemma applicable here? (check hypotheses)
- Are there implicit assumptions that need to be stated?
- Are quantifiers and logical connectives used correctly?
- Are set membership, domain, and type constraints respected?

### Step 3: Global Structure Check
- Does the proof cover all cases?
- Are there boundary cases or degenerate cases missing?
- Is the induction base case proved? Is the inductive step correct?
- Does the conclusion actually follow from what was proved?

### Step 4: Report
Produce a structured report:
- **Status**: Valid / Invalid / Incomplete / Needs Revision
- **Errors**: list each error with line reference and explanation
- **Gaps**: unjustified leaps that need filling
- **Suggestions**: how to fix each issue

## Notes
- Distinguish between minor presentational issues and actual logical errors
- If a step is correct but non-obvious, flag it for clarification
- When in doubt, ask the user for the source of a claimed result
