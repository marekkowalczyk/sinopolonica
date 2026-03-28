[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19299193.svg)](https://doi.org/10.5281/zenodo.19299193)

# Sinopolonica: A Logographic-Latin Hybrid Writing System for Polish

## What Is This?

Sinopolonica is a constructed writing system for the Polish language that
pairs Classical Chinese logographic characters with Latin-script
inflectional suffixes. It is a thought experiment in fantasy linguistics
— exploring what would happen if Polish had been drawn into the
Sinosphere the way Japanese, Korean, and Vietnamese once were.

The system is governed by five axioms (see `docs/00-axioms.md`) and a
set of numbered principles documented across the `docs/` directory.

## Quick Example

| Polish | Sinopolonica |
|---|---|
| Mój stary ojciec mieszka w małym domu nad rzeką. | 吾ój 古y 父 居a 中 小ym 家u 臨 河ą. |

Every morpheme carrying semantic content is a Chinese character. Latin
script handles only inflectional endings.

## Repository Structure

```text
sinopolonica/
├── README.md .................. this file
├── CONTRIBUTING.md ............ contribution guidelines
├── docs/
│   ├── 00-axioms.md .......... foundational axioms and numbered principles
│   ├── 01-registers.md ....... character sources and register system
│   ├── 02-nouns.md ........... nouns, case, diminutives, augmentatives
│   ├── 03-adjectives.md ...... adjectives, comparison, agreement
│   ├── 04-verbs.md ........... verbs, prefixes, aspect, multi-reading
│   ├── 05-pronouns.md ........ personal, possessive, reflexive, interrogative
│   ├── 06-function-words.md .. prepositions, conjunctions, particles, negation
│   ├── 07-derivation.md ...... productive suffixes, compounds, silent classifiers
│   ├── 08-learned.md ......... Latinate/Greek compound decomposition
│   ├── 09-numerals.md ........ three-tier numeral system
│   ├── 10-orthography.md ..... spacing, punctuation, direction, proper nouns
│   └── 99-open-questions.md .. unresolved design decisions, future work
├── examples/
│   ├── sentences.md .......... annotated example sentences
│   └── literary.md ........... longer literary passages
├── lexicon/
│   ├── README.md ............. lexicon organization principles
│   ├── core-500.md ........... [placeholder] essential 500 characters
│   ├── everyday.md ........... [placeholder] everyday register inventory
│   ├── learned.md ............ [placeholder] learned register inventory
│   └── suffixes.md ........... [placeholder] derivational suffix characters
└── tools/
    └── README.md ............. [placeholder] future tooling ideas
```

## Status

This project is at the **specification stage**. The design principles are
stable. The core character lexicon has not yet been compiled.

## License

Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0).

## Authors

Conceived by Marek Kowalczyk
([ORCID 0009-0008-3874-6736](https://orcid.org/0009-0008-3874-6736))
& Claude (Anthropic), March 2026.
