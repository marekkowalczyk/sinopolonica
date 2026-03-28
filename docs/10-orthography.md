---
title: "Orthography"
subtitle: "Document 10 — Implements A5, P13, P15"
---

## Writing Direction

Left to right, horizontal. No vertical writing option is provided. The
system is a hybrid — Polish reading habits and typographic conventions
are preserved.

## Spacing

Characters and Latin-script segments **within a single word** are written
without spaces: 歩łem, 古ych, 不誰, 冊舍i.

Spaces separate words as in standard Polish orthography. No CJK
word-boundary conventions are imported.

## Polish Diacritics

All Polish-specific letters are preserved in the Latin-script layer:
ą, ę, ó, ł, ż, ź, ś, ć, ń. These are integral to inflectional endings
and must be rendered correctly.

## Punctuation

Western punctuation is used throughout: period (.), comma (,),
semicolon (;), colon (:), em dash (—), exclamation mark (!), question
mark (?), quotation marks (Polish „..." or «...»).

No CJK punctuation conventions (full-width comma, hollow period, corner
brackets) are imported.

## Proper Nouns (P13)

All proper nouns remain in Latin script:

- Personal names: Jan, Katarzyna, Kowalski
- Place names: Warszawa, Kraków, Gdańsk
- Foreign names: London, Einstein, Toyota
- Brand names: Solaris, Mandarine

Polish Latin script serves as the phonetic script of this system. Unlike
Japanese, which needs katakana for foreign names, Sinopolonica has no
need for a separate transliteration mechanism.

## Onomatopoeia

Onomatopoeic words remain in Latin script: bęc, łup, trach, chlup,
bum. These are sound-imitative and have no semantic content amenable to
logographic representation.

Exception: conventional onomatopoeia that has become a standard semantic
word (e.g., *grzmot* = thunder) receives a character: 雷.

## Line Breaking

Lines may break between words (at spaces) or between a character and its
Latin-script suffix if the suffix begins a new syllable. A character and
its immediately following Latin suffix should not be separated across
lines when possible. Typesetting software should treat
character-plus-suffix as a single token for line-breaking purposes.
