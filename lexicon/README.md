---
title: "Lexicon Organization"
---

## Structure

The lexicon is organized into four files, each serving a different
purpose:

- **core-500.md** — The essential 500 characters needed for everyday
  Polish literacy. This is the minimum viable character set. A reader
  who masters these 500 characters can navigate most non-specialist
  texts. (Status: placeholder, awaiting compilation.)

- **everyday.md** — The complete everyday register inventory. All
  characters from the common/Japanese kanji pool, organized by semantic
  domain. (Status: placeholder.)

- **learned.md** — The complete learned register inventory. All
  Classical Chinese characters assigned to Latinate/Greek stems,
  organized by source language and semantic domain. (Status: placeholder.)

- **suffixes.md** — All productive derivational suffixes that receive
  characters, with their assigned characters and productivity notes.
  (Status: placeholder.)

## Entry Format

Each lexicon entry should follow this format:

```text
## 心 — serce (heart)

- **Register:** everyday
- **Polish stem(s):** serc-, serdecz-
- **Readings:** serce (NOM), serca (GEN), sercu (DAT), sercem (INST)
- **Derivations:** 心eczny (serdeczny = heartfelt)
- **Learned doublet:** 衷 (kardio-)
- **Frequency rank:** [TBD]
- **Notes:** Also used metaphorically for "core" or "center."
```

## Compilation Methodology

The Core 500 should be compiled by:

1. Taking a frequency-ranked Polish word list (e.g., from the NKJP
   corpus).
2. Decomposing each word into morphemes per the rules in
   `docs/07-derivation.md`.
3. Ranking morphemes by frequency of occurrence.
4. Assigning characters to the top 500 semantic morphemes.
5. Cross-checking that the resulting set covers common everyday
   communication.

## Contributing to the Lexicon

See `CONTRIBUTING.md` for guidelines on proposing new character
assignments, challenging existing ones, or reporting gaps.
