---
title: "Contributing to Sinopolonica"
---

## How to Contribute

Sinopolonica is a constructed writing system — a thought experiment in
fantasy linguistics. Contributions that deepen, correct, or extend the
system are welcome.

## Types of Contributions

### Character proposals

Propose a new character assignment for a Polish morpheme not yet covered.
Your proposal should include:

1. The Polish morpheme and its meaning.
2. The proposed character, with justification (Classical Chinese source,
   semantic fit, register appropriateness).
3. Which principle(s) from `docs/00-axioms.md` govern the assignment.
4. Example words showing the character in context.
5. Any competing candidates you considered and why you rejected them.

### Principle challenges

If you believe a numbered principle (P01–P18) produces an incorrect or
inelegant result in a specific case, file an issue with:

1. The principle number.
2. The specific Polish word or construction that causes the problem.
3. Your proposed resolution.
4. Whether the resolution requires amending the principle or adding an
   exception.

### Example texts

Contribute new example sentences or literary passages with full
annotation. Follow the format in `examples/sentences.md`.

### Lexicon entries

Contribute entries to the lexicon files following the format in
`lexicon/README.md`.

### Tools and code

Contribute computational tools to the `tools/` directory. Any language
is acceptable. Include tests and documentation.

## Style Guidelines

- Reference principles by number (P01, P02, etc.) and axioms by code
  (A1, A2, etc.) in all discussions.
- When proposing character assignments, always check `docs/01-registers.md`
  for register appropriateness.
- Apply the recursive stem test from `docs/07-derivation.md` checklist
  before finalizing any rendering.

## Code of Conduct

This is a linguistic thought experiment. Approach contributions with
curiosity, rigor, and good humor. Disagreements about character
assignments are expected and welcomed — they are the heart of the
project.
