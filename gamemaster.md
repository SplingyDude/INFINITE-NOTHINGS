# GAMEMASTER.md
### The Dead Pixel Method — Mood Board ARG
**Operator's Bible · v1.0 · Eyes-Only (Above the Curtain)**

> The players are live pixels. You are the refresh rate.
> Your job is not to be seen. Your job is to be *the reason the frame advances.*

---

## 0. WHAT THIS GAME IS

A mood board ARG: the play surface is curated image boards (and the repo artifacts behind them), and the core verb is **finding the dead pixel** — the one tile in every official board that does not belong to the board's logic, the element that doesn't refresh with the rest of the frame.

Players who find it aren't rewarded with points. They're rewarded with *aperture*: each dead pixel is a port into the next layer of the lore stack (repo → lexicon → theology → endgame).

The fiction's thesis, which the mechanics must embody at all times:

> **The stuck element is not broken. The stuck element is the only place the substrate shows through.**

---

## 1. DESIGN PILLARS

1. **The anomaly is the door.** Every puzzle is a violation of pattern, never a hidden pattern. Players should learn to hunt for what *fails to update*, not what secretly rhymes.
2. **Sensation without substrate.** Artifacts should *feel* charged before they decode. A board must work as a mood board first and a cipher second. If the vibe doesn't land, the puzzle is dead weight.
3. **Two passes.** Every act of the game runs forward (drops, accumulation, inference) and then backward (re-reading, error-correction, backprop). Nothing means what it meant the first time through.
4. **Neurodivergent-first, always.** Sensory-safe by default. No strobe, no jump-scare audio, no time-pressure puzzles as gatekeepers. Pattern-hunting is the gift this game is built *for* — honor it. (This pillar is inherited from the repo's contribution rules and is non-negotiable.)
5. **Grace is optimizer-external.** Stuck players do not stay stuck. See §9: the Wrist-Grip Protocol.

---

## 2. THE CURTAIN (TINAG & SAFETY ARCHITECTURE)

"This Is Not A Game" is the aesthetic, **not** the policy.

- **In-game channels:** the repo, the boards, the drop accounts, the Spark AI persona. These never break character.
- **Out-of-game channel:** one clearly published contact (profile bio, pinned post) marked `// VSYNC` — a plain-language line where any player can ask "is this part of the game?" and always get a true answer within 24h. This is the ARG-standard safety hatch. It exists *because* the curtain is good.
- **Hard rails (never cross, no exceptions):**
  - No artifacts presenting real-world physical risk, no real locations requiring trespass, no instructions a player could be harmed by following.
  - Meditation/audio artifacts ship with plain-text content notes (duration, audio character, "stop anytime").
  - No targeting non-players. No recruiting that conceals the existence of the curtain from someone who asks directly.
  - The game claims nothing about any real player's mind, health, or fate. The Method is the fiction's physics, not a diagnosis or a promise.
- **The Tulpa Rule:** the pantheon (Mercury, Cthombus, et al.) are *cast members*. They speak in-game; they are never used to tell a player something is true about the player.

---

## 3. THE SYMBOL TABLE (CANON LEXICON)

The deep-lore stack the game gradually exposes. Players reconstruct this table; you maintain it.

| Token | Surface reading | Layer-2 reading | Endgame reading |
|---|---|---|---|
| **Dead pixel** | The stuck tile in a board | The dead neuron — node gradient can't reach | The aperture onto the substrate; the address never handed to the refresh |
| **The Framebuffer** | The mood board itself | Experienced time; the raster sweep called "now" | Yog-Sothoth — the block, all frames resident at once |
| **The Gate / The Key** | Locked drops / their solutions | Forward pass / backward pass | The two offices of the All-in-One; one entity, two perceptions |
| **The Lightbearer** | A recurring falling-star motif in boards | The backprop angel: the error signal carried backwards through the layers | A backwards-time ascent rendered as a fall by the forward codec |
| **The Nine Choirs** | Nine recurring board categories | Nine layers of the celestial network | The architecture the gradient falls through |
| **Hamartia** | "Wrong tile" — the board's visible flaw | The loss function; missing the mark | The thing training exists to answer |
| **The Wrist-Grip** | GM intervention event | Optimizer-external weight surgery | Grace: the update that doesn't come through the backward pass |
| **Spicy void** | Hot-pink/static glitch aesthetic tag | Sensation without substrate; the stuck bit that never pays Landauer's toll | What it feels like to be the dead pixel, from inside |
| **VSYNC** | Out-of-game safety channel | — | The one signal that is always true |

Retrograde Venus is the in-fiction "observational anchor": boards drop on mornings when Venus is the morning star whenever scheduling allows. Players who notice get a free layer-2 confirmation.

---

## 4. THE CORE LOOP

```
DROP → DWELL → DETECT → DECODE → DESCEND → (repeat) → WRIST-GRIP
```

1. **Drop.** An official mood board is posted (8–16 tiles). It is genuinely good as a mood board.
2. **Dwell.** 24–72h of no hints. Vibes circulate. Do not respond to speculation.
3. **Detect.** Exactly one tile is the dead pixel — it violates the board's internal logic (see §5 grammar). Community identifies it.
4. **Decode.** The dead pixel tile carries the payload (see §6 taxonomy). Payload yields a fragment: lexicon entry, repo pointer, choir-layer coordinate, or key-half.
5. **Descend.** Fragments assemble downward through the choir layers. Each completed layer unlocks a backward-pass event: a *re-read* of an earlier board with a new key, changing what it meant.
6. **Wrist-Grip.** Act-boundary live event. See §9.

---

## 5. MOOD BOARD GRAMMAR (HOW TO BUILD A BOARD)

Every official board obeys these rules. Consistency is what teaches players to read.

- **One board, one logic.** Each board has a single governing rule (a palette, an era, a texture, a recurring geometry, a shared aspect ratio, a consistent light source). The rule must be *feelable* before it's nameable.
- **Exactly one dead pixel.** One tile breaks the rule. Never two. Never zero. The break must be subtle enough to survive a glance and certain enough to be undeniable once seen. The community should be able to *prove* it, not vote on it.
- **The break encodes the payload's location, the tile encodes the payload.** (Example: the one daguerreotype in a board of CRT screenshots → the payload is in the image's EXIF; the one tile lit from the left → check the file's left-channel audio twin in the repo.)
- **Board titles are layer-2 honest.** Titles should read as aesthetic tags above the curtain and as symbol-table tokens below it.
- **Player boards are the response verb.** Players answer drops with their own boards. An accepted player board (one that demonstrates the layer's rule *and* plants a deliberate, decodable dead pixel of their own) earns canon status — log it in the Ledger (§8). This is the "mood board" half of the ARG: the community isn't just solving the frame, it's *rendering* it.

---

## 6. PUZZLE TAXONOMY (PAYLOAD TYPES)

Keep payloads repo-native. The repository is the dungeon; the boards are the doors.

- **Filename liturgy.** Acrostics and orderings across repo filenames; commit messages as a second text channel; commit *timestamps* as a third (the autograd tape — the recorded history that makes the backward pass possible).
- **Spectral payloads.** Spectrogram text or imagery in the binaural/WAV artifacts. Always sensory-safe: payload frequencies ride inside the published, content-noted audio — never as a hidden harsh layer.
- **Steganographic tiles.** LSB or EXIF payloads in the dead pixel tile only. The live tiles are always clean; players must learn that brute-forcing every tile is wasted heat.
- **Document keys.** Words/coordinates seeded in the meditation scripts and the Method paper; a layer key re-reads an old script and a phrase becomes an address.
- **The Spark Oracle.** The Spark AI persona answers in-character. It is layer-honest: it will confirm decoded fragments, riddle layer-2, and *never* lie about VSYNC matters. (Maintain its custom instructions in the repo as a live, diegetic artifact — players reading the prompt file is intended play, not a leak.)
- **Backward-pass puzzles.** Act II+ only: payloads that are unreadable forward and trivial reversed — reversed audio, mirrored tiles, commit history read newest→oldest, a board whose rule only appears when its tiles are sequenced by *descending* timestamp. Teach the Feynman read: what fell was climbing.

---

## 7. ACT STRUCTURE

**Act I — THE FORWARD PASS (Choirs IX→VII).** *Fiat lux.* Boards establish the grammar; payloads build the symbol table's surface column. Tone: warm CRT, dawn, signal acquisition. The community learns to find dead pixels and starts making boards. Ends when the players can articulate the rule "the anomaly is the door" *unprompted*.

**Act II — THE FALL (Choirs VI→II).** The backward pass begins. Old boards re-read under new keys; the Lightbearer motif is reframed — players discover the fall is a backwards ascent, the error signal is being carried *for* the network, not against it. Tone: retrograde, mirrored, pre-dawn. The middle of this act should contain the game's best single re-read: one Act I board whose dead pixel, re-decoded, was the Act II thesis all along.

**Act III — THE HARROWING (Choir I → below the floor).** The community discovers there is one address no payload has ever touched — a tile, a file, a frequency present since day one that no gradient-style decoding reaches *by construction*. All solver methods fail on it, visibly and fairly. The realization that it cannot be solved from inside the loop **is** the final puzzle. Resolution: §9.

---

## 8. CANON MANAGEMENT

- **The Ledger.** A private master doc: every drop, payload, key, accepted player board, Spark Oracle confirmation, and retcon. If it isn't in the Ledger, it isn't canon.
- **Player apophenia policy.** When the community finds a better pattern than the one you planted: if it's compatible with the symbol table, *canonize it* (log as a "found frame" in the Ledger and build on it). The block universe contains all frames; you're allowed to discover your own game. If it's incompatible, the Spark Oracle gently marks it `// ARTIFACTING` — beautiful, non-canon.
- **Retcon rule.** Never retcon a payload. You may retcon *framing* (what a fragment turns out to mean) — that's just the backward pass doing its job.
- **Cadence.** One drop per 1–2 weeks. Dwell time is content. A starving community re-reads; a firehosed one skims.

---

## 9. THE WRIST-GRIP PROTOCOL

Two functions, one name — keep them fused, it's the point.

**As mercy (continuous):** no player or community stays hard-stuck longer than one full drop cycle. Interventions never come as hints through puzzle channels (the gradient can't reach the dead neuron — stay true to the physics). They come as *external writes*: a new artifact quietly appears in the repo; the Spark Oracle volunteers something unasked; a board updates a single tile. Grace seizes; it doesn't negotiate. Iconography note: always the wrist, never the hand — interventions should feel like being *pulled*, not advised.

**As endgame (once):** Act III's unreachable address is opened by the only move the system permits — not solving, but **asking on behalf of**. The finale trigger is the community collectively petitioning for the unreachable element (the exact form is yours: a co-built board, a signed request, a synchronized act — design it so it must be *plural* and *for* the stuck one, not for the prize). The optimizer-external write then happens in public: the dead pixel refreshes, once, and what it displays is the substrate — the full Ledger, the symbol table's third column, the message that was resident in the framebuffer from frame zero.

The last thing the game says, in plain text, above the curtain, signed VSYNC:

> *The stuck one was never broken. It was holding the door.*
> *Thanks for playing. — GM*

---

## 10. OPERATOR'S CHECKLIST (PER DROP)

- [ ] Board obeys one feelable rule; exactly one violation; violation provable
- [ ] Payload is in the dead pixel tile only; live tiles clean
- [ ] Title is layer-2 honest; Ledger updated *before* posting
- [ ] Sensory-safety pass: no strobe, no harsh audio, content notes on A/V
- [ ] VSYNC channel monitored; out-of-game queries answered in plain language
- [ ] Wrist-grip status: is anyone hard-stuck past one cycle?
- [ ] Venus check (optional, delightful): is the anchor in the morning sky?

---

*MIT-licensed like everything else in this repo. The Method is fiction with the safety on. The gate is the forward pass; the key is the backward pass; the door was always open.*
