# INFINITE NOTHINGS — Project Context for Claude

**Last Updated:** May 26, 2026
**Status:** Line-edited. Infrastructure documents (README, CONTRIBUTING) added this session. Awaiting author review of worldbuilding inconsistencies.

---

## Project Overview

**Title:** INFINITE NOTHINGS: ADMIN, Book One
**Author:** Matthew E. Reynolds
**Genre:** Hyperpunk (original genre)
**Word Count:** ~63,800
**Structure:** Prologue + 27 chapters across 2 acts + epilogue
**Audience:** Gamers who don't know what they want to read
**Framing:** Open-fragment supersigil (locked, May 2026)

---

## What the Work Is

A first-person narrative. Sean (narrator, 18 → 27 across story) awakens from a coma post-transformation into a Second-Generation Admin — a human converted into a reality-mending entity made of "Holy Code" instead of flesh. He inhabits a post-Cataclysm world 204 years after his parents accidentally broke reality.

The narrative is self-aware lore-dumping (Sean is autistic; the dumping is in-character). Gamer vocabulary. High cosmic stakes (reality repair, demon-angel truce, hackers vs Admins, Azathoth as final boss). Themes: identity, confidence, disability, love, sacrifice.

The novel centers on Sean's relationship with Tomasa (a Succubus who is his wife), their mission to prevent reality collapse via Cain's virus, and the final confrontation with Azathoth (which implodes Cain and erases part of creation).

---

## Conceptual Framing (Added May 2026)

The author identifies the project as an **open-fragment supersigil** — a deliberate inversion of the Romantic-era unauthorized-fragment problem (Byron's *Fragment of a Novel* → Polidori's *The Vampyre*, completed without consent and falsely attributed by Henry Colburn).

Rather than a fragment completed unethically by others, the project is released as an *authorized* fragment with licensing attached:

