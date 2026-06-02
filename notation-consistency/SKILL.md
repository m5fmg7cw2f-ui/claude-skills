# Notation Consistency Skill

## Purpose
Guide Claude to audit and enforce consistent mathematical notation throughout a paper or document.

## Trigger
Use this skill when the user asks to:
- Check notation consistency in a paper
- Standardize symbols across sections
- Build a notation table
- Resolve conflicting uses of the same symbol

## Workflow

### Step 1: Extract All Notation
Scan the document and build a notation inventory:
- All single-letter variables and their domains
- All operators, maps, and functions
- All special sets, spaces, and structures
- All indexed families and their index sets

### Step 2: Detect Conflicts
Flag:
- Same symbol used for different objects
- Same object referred to by different symbols
- Symbols introduced but never defined
- Symbols defined but never used
- Notation that conflicts with standard usage in the field

### Step 3: Propose Resolutions
For each conflict:
1. State the conflict clearly
2. Propose a resolution (which symbol to keep, what to rename)
3. List all locations that need updating

### Step 4: Generate Notation Table
Produce a notation table listing each symbol and its meaning, suitable for inclusion in the paper's preliminaries section.

## Notes
- Respect standard conventions of the field unless user wants to deviate
- Flag any notation that may confuse referees familiar with standard usage
- Check that subscript and superscript usage is consistent throughout
