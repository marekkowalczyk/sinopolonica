---
title: "Open Questions and Future Work"
subtitle: "Document 99 — Design Decisions Pending Resolution"
---

## Open Design Questions

### OQ-01: Plural-only nouns and defective paradigms

Polish has nouns that exist only in plural (pluralia tantum): *drzwi*
(door), *nożyczki* (scissors), *skrzypce* (violin). How should the
character interact with a word that has no singular? Current assumption:
the character represents the concept; the plural ending is mandatory.

### OQ-02: Gerunds and verbal nouns

The verbal noun *czytanie* (reading, the act of) — is *-anie* a
derivational suffix deserving a character, or an inflectional nominalization?
Current leaning: inflectional → Latin script. But this deserves further
analysis.

### OQ-03: Aspectual po- and other bleached prefixes

Distributive *po-* (P02) currently stays in Latin as "purely aspectual."
But the boundary between spatial and aspectual meaning is fuzzy.
*Powyrzucać* (throw out one by one) — *po-* is distributive, *wy-* is
spatial. Is *po-* truly devoid of meaning here? This needs a principled
criterion.

### OQ-04: Productive neologisms

How does the system handle new words entering Polish? Who assigns
characters to *streaming*, *podcast*, *startup*? Possible approach:
decompose into semantic components when possible (遠播 for *podcast* =
far + broadcast?), leave in Latin when the word is too opaque or too new
to have settled.

### OQ-05: Dialectal and archaic vocabulary

Should the system accommodate regional or archaic Polish stems that have
different roots than standard Polish? E.g., Silesian *hajer* (miner) vs.
standard *górnik*.

### OQ-06: Homophonous stems

Polish has stems that sound identical but differ in meaning: *zamek*
(castle) vs. *zamek* (lock). These should receive different characters
(城 vs. 鎖). The system here is actually *more* precise than Polish
Latin-script orthography, which cannot distinguish them. Document these
disambiguation gains systematically.

### OQ-07: The 己行 vs. 己行機 policy

P16 allows optional silent classifiers. Should the lexicon mark a
recommended default (with or without classifier), or leave it entirely
to writer's choice? A standardization body would eventually need to
resolve this.

### OQ-08: Ordinal numbers and number-derived adjectives

*Pierwszy* (first), *drugi* (second), *trzeci* (third) — these have
opaque etymologies. Do they receive characters (第一, 第二...)? Or is this
over-reaching into the numeral system?

## Future Work

### Core lexicon compilation

Priority: compile the Core 500 characters — the minimum set needed to
write everyday Polish. This requires frequency analysis of Polish text
corpora cross-referenced with the morpheme-to-character mapping rules.

### Font and rendering

Explore whether existing CJK fonts can be used as-is, or whether a
custom font incorporating both CJK characters and Polish diacritics in a
harmonious visual style is needed.

### Pedagogical materials

Develop a graded reader series: texts using only the first 100
characters, then 200, then 500, with full glosses.

### Input method

Design a keyboard input method that allows efficient typing of
character-plus-suffix sequences. Consider radical-based input (as in
Chinese IMEs) with automatic suffix attachment.

### Computational tools

Build a tokenizer that can split Sinopolonica text into
character-plus-suffix tokens. Build a converter that transforms standard
Polish text into Sinopolonica (requires morphological analysis and a
character lookup table).

## Developmental Phases

The project has a natural three-phase trajectory, each more ambitious
than the last.

### Phase 1 — Sinopolonica (current)

Chinese characters adapted to Polish. The system borrows both the
characters and the structural principle from the Chinese writing
tradition. This is analogous to what Japanese, Korean, and Vietnamese
did historically.

### Phase 2 — Cross-Slavic and cross-Indo-European extension

The same character set, applied to other Slavic languages. Because
Slavic languages share most lexical roots, a Sinopolonica text is
partially legible to speakers of Czech, Slovak, Russian, Ukrainian,
Serbian — the semantic characters are language-independent, and the
grammatical tails (while different) are recognizable. This could
extend to a pan-Indo-European logographic layer, exploiting the deep
shared roots: Latin *domus*, Polish *dom*, Russian *дом*, Sanskrit
*dáma-* — one character, many grammars.

This is structurally parallel to how Literary Chinese (文言文) served as
a shared written medium across East Asia for centuries — a
supralinguistic script layer above mutually unintelligible spoken
languages.

### Phase 3 — Ideographica: a native Indo-European logographic script

The most ambitious extension. Analogous to what the Tangut Empire did
in the 11th century: instead of borrowing Chinese characters, the Tangut
reverse-engineered the *design logic* of the Chinese writing system —
stroke types, radical-phonetic composition, visual density — and built
an entirely new set of ~6,000 glyphs that look Chinese at first glance
but share zero characters with actual Chinese.

Ideographica would do the same for Indo-European languages:

**Radicals based on IE semantic categories.** Instead of Chinese
radicals (氵= water, 木 = wood, 口 = mouth, 心 = heart), develop
radicals derived from Proto-Indo-European root meanings: *\*h₂ékʷeh₂*
(water), *\*dóru* (wood/tree), *\*h₃éh₁os* (mouth), *\*ḱḗr* (heart).
The radical inventory would reflect the semantic universe of IE
languages rather than Chinese.

**Phonetic components based on IE/Slavic phonology.** Chinese phonetic
indicators encode Mandarin syllable structure (CV, CVn, CVng). IE
phonetic components would encode Slavic consonant clusters (sz, cz, rz,
szcz, str, prz) and vowel patterns that Chinese phonology cannot
represent. A reader seeing the phonetic component would get an
approximate pronunciation hint in any Slavic language.

**Composite character construction.** Like Chinese, each character would
be a radical + phonetic composite. But the composites would be
self-describing for IE speakers in a way that Chinese characters are for
Chinese speakers. The radical tells you the semantic domain; the
phonetic component hints at the pronunciation. A character for Polish
*rzeka* (river) might combine the water radical with a phonetic element
suggesting *rzek-*.

**Cross-IE legibility by design.** Because the radicals encode IE
semantic categories and the phonetic components encode IE sound patterns,
the same script would be partially legible across all IE languages —
just as Chinese characters are partially legible across Chinese
dialects. A Polish reader and a Hindi reader would share the radicals
(semantic layer) while reading different phonetics.

**Visual identity.** The resulting script would *look* like a
logographic system — dense, square, component-based — but would be
visually distinct from Chinese, Japanese, or Tangut. It would be the
first logographic script designed for the Indo-European language family.

This phase is speculative and would require significant collaborative
effort from linguists, typographers, and script designers. But the
Tangut precedent proves it is possible: one civilization, working from
Chinese design principles, produced a complete parallel logographic
universe. There is no reason the same cannot be done for Indo-European.

