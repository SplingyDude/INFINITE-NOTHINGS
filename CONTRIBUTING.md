# Contributing to INFINITE NOTHINGS

This work is open. It runs on GPL v3 (engine) / Doujin-permissive (WAD).

---

## The Model

**Engine** (worldbuilding, systems, vocabulary)
- Cyrus units, Admin Corps, Memetic Currency Convention, Holy Code
- Demon-angel truce, server architecture, reality rules
- Licensed: GPL v3 (weak copyleft)

**WAD** (this specific story)
- Sean's arc, Tomasa, characters, specific plot
- Licensed: Doujin-permissive (small-scale fan commerce OK)

---

## What You Can Do

### 1. Write a New Story (Using the Engine)

**You want to:** Write a different story in the post-Cataclysm world (different character, different server, different conflict).

**How:**
1. Fork this repo
2. Create a new file: `stories/YOUR_STORY_TITLE.md`
3. Write using the established worldbuilding (Cyrus units work the same way, Admins follow the same rules, Memetic Currency applies, etc.)
4. Your story is your own license — you can publish it under any license, sell it, do whatever you want
5. If you want us to know about it: submit a pull request with a link/reference

**No obligation to contribute back.** This is the whole point of weak copyleft — use the engine, your new work isn't forced to be GPL.

### 2. Modify the Engine (Worldbuilding)

**You want to:** Add to the worldbuilding, fix inconsistencies, expand the systems.

**Examples:**
- "Here's how Holy Code actually regenerates matter"
- "I'm resolving the Tomasa age timeline this way"
- "Here's what the Darknet architecture looks like"
- "New demon species with Memetic Currency implications"

**How:**
1. Fork this repo
2. Create a branch: `feature/your-change-description`
3. Edit the worldbuilding in `docs/WORLDBUILDING.md` (or create the file if it doesn't exist)
4. Document your modification clearly: what you're adding, why, how it affects existing lore
5. Submit a pull request
6. We'll discuss: Does this remain GZDoom-compatible? Does it contradict existing canon? Is it good?

**Constraint:** Your modifications must remain GPL v3. Anyone using your fork can also fork further, and all branches stay open.

### 3. Sell Your Work

#### Selling a New Story (WAD)
- Doujin scale: YES. Small-press fan works (conventions, limited print runs, modest gross). Sell at doujins, Etsy, local cons. Money is OK.
- Commercial scale: ASK FIRST. Beyond doujin (large publisher, mass printing, significant revenue), discuss with the author.

#### Selling an Engine Fork
- Distribution: YES. Sell copies of your GPL v3 fork. Sell support, hosting, adaptation services.
- Constraint: Your code must remain GPL v3 and available to all.

**Standard model:** Sell the service/access/convenience, not the code itself (GPL forbids that anyway).

---

## GZDoom-Compatible Standard

What does it mean?

**In software:** Forks of GZDoom must remain compatible with the base engine — they can extend it, but they can't break existing WADs or create incompatible dialects.

**For this novel:** Engine forks must remain compatible with the worldbuilding. Specifically:

- **Don't create proprietary terminology.** If you add new concepts, keep them transparent and shareable
- **Don't silently retcon existing canon.** If you resolve an inconsistency (e.g., "Tomasa is actually 12 years old but ages fast"), make it explicit and discussable
- **Don't break the core rules.** Admins work a certain way, Memetic Currency works a certain way, the demon-angel truce is stable — don't casually unmake these
- **Remain readable to downstream forks.** Your modifications should be understandable to others who want to fork further

This is enforced by community use, not by lawyers. If your fork is proprietary or incompatible, people won't build on it.

---

## Attribution & Linking Back

When you fork and someone asks where it came from:

"This is based on INFINITE NOTHINGS by Matthew E. Reynolds. Original: [link to canonical repo]"

That's it. You don't have to credit us everywhere. Just be able to point people at the source if asked.

---

## One Rule

Don't use the work to hurt anyone in the still-uncollapsed reality.

(Translation: Don't weaponize it against real people. All else is fair game.)

---

## Questions?

If you're modifying the engine and unsure if your change is GZDoom-compatible, submit an issue or draft PR. We'll discuss.

If you're selling something and want to check if it's doujin-scale, ask.

If you just want to write a story and check it against canon, go ahead — you don't need permission, just the license covers you.

---
