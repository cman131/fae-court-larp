# Storyline Separation Design

**Date:** 2026-06-07

## Goal

Separate full court storyline content from player-facing character briefs. Players get the starting hook and situation; storytellers get the full beat-by-beat breakdown.

## Approach

Keep the narrative hook (backstory + inciting tension the character knows at Revel start) in character files. Remove tactical step lists, outcome conditions, and "what your court can do" sections. Add a storyteller reference link in each character file.

## Changes

**aurora.md** — trim to opening paragraph; add link to `storyteller/storylines/court-of-storms/index.md`.

**mab.md** — trim to everything through "Someone already moved against you before the night began."; link already present; `hidden-heir.md` unchanged.

**spriggan.md** — trim to first two paragraphs; add link to `storyteller/storylines/court-of-beasts/index.md`.

**court-of-storms/index.md** — replace placeholder with full Marriage Pact content (hook + "Tonight you must" list + outcomes) plus back-reference to aurora.md.

**court-of-beasts/index.md** — replace placeholder with full Old Debt content (hook + "Direct your court members to" list + outcomes) plus back-reference to spriggan.md.
