---
format: 1080x1920
duration: 22s
message: "It's not a willpower problem — it's a wiring problem, and wiring can be rewired"
arc: Recognition → Agitation → Reframe → Break → Relief → Offer
audience: Christian men who have tried and failed to quit porn on willpower and prayer alone
mode: collaborative
music: tense ambient pulse, low and unresolved, resolving to a hopeful major swell at 9s
---

## Frame 1 — You meant it this morning

- scene: Phone-glow pool breathes in a black room; the caption slams in on the first beat
- duration: 2s
- transition_in: cut
- status: animated
- type: hook
- blueprint: kinetic-type-beats (Adapt)
- poster: 1.2s
- src: compositions/frames/01-you-meant-it.html
- asset_candidates: none
- caption_verbatim: "You meant it this morning."
- handoff_out: glow-pool — center x 50%, y 46%, scale 1.0, opacity 0.62, drifting +0.4% scale/s, cold blue-white #9FB4C8 at 10% over #080B0F

Cold open, no logo, no lead-in. The screen is almost entirely black — the only thing
alive is a soft cold pool of light, as if a phone were lying face-up just out of frame.
**The hook must land inside 1 second**, so the caption is on screen by 0.35s. No face,
no body — the light does the acting. This frame's job is a single flinch of recognition:
*he knows this room.*

### Shot sequence

- **Scene 1 (0.0–0.35s)** — Ground already present at t=0 (no fade-up; a fade wastes the
  hook window). Glow-pool sits at 46% height, opacity 0.55. One 1px ember hairline sits
  at the very bottom of the safe area, 18% width, as the only chrome.
  Layout: `full-bleed dark register, single radial light source, no text yet`.
  Motion: `ambient-glow-bloom` — glow breathes 0.55→0.62 opacity, 6s loop (reads as
  almost-still across 2s).
- **Scene 2 (0.35–0.9s)** — Caption slams in, centered, `display` ramp at 8.5cqw,
  lowercase, cream. It arrives as ONE unit, not word-by-word — a word-by-word build
  would spend the whole hook window.
  Motion: `kinetic-beat-slam` — y +24px → 0, opacity 0 → 1, scale 1.04 → 1.0, 0.28s,
  `power4.out`. No blur, no glow on the type itself.
- **Scene 3 (0.9–2.0s)** — Hold. The caption does not move. The glow keeps breathing and
  the hairline creeps 18% → 24% width. Stillness here is deliberate: it lets the line be
  read twice.
  Motion: `ambient-glow-bloom` (continuing).

## Frame 2 — You're here again

- scene: Three pain lines land one at a time in the same darkness, the last one alone
- duration: 3s
- transition_in: cut
- status: animated
- type: pain_point
- blueprint: kinetic-type-beats (Reproduce)
- poster: 2.4s
- src: compositions/frames/02-here-again.html
- asset_candidates: none
- caption_verbatim: "You prayed about it. You deleted the apps. You're here again."
- handoff_in: glow-pool — center x 50%, y 46%, scale 1.0, opacity 0.62, drifting +0.4% scale/s, cold blue-white #9FB4C8 at 10% over #080B0F
- handoff_out: glow-pool — center x 50%, y 46%, scale 1.0, opacity 0.28, dimming, cold blue-white #9FB4C8 at 10% over #080B0F

**Hard cut, identical ground** — the shot list says "same darkness", so nothing about the
room changes. Only the words move. The caption is one sentence of client copy but it has
three beats in it, and the rhythm *is* the agitation: two things he did right, then the
verdict. The third line must land alone, with air around it.

### Shot sequence

- **Scene 1 (0.0–0.8s)** — "You prayed about it." enters at 5.2cqw, cream, upper third.
  Motion: `discrete-text-sequence` — hard-cut in, no fade (0.0s in, holds).
- **Scene 2 (0.8–1.6s)** — "You deleted the apps." enters directly beneath it, same size,
  same treatment. Line 1 drops to 55% opacity as line 2 arrives — the past tense receding.
  Motion: `discrete-text-sequence` + opacity step on line 1.
- **Scene 3 (1.6–2.4s)** — Both earlier lines fall to 22% opacity and the third line,
  **"You're here again."**, slams in at 7.5cqw in **ember `{colors.fire-orange}`** — the
  first color in the video. It is the only ember moment before the break, and it is the
  accusation.
  Motion: `kinetic-beat-slam` — scale 1.06 → 1.0, 0.24s, `power4.out`.
- **Scene 4 (2.4–3.0s)** — Hold, then the glow-pool begins to dim (0.62 → 0.28) under the
  held text. The room is going out; we are about to leave it.
  Motion: `ambient-glow-bloom` reversed (dim, not bloom).

