---
name: tv-episode-anki-deck-bilingual
description: Extract, clean, and convert English or German TV show subtitles into an Anki-compatible vocabulary learning deck (CEFR B2-C2) with grammar annotations and dual example sentences.
---

# Universal TV Episode Anki Deck Generator (English & German)

## Overview & Goal
This skill processes English or German TV episode subtitles, cleans noise, filters 50 target vocabulary items (CEFR B2–C2), enriches them with language-specific grammar metadata, and outputs a formatted table for direct Anki import.

---

## Input Format
Provide the request in one of the following styles:

```text
Show Name: [Title in English, German, or Original]
Season & Episode: S[2 digits]E[2 digits]
Target Language: [English / German]
Subtitles (Optional): [Paste SRT/VTT text here if offline or unavailable via search]
