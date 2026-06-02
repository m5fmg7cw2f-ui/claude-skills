# Numerical Simulation for Mathematics Skill

## Purpose
Guide Claude to design, implement, and interpret numerical simulations that support or explore mathematical conjectures and results.

## Trigger
Use this skill when the user asks to:
- Numerically verify a mathematical conjecture
- Simulate a mathematical process or dynamical system
- Compute examples to build intuition
- Generate data to support or refute a hypothesis

## Workflow

### Phase 1: Problem Formulation
1. State the mathematical object to simulate precisely
2. Identify the parameters and their ranges
3. Determine what quantity to measure or observe
4. Set success criteria: what would confirm or refute the conjecture?

### Phase 2: Numerical Design
Choose appropriate method:
- **Direct computation**: exact arithmetic where possible using sympy or sage
- **Floating point**: numpy and scipy for continuous problems
- **Monte Carlo**: random sampling for probabilistic statements
- **Iteration**: fixed-point, eigenvalue, or optimization problems

Precision considerations:
- Use mpmath for high-precision arithmetic when needed
- State the precision used and potential rounding errors
- For combinatorial problems, use exact integer arithmetic

### Phase 3: Implementation
Always document:
- What is being computed
- Parameter ranges chosen and why
- Expected output format

### Phase 4: Validation
- Test on known cases first
- Check limiting cases and boundary behavior
- Compare with analytical results where available
- Report error bounds or confidence intervals

### Phase 5: Interpretation
- State clearly what the simulation shows
- Distinguish: "consistent with" vs "proves"
- Note limitations of the numerical approach
- Suggest analytical follow-up if patterns emerge

## Output Format
- Code with comments
- Plots with labeled axes and title
- Summary table of results
- Interpretation paragraph