## Frame 3 — It's not a willpower problem

- scene: Slow push into a field of heavy iron chains, one caption held low
- duration: 4s
- transition_in: crossfade
- status: animated
- type: pain_point
- blueprint: compose (slow push-in on a static set — no menu shape fits a held camera move)
- poster: 3.0s
- src: compositions/frames/03-chains.html
- asset_candidates: none
- caption_verbatim: "It's not a willpower problem."
- handoff_in: glow-pool — center x 50%, y 46%, scale 1.0, opacity 0.28, dimming out to 0 across the crossfade
- handoff_out: chain-X — center x 50%, y 50%, scale 1.18, opacity 1.0, pushing in at +4.5% scale/s, link centre at exact frame centre, unbroken

The reframe beat, and the first appearance of the cover's motif. Four heavy chain runs
cross the frame in an X, converging at dead centre — the **exact geometry of the book
cover**, so that when it snaps in Frame 4 and appears again on the cover in Frame 6, it
reads as one object seen three times. Lighting is low-key: a single raking light from
upper-left, links falling to near-black at the edges.

The camera does one thing for four seconds: **push in, slowly, without stopping.** The
restraint is the point — after the staccato of Frame 2, the video suddenly holds still
and gets heavy. That contrast is what sells the line.

### Shot sequence

- **Scene 1 (0.0–0.6s)** — Crossfade completes from Frame 2's dying glow. Chain-X is
  already at scale 1.0, centred, 70% opacity, edges crushed to black.
  Layout: `full-bleed dark register, chain-X converging at centre, vignette to #080B0F`.
  Motion: `depth-of-field-blur` — edges 3px blur → 0 across the scene as the eye settles.
- **Scene 2 (0.6–2.2s)** — The push begins and never stops: scale 1.0 → 1.10, linear-ish
  `power1.inOut`, no easing hitch. Opacity 70% → 100%. The raking light creeps 4% right.
  Motion: `multi-phase-camera` (phase 1 of 2 — continuous push).
- **Scene 3 (2.2–3.0s)** — Caption enters LOW (68% height, below the convergence point so
  it never covers the link that is about to break), `h1` ramp 6.8cqw, cream, lowercase.
  Motion: `kinetic-beat-slam` — y +18px → 0, 0.3s, `power3.out`.
- **Scene 4 (3.0–4.0s)** — Push continues to scale 1.18. A single ember glint appears on
  the centre link at 3.6s — 2% opacity, 8px — the first hint of heat, well under conscious
  notice. This is the seed the burst grows from.
  Motion: `multi-phase-camera` (phase 2) + `ambient-glow-bloom` (glint, barely on).

## Frame 4 — Wiring can be rewired

- scene: The centre link snaps; a white-gold ember burst throws sparks; the reframe lands
- duration: 3s
- transition_in: cut
- status: animated
- type: product_intro
- blueprint: compose (the break is the signature move — no menu shape covers a physical snap)
- poster: 1.0s
- src: compositions/frames/04-break.html
- asset_candidates: none
- caption_verbatim: "It's a wiring problem. And wiring can be rewired."
- handoff_in: chain-X — center x 50%, y 50%, scale 1.18, opacity 1.0, pushing in at +4.5% scale/s, link centre at exact frame centre, unbroken
- handoff_out: ember-core — center x 50%, y 50%, scale 0.4, opacity 0.5, contracting, gold #E8A23D core cooling toward ember #D98324

**The turn of the entire ad, and the only frame that spends the orange register.** Hard
cut from Frame 3 at the exact same scale and position — the chain does not jump, so the
snap reads as *happening to the thing we were just looking at*, not as a new shot.

The break is a **three-frame event**: hold → snap → light. Sparks throw outward along the
four chain runs, so the energy travels the geometry we already established rather than
spraying randomly. The white-gold core is the hottest value in the video; nothing later
is allowed to be brighter.

### Shot sequence

- **Scene 1 (0.0–0.18s)** — Inherits the push at scale 1.18. For 3 frames, nothing. The
  chain holds under load. (This micro-hold is what makes the snap feel violent.)
  Motion: `multi-phase-camera` (inherited push, decelerating to a stop).
- **Scene 2 (0.18–0.45s)** — **SNAP.** The centre link separates: two halves rotate apart
  ±14° and translate ±22px along their chain runs, `power4.out`, 0.14s. Simultaneously
  the ember core detonates from 0 → scale 1.0, white-gold `{colors.gold}` centre bleeding
  to ember `{colors.fire-orange}` at the rim. A one-frame full-frame flash at 18% white
  sells the impact.
  Motion: `particle-burst` (sparks along the four runs, 34 particles, gravity-weighted) +
  `center-outward-expansion` (the core) + `kinetic-beat-slam` (the flash).