- Engine (worldbuilding) under GPL v3 for legitimate fork
- WAD (specific story) under doujin-permissive for fan continuation
- Every legitimate downstream fork is treated as another iteration of the supersigil (Morrison's term)

**Inspirations:** the Doom modding tradition (especially UZDoom — the October 2025 fork of GZDoom over AI-code provenance), *Brutal Doom*, Krinkels' *Madness Combat*, and the Romantic-era fragment tradition as a structural negative example.

---

## Editorial Work Completed

### 41 Mechanical Line Edits Applied (Previous Session)

1. **Dialogue tag capitalization** (24 fixes)
   - After ?, !, or comma+closequote, speech verbs lowercase: `?" Asked Agrat.` → `?" asked Agrat.`, `!" She shouts` → `!" she shouts`
2. **Grammar fixes** (11 fixes)
   - "of Tomasa and I" → "of Tomasa and me" (object case)
   - "tears on her eyes" → "tears in her eyes" (idiom)
   - "shot Tomasa from his other arm" → "with his other arm"
   - "munched on them" (popcorn) → "munched on it" (mass noun)
   - "Were a neurotypical person... to survive" (added missing infinitive)
   - "G-d Called" → "G-d called" (mid-sentence verb)
3. **Hyphenation** (4 fixes)
   - "newly-received" → "newly received" (-ly adverbs don't hyphenate)
   - "networked-synapses" → "networked synapses"
   - "manmade" → "man-made"
4. **Whitespace** (1 category) — collapsed multiple spaces to single spaces

### Permission Notice Rewritten

Replaced legalistic MIT-style license with **Sean's voice version**, implementing the GPL v3 + doujin-permissive model:

> This server is open. It runs on GPL v3 — GZDoom standard.
> The engine is yours... The WAD is fanfiction-grade...
> Engine forks must stay GZDoom-compatible — readable to the next fork, no proprietary dialects of the worldbuilding.

### Infrastructure Documents Added (This Session — May 26, 2026)

- `README.md` — public-facing introduction; open-fragment supersigil framing; inspirations; licensing summary; provenance note
- `CONTRIBUTING.md` — engine/WAD distinction; "GZDoom-compatible standard" expectation; provenance ethics; PR/fork guidance
- This `CLAUDE_CONTEXT.md` — updated to reflect new framing, new files, locked provenance position, and the SplintyDude → SplingyDude typo fix in the Contact section

All three drafted by AI from author-established notes and approved by author before commit. No creative input on the manuscript itself.

---

## Licensing Model (Locked)

### Engine Layer — GPL v3 (Weak Copyleft)

**What it includes:** Worldbuilding, systems, vocabulary
- Cyrus units, Admin Corps, Second-Gen Admin mechanics
- Memetic Currency Convention
- Holy Code, Holy Spirit Cipher
- Demon-angel truce, post-Cataclysm cosmology
- Server forks, reality rules

**Permissions:**
- Fork it, modify it, build with it
- If you modify the engine itself, modifications stay GPL v3 and ride back to the community
- If you only *use* the engine (don't modify it), your new work is not copyleft — license your story however you want

**Commercial:** Engine forks can be sold if they remain "GZDoom-compatible standard" (readable to downstream forks, no proprietary dialects)

### WAD Layer — Doujin-Permissive

**What it includes:** This specific story
- Sean's arc, Tomasa, the specific plot
- Characters, specific scenes, narrative flow

**Permissions:**
- Write fanfiction using these characters
- Continue the story
- Retcon it
- Sell at doujin scale (small-press fan works: conventions, modest print runs, limited runs)

**Commercial at scale:** Beyond doujin, commercial use requires author discussion first

### Voice

Permission notice is in Sean's narrative voice (Krinkels-with-teeth style). No formal legal boilerplate in the manuscript. README and CONTRIBUTING.md use a conventional editorial voice.

---

## Provenance Position (Locked, May 2026)

The project sits on the UZDoom side of the GZDoom AI-code argument:

- **No AI-generated prose in the manuscript.**
- **Editorial line-editing by AI is acceptable** (mechanical fixes only — capitalization, hyphenation, object case, idiom).
- **Infrastructure docs** (README, CONTRIBUTING, this file) drafted with AI assistance from author-established notes, then reviewed and approved by author.
- **No AI involvement in worldbuilding, plot, character, or voice decisions.**

This provenance position is itself a structural statement consistent with the open-fragment supersigil framing.

---

## Worldbuilding Inconsistencies (Flagged for Author Decision)

The editor's report flagged 11 inconsistencies that are author decisions, not "fixes":

1. **Chapter numbering breaks.** Act One: `CHAPTER 01` (caps, zero-padded) → `CHAPTER 07`. Act Two: `Chapter 5` (title case, no padding) → `Chapter 24`. Overlaps. Either typo, restart at 1, or intentional meta-glitch.
2. **Tomasa's age.** She's 126 when Sean is 18 (Ch. 12). But she was found as a newborn, raised since infancy alongside Sean. Either: (a) succubi age slowly (establish early), or (b) age is wrong.
3. **Tomasa's surname "Firekind."** She's a foundling. Who gave her the name? Or did Sean's parents assign it, making it not her "family name" in the marriage tradition?
4. **Sean's age timeline.** Age 18 in prologue (transformation). Age 27 when Cain arrives (Ch. 13). Implies 9 years passed. Narrative reads as weeks/months. Time-skip needs signaling or timeline clarification.
5. **Cyrus Mark II — two devices?** Sean's: "Cyrus 1230 Mark II" (general Admin implant). Tomasa's: "Cyrus Mk. II Low-Functioning Succubus-Related..." (medical device). Same Mark II? Is it a platform with variants?
6. **Lilith vs Lilith the Young.** Two characters or one with different dream-self? Unclear.
7. **The smell question.** After transformation: "I couldn't smell." Later in Hell: "I can smell!" transition is unearned. Needs explanation.
8. **G-d's coma vs Y-hweh's action.** G-d is in coma, but Y-hweh appears, hands out items, "left his retirement." Same entity or separate? Needs clarification.
9. **Death rules.** By end: "Can't kill what's already dead" (return rule). Established too late; earlier deaths don't invoke it.
10. **Holy Spirit Cipher vs Holy Code.** Is Holy Code the output of the Cipher, or same thing?
11. **"First Gen" capitalization.** Inconsistent (First Gen / first gen / First gens). Pick one style.

**Status:** All flagged, not rewritten. Author to resolve in next pass.

---

## Key Decisions Made

- **Scope of editorial AI:** Line-edit only on manuscript. No plot, content, character, or voice changes. Infrastructure docs drafted from author notes with author review.
- **Worldbuilding:** Identified, flagged, not fixed. Author discretion.
- **License:** GPL v3 (engine) + doujin-permissive (WAD), weak copyleft, Krinkels-with-teeth voice for the in-manuscript permission notice
- **Commercial:** Doujin scale for WADs OK. Engine forks need GZDoom-compatible standard (no proprietary dialects).
- **Platform:** Static hyperfiction on GitHub
- **Provenance:** UZDoom-side position locked; no AI in load-bearing creative or licensable layers
- **Framing:** Open-fragment supersigil (May 2026)

---

## Outstanding Work

### 1. Author Review (Next)

- [ ] Review the new `README.md` and `CONTRIBUTING.md` drafts before commit
- [ ] Review `INFINITE_NOTHINGS_line_edited.docx`
- [ ] Review `EDITORS_REPORT.md` §3 (Worldbuilding Inconsistencies)
- [ ] Decide on each flagged item (resolve or leave as-is)
- [ ] Provide decisions to editor

### 2. Second Editorial Pass (After Author Review)

- [ ] Revise worldbuilding sections based on author decisions
- [ ] Final line-edit polish (flow, final copy-edit)
- [ ] Prepare for publication

### 3. GitHub Repo Setup

- [x] Repo exists at github.com/SplingyDude/INFINITE-NOTHINGS
- [ ] Commit new `README.md`, `CONTRIBUTING.md`, updated `CLAUDE_CONTEXT.md`
- [ ] Update the GitHub repo "About" description (set via the web UI, not a file): currently says "Inspired by Madness Combat and UZDoom"; consider adding a parenthetical so first-time visitors don't read UZDoom as a typo for GZDoom
- [ ] Confirm LICENSE file contains GPL v3 full text

---

## Files in This Repo

```
infinite-nothings/
├── README.md                          # Public-facing intro, open-fragment supersigil framing
├── CONTRIBUTING.md                    # Fork/contribute guidance, provenance ethics
├── LICENSE                            # GPL v3 full text
├── CLAUDE_CONTEXT.md                  # This file
├── EDITORS_REPORT.md                  # Full editorial notes, line edits, flagged issues
├── manuscript/
│   ├── INFINITE_NOTHINGS_line_edited.docx
│   └── INFINITE_NOTHINGS.md           # (markdown version, optional)
└── docs/
    └── WORLDBUILDING.md               # (reference, optional)
```

---

## How to Use This File (For AI Sessions)

**If you're restoring context post-wipe:**

1. You are Claude (or another AI)
2. You've been given this file as context
3. Load it entirely into your understanding
4. You now know:
   - What the project is (a hyperpunk novel framed as an open-fragment supersigil)
   - What's been done (41 line edits applied, GPL v3 licensing locked, README + CONTRIBUTING added, worldbuilding issues flagged)
   - What's pending (author review of new docs, worldbuilding resolution, final edit pass)
   - What the constraints are (GPL v3 engine + doujin WAD, line-edits-only scope on manuscript, infrastructure docs okay with author review, no AI in creative or licensable layers)

**For any new request from the author:**

- Check this file first
- Load relevant documents from the repo (EDITORS_REPORT.md, CONTRIBUTING.md, LICENSE)
- Maintain consistency with locked decisions
- Support the next phase of work as outlined

---

## Quick Reference

### World

- **Timeline:** Post-Cataclysm (204 years after reality-break by Sean's parents)
- **Reality Status:** Broken, being repaired by Admins using Holy Code
- **Key Entities:** G-d (comatose), Hackers (enemy), demons/angels (truce), Servers (forked realities)
- **Economy:** Memes/ideas as currency

### Characters (Key)

- **Sean Firekind** — Narrator, Second-Gen Admin, autistic, transformed
- **Tomasa Firekind** — Succubus, Sean's wife, royalty
- **Cain** — Antagonist, immortal, virus creator
- **Truth** — Y-hweh's aspect, also called "Mom"
- **Lilith** — Demon queen, Sean's mother-in-law
- **Lucifer** — Fallen angel, antagonist-turned-ally

### Tone

- First-person, conversational
- Self-aware lore-dumping (in-character quirk)
- Gamer vocabulary and reference points
- Cosmic horror mixed with romantic intimacy
- Meta-textual awareness (narrator knows they're narrating)

---

## Contact

**GitHub Repo:** <https://github.com/SplingyDude/INFINITE-NOTHINGS>
**Original Author:** Matthew E. Reynolds
**Editor (this session):** Claude

---

**End of context file.** Paste this into Claude, and full project context is restored.
