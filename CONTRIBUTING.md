# Contributing to INFINITE NOTHINGS

This isn't a software project, but it borrows software-project conventions because the licensing model is structural and the structure matters. Read this before forking.

## The engine/WAD distinction

The project is licensed in two layers, modeled on the source-port convention of separating the engine from the WAD content it loads.

### The engine — GPL v3

The engine is the *generalizable* part of the work. Anything that could be lifted out of this specific story and reused in another:

- Second-Gen Admins, Cyrus units, Holy Code
- The Holy Spirit Cipher
- The demon-angel truce after the Cataclysm
- The 204-years-after-reality-broke timeline frame
- Memetic Currency Convention
- The Hacker/Admin opposition
- Server-as-forked-reality cosmology

Weak copyleft. If you modify the engine itself — change a rule, add a faction, extend the cosmology — your modifications return to the commons under GPL v3. If you only *use* the engine without modifying it (write a story set in the world without altering the rules), your story is yours under whatever license you pick.

### The WAD — doujin-permissive

The WAD is this *specific* story. Sean. Tomasa. The arc from Sean's awakening to the implosion of Cain. The specific scenes, the specific phrasing, the named beats.

- Fanfiction is welcome.
- Continuations are welcome.
- Retcons are welcome.
- Small-press editions for conventions or limited print runs are welcome.
- Commercial use beyond doujin scale (mass-market editions, anthology inclusion, adaptation rights) requires a conversation with the author.

## "GZDoom-compatible standard"

Borrowed from the source-port community: engine forks should remain *readable* to downstream forks. No proprietary dialects of the worldbuilding. If you split off, others should be able to follow your fork and understand how it relates to the trunk.

Practically: don't rename Cyrus units to something only your fork knows. If you change a rule, document the change. The point of an open engine is that the next fork can build on yours.

## Provenance

This project sits on the UZDoom side of the AI-code argument, and the position carries across:

- **No AI-generated prose in the manuscript.** Mechanical editorial assistance from AI (capitalization, hyphenation, idiom, object case) is acceptable; AI prose generation is not.
- **No unvetted AI code in engine forks** if you ever build software around this. If you use AI assistance for tooling, scope it the way copy-editors are scoped: mechanical corrections only, never load-bearing creative or licensable material.

Forks that violate this position break engine compatibility. Forks that respect it stay in the family.

## How to contribute

- **Typo or line-edit fix to the trunk:** open a pull request against the relevant file. Keep the PR scoped to mechanical fixes. Plot, character, and voice changes are not accepted into the trunk.
- **Engine extension you'd like merged upstream:** open an issue first describing the addition and how it coheres with existing cosmology, then a PR. Engine additions must be consistent with what's already there.
- **Your own WAD (a story set in the world):** don't PR it to this repo. Fork the repo, or start your own and link back. Continuations and retcons belong in your own space.
- **Engine fork:** see above. Stay readable. Document divergences in your README.

## Voice

The permission notice inside the manuscript is in Sean's first-person voice. This document and the README are in a conventional editorial voice. Contributions to engine documentation can use either register; contributions to the manuscript itself should match the existing first-person narrator.

## Author

Matthew E. Reynolds.