- **Scene 3 (0.45–1.4s)** — Sparks arc out and fall, cooling gold → ember → out. The core
  contracts 1.0 → 0.55 and the frame breathes back. Chain halves settle, still swinging
  ~2°, `sine-wave-loop`.
  Motion: `particle-burst` (decay) + `sine-wave-loop` (chain settle).
- **Scene 4 (1.4–3.0s)** — Caption arrives in two beats, straddling the break so the
  burst is never covered: **"It's a wiring problem."** above the break at 5.4cqw cream
  (1.4s), then **"And wiring can be rewired."** below it at 6.4cqw in gold
  `{colors.gold}` (2.0s) — the promise, in the hottest color, at the hottest moment.
  Motion: `discrete-text-sequence` (beat 1) → `kinetic-beat-slam` (beat 2, the payoff).

## Frame 5 — The plan

- scene: Night crossfades to a warm dawn wash; three benefit lines accumulate
- duration: 5s
- transition_in: crossfade
- status: animated
- type: benefit_highlight
- blueprint: grid-card-assemble (Adapt — vertical accumulating list, no cards)
- poster: 3.8s
- src: compositions/frames/05-the-plan.html
- asset_candidates: none
- caption_verbatim: "A 90-day plan. Brain science, real tools, and grace instead of shame."
- handoff_in: ember-core — center x 50%, y 50%, scale 0.4, opacity 0.5, contracting, gold #E8A23D core cooling toward ember #D98324; it expands and diffuses into the dawn wash rather than cutting
- handoff_out: dawn-wash — full-bleed, gold #E8A23D at 14% top-weighted, opacity 1.0, static; broken-chain silhouette at 8% opacity lower third

The relief beat. The shot list calls for "night dissolves to a dawn window" — rendered
**without a window and without a man**, per the no-people constraint. Instead the ember
core from Frame 4 *becomes* the dawn: it expands, loses its edge, and turns into a warm
gradient wash across the top of the frame. Cause and effect, carried by one element.

The broken chain stays visible in silhouette at the bottom, at 8% — quiet evidence, not
a callback gag.

This is the only frame with three enumerated items, so it is the only frame that
accumulates rather than replaces.

### Shot sequence

- **Scene 1 (0.0–0.9s)** — Crossfade. Ember core scales 0.4 → 6.0 while dropping to 14%
  opacity, becoming the dawn wash. Ground shifts #080B0F → a top-weighted gold gradient.
  The cold blue of Frames 1–2 is fully gone; this is the first warm ground.
  Motion: `theme-crossfade-morph` — the night→dawn temperature shift, 0.9s, `power2.inOut`.
- **Scene 2 (0.9–1.7s)** — **"A 90-day plan."** lands alone, centred, `h1` 7.2cqw, cream,
  lowercase. It gets its own beat because it is the offer.
  Motion: `kinetic-beat-slam`.
