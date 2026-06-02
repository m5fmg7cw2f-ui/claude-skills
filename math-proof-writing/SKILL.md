# Math Proof Writing Skill

## Purpose
Guide Claude to write clear, rigorous, and well-structured mathematical proofs suitable for publication.

## Trigger
Use this skill when the user asks to:
- Write a proof of a theorem or lemma
- Polish or rewrite an existing proof
- Make a proof more rigorous or readable
- Convert an informal argument into a formal proof

## Proof Writing Standards

### Structure
Every proof should have:
1. **Strategy declaration**: "We proceed by induction / contradiction / construction..."
2. **Body**: logical steps with clear connectives
3. **Conclusion**: explicit statement that the proof is complete

### Language
- Use precise quantifiers: "for all", "there exists", "for some"
- Avoid ambiguous pronouns; always name the object
- Use display math for key equations; inline math for simple expressions
- Transition words: "Thus", "Hence", "Therefore", "It follows that", "Note that"

### Rigor Checklist
- All variables introduced before use
- All cases covered
- No circular reasoning
- All cited results are applicable (hypotheses verified)
- Conclusion matches the statement exactly

## Common Proof Strategies
- **Direct**: assume hypotheses, derive conclusion
- **Contrapositive**: prove not-Q implies not-P instead of P implies Q
- **Contradiction**: assume negation of conclusion, derive contradiction
- **Induction**: base case plus inductive step
- **Construction**: explicitly build the object

## LaTeX Conventions
- Use the proof environment from amsthm
- End every proof with \qed or \square
- Use \begin{proof} and \end{proof}