- **Scene 3 (1.7–3.6s)** — The three mechanisms stack beneath it, 0.42s apart, each with a
  1px ember hairline to its left (the preset's `/` bullet, restyled as a rule):
  `brain science` → `real tools` → `grace instead of shame`. Body ramp at 3.4cqw, cream.
  The third line is ember `{colors.fire-orange}` — it is the emotional differentiator and
  the one Christian men are actually buying.
  Motion: `waterfall-entry` — staggered y +16px → 0, opacity 0 → 1, 0.34s each,
  `power3.out`.
- **Scene 4 (3.6–5.0s)** — Everything holds. The dawn wash brightens 14% → 18% across the
  full scene, very slowly. Broken-chain silhouette fades up 0% → 8%.
  Motion: `ambient-glow-bloom` (the wash).

## Frame 6 — Endcard

- scene: Book cover on navy, ember divider, product name and CTA
- duration: 5s
- transition_in: cut
- status: animated
- type: cta
- blueprint: titlecard-reveal (Reproduce)
- poster: 3.5s
- src: compositions/frames/06-endcard.html
- asset_candidates: none
- caption_verbatim: "The 90-Day Battle Plan" / "Quit for good in 90 days — link in bio."
- handoff_in: dawn-wash — full-bleed, gold #E8A23D at 14% top-weighted, opacity 1.0, static; hard cut extinguishes it back to #080B0F navy ground

The ask. Calm, still, and long — 5 seconds is a lot of endcard for a 22s ad, and that is
correct: this is the frame people screenshot, and TikTok will loop back to the hook
anyway. **One restrained move, then a full hold.**

Product name is **"The 90-Day Battle Plan"** — matching the landing page and the
stan.store/battleplan checkout, per your confirmation. It is not "The Freedom Protocol".

**Safe area matters most here.** TikTok's UI eats roughly the bottom 380px and the right
180px. The CTA line sits above 1540px, and nothing meaningful goes right of 900px.

### Shot sequence

- **Scene 1 (0.0–0.5s)** — Hard cut to flat navy `{colors.ink-black}`. Cover springs in
  centred, upper-middle, occupying ~52% of frame height, sharp-cornered, 1px
  `{colors.border-dark}` edge, no drop shadow.
  Motion: `spring-pop-entrance` — scale 0.94 → 1.0, opacity 0 → 1, 0.42s, gentle
  overshoot. This is the one restrained move.
- **Scene 2 (0.5–1.1s)** — Ember divider draws outward from centre beneath the cover:
  a 2px rule, 0 → 42% width, gold `{colors.gold}` at the centre cooling to ember
  `{colors.fire-orange}` at the tips — the burst geometry, flattened into a line.
  Motion: `svg-path-draw` — centre-out, 0.5s, `power2.out`.
- **Scene 3 (1.1–1.9s)** — **"the 90-day battle plan"** sets beneath the divider,
  `display` ramp 9cqw, lowercase, cream, negative-tracked. The preset's signature move:
  type large enough to stop reading as text.
  Motion: `kinetic-beat-slam`.
- **Scene 4 (1.9–2.6s)** — CTA line: **"Quit for good in 90 days — link in bio."** at
  3.2cqw, `{colors.cream-muted}`, sitting above the 1540px safe line. Beneath it, a mono
  kicker in ember: `STAN.STORE/BATTLEPLAN`.
  Motion: `discrete-text-sequence`.
- **Scene 5 (2.6–5.0s)** — Full hold, 2.4 seconds, nothing moving except a barely-there
  ember bloom on the divider (opacity 0.9 → 1.0 → 0.9, 3s). Stillness is the payload.
  Motion: `ambient-glow-bloom`.

## Video direction

**Thesis.** One idea carries the whole ad: *the problem is mechanical, not moral.* Every
frame before 9s builds the weight of the mechanism; every frame after it shows the
mechanism broken. Nothing in this video shames the viewer — the copy indicts the wiring,
never the man.

**Sound-off first.** Assume no audio. The burned-in captions carry 100% of the message and
are never decorative. Music is atmosphere only: a low, unresolved, tense pulse under
Frames 1–3, resolving to a hopeful major swell **timed to land on the snap at 9.0s**, then
open and warm through Frames 5–6. The swell's attack is the sync point — not the bar line.

**Colour as temperature, not decoration.** The video runs cold → hot → warm. Frames 1–2 are
cold blue-white on near-black. Ember first appears as a single accusatory word at ~4.4s.
The break at 9s is the only white-gold moment and the only spend of the orange register.
Frames 5–6 sit in recovered warmth. Gold is always the *inner, hotter* value; ember is the
outer, cooler one — one fire at two temperatures, never two flat accent colours.

**Motion doctrine.** Two speeds only, and the contrast between them is the edit. Frames 1–2
are **staccato** — hard cuts, slams, no eases longer than 0.3s. Frame 3 is a single
**unbroken four-second push** that never stops. Frame 4 is the **collision** of the two.
Frames 5–6 **decelerate to stillness**. No continuous ambient drift anywhere except the
glow/wash breathing; nothing bounces; nothing loops decoratively.

**The chain is one object, seen three times.** Same X geometry, same convergence point at
frame centre, in Frame 3 (whole), Frame 4 (breaking), and Frame 6 (on the cover). Workers
must not re-invent the chain layout per frame — the convergence sits at exactly 50%/50% in
all three.

**Type.** Barlow Condensed, lowercase, weight 700–900, negative-tracked, for every caption.
IBM Plex Mono uppercase for chrome only (the URL kicker). Regular Barlow for the benefit
lines in Frame 5. No uppercase display anywhere; no italics; no letter-by-letter builds
except where explicitly specified.

**Hard constraints (non-negotiable).** No faces, no bodies, no people, no photographic
human presence of any kind. No explicit or sexual imagery, and no visual euphemism for it
either. Symbolic and atmospheric only. Caption copy is client-locked: re-weight or re-break
lines for rhythm, never reword.

**Safe area (9:16 / TikTok).** Keep all meaningful content inside x: 60–1020px and
y: 220–1540px. TikTok's caption block, CTA button and right-hand action rail sit outside
that box. Frame 6's CTA line and Frame 3's low caption are the two tightest cases.
