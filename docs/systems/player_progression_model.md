# Overview

Progression is narrative-first, skill-driven, and gated by three interlocking meters:

Skills (clusters with levels 1–10)

Gravity (0–100) — openness toward the sect

Evidence Score (0–20) — how many distinct, interpreted clues the player has


Act transitions, access to scenes, and available editorial levers are determined by combinations of these three. Skill increases unlock new internal-voice options, dialogue branches, ritual outcomes, and report-building components.
---

# Table of Contents 

1. [Starting State](#1-starting-state-prologue-act-i-opening)
2. [Mid-game abilities](#2-mid-game-abilities-act-ii-integration)
3. [Late-game narrative tools](#3-act-iii-pre-report)
4. [Crossroad Choices (Final branching mechanics)](#4-crossroad-choices-final-branching-mechanics)
5. [Ending Map — quick reference](#5-ending-map-quick-reference-6-major-epilogue-clusters)
6. [Progression Metrics & Implementation Suggestions](#6-progression-metrics--implementation-suggestions)
7. [Example Encounters showing progression interaction](#7-example-encounters-showing-progression-interaction)
8. [UI & UX suggestions for progression feedback](#8-UI--UX-suggestions-for-progression-feedback)
9. [Quick design checklist to implement immediately](#9-quick-design-checklist-to-implement-immediately)

---

# 1) Starting State (Prologue / Act I opening)

Player archetypes: pick one Bias Triad at character creation — each gives +2 to three skills (on a 1–10 scale), and a small starting Gravity shift (+/-).

Example Triads (start values assume baseline skill = 3):

Skeptic: +2 Critical Reason, +2 Skeptic’s Edge, +2 Pattern Recognition. Gravity -10.

Empath: +2 Empathic Entry, +2 Emotional Reading, +2 Charm. Gravity +10.

Curious Generalist: +2 Detail Sense, +2 Contextual Memory, +2 Investigative Instinct. Gravity 0.


Start meters example:

Skills: most at 3, boosted by triad

Gravity: 40 (baseline) ± triad modifier (range 30–50)

Evidence Score: 0

Inventory: Notebook, recorder (basic), one “lead” (police report)


What the player CAN do at start:

Move through valley zones, spot obvious clues (Perception rolls at easy DCs)

Ask basic questions (charm/authority checks)

Join minor social scenes but are treated as an outsider

See first-level internal monologue options (limited voices active)


Design notes: Early checks are forgiving to teach systems. Failures still progress, but along divergent (shallower) paths.


---

# 2) Mid-Game Abilities (Act II / Integration)

Typical mid-game thresholds

Evidence Score ≈ 6–10

At least one skill ≥ 5

Gravity either >55 (open) or <35 (closed) for some gated scenes


New abilities unlocked:

Ritual Participation (Meaningful) — available once Ritual Attunement ≥ 4 or Empathic Entry ≥ 5 with Gravity ≥ 50. Participating yields 1–3 Evidence points depending on interpretation success.

Pattern Synthesis — Pattern Recognition ≥ 6 unlocks multi-source inference: combine 2+ weak clues into a new, stronger clue.

Off-the-record Relationships — Charm ≥ 6 or Empathic Entry ≥ 6 unlocks deeper confessions / access to private journals; raises NPC trust.

Dream/Memory sequences — Dreammind ≥ 5 unlocks symbolic dream-scenes that are optional but reveal hidden context and can produce ritual evidence.

Framing Options in Mid-Report Drafting — Framing ≥ 5 unlocks nuanced paragraph openings (empathetic, investigative, sensational) usable in the final report editor.

Gravity-driven world layers — If Gravity > 65, exclusive events (late-night kitchen conversations, ritual backstories) become available; if Gravity < 25, rumor/skeptic paths open (leaks, local resistance).


Mechanics examples:

Ritual Participation: requires a skill check (Ritual Attunement or Empathic Entry). Success: +2 Evidence and +10 Gravity toward sect. Failure: -5 Gravity and +1 Evidence (misread symbol).

Pattern Synthesis: consumes 1 “Inference” token (recharged by evidence) to reveal a hidden relation between suspects/dates.


Mid-game behaviors and pacing:

Encourage players to choose whether to deepen Gravity (trust & depth) or remain skeptical to access different branches.

Mid-game is where the player meets Elias — meeting is gated: Evidence ≥ 8 OR Charm ≥ 6 + one supporting clue.



---

# 3) Late-Game Narrative Tools (Act III / Pre-Report)

Typical late-game thresholds

Evidence Score ≈ 12–16

At least two skills ≥ 7 (or one at 9)

Gravity either high (>70) or low (<20), or carefully balanced (40–60) for ambiguous endings


Powerful narrative tools unlocked:

Report Editor (Full) — access to headline, angle, evidence citations, photo selection, anonymous testimony selection, and moral-weight sliders.

Moral Weighting — slider that alters narrative emphasis (Justice / Empathy / Public Interest). Requires Moral Weighting skill; each tilt locks/unlocks different epilogues.

Public Framing Options — Framing ≥ 8 unlocks narrative devices: lead anecdote, metaphorical frame, and rhetorical device choices that meaningfully affect public reaction.

Silent Option — a late-game tool to withhold publication (requires contextual memory ≥ 8 + either high empathy or direct bargain with an NPC).

Join / Expose / Reframe / Sabotage actions — high-tier narrative actions requiring combination checks (e.g., join requires Gravity ≥ 80 + Ritual Attunement ≥ 7).

Evidence Forensics — Critical Reason ≥ 8 unlocks deep-forensics checks that can turn “soft evidence” into “hard evidence” (document, timestamp, chain-of-custody).


Late-game consequences:

These tools aren’t “win” buttons — they provide different ethical levers. E.g., you can produce a sensational expose with partial evidence (fast path), or craft a slow, careful exoneration that preserves the community but angers your editors.



---

# 4) Crossroad Choices (Final branching mechanics)

Each crossroad is a high-impact decision node in Act III that maps to a particular epilogue cluster. Crossroads are gated by skill + Gravity + Evidence combinations. I list core crossroads, their mechanical triggers, and the typical endings they produce.

Crossroad A — Immediacy vs. Diligence

Choice: Publish now (fast route) vs Delay to verify (slow route)

Trigger for Publish-now option: Evidence ≥ 6 and Investigative Instinct ≥ 5 OR Editor pressure event

Outcomes:

Publish-now → Short route epilogues: high drama, fast public reaction, potential harm to town, faster professional acclaim or backlash.

Delay → Unlocks more investigation, deeper endings; may lose scoop but gain nuanced epilogues.



Crossroad B — Condemnation vs Contextualization

Choice: Frame the piece as condemnation (cult = danger) vs Contextualized understanding (cultural practice)

Mechanical mapping: Critical Reason vs Empathic Entry + Evidence balance.

Condemnation favored if Critical Reason ≥ Empathic Entry by 3+ points and Framing ≥ 6.

Contextualization favored if Empathic Entry ≥ Critical Reason by 2+.


Endings: Condemnation → legal action, exodus, sensationalism epilogues. Contextualization → preservation, reconciliation, or uneasy peace endings.


Crossroad C — Transparency vs Concealment

Choice: Reveal names/testimony vs anonymize/withhold

Mechanical mapping: Moral Weighting + NPC Trust + Risk assessment (Contextual Memory)

Endings: Public accountability vs Protected community (if names withheld, may avoid legal harms but create moral consequences and editor fury).


Crossroad D — Integration vs Separation

Choice: Join / convert / integrate into the sect vs remain an outsider journalist or even sabotage

Trigger: Gravity ≥ 80 and Ritual Attunement ≥ 7 for join option; alternatively, low Gravity + Skeptic’s Edge high enables a sabotage path.

Endings: If join → introspective epilogues, different career path, deeper unresolved mysteries. If sabotage → expose + possible criminal consequences, personal moral rot epilogues.


Crossroad E — Silence (Refusal to Publish)

Choice: Never publish — keep notes private, return later, or burn material.

Trigger: Contextual Memory ≥ 8 + Empathic Entry ≥ 8 or a strong personal/professional cost (editor threat).

Endings: Quiet life, secret knowledge, local protection, or self-betrayal depending on prior choices.



---

# 5) Ending Map — quick reference (6 major epilogue clusters)

1. The Exposé — Sensational publication; town scapegoated; player gains national notoriety; mixed personal cost.

Typical triggers: Publish-now, Condemnation, Evidence 10+, Critical Reason high



2. The Nuanced Article — Balanced, contextual reporting; community survives with modifications; player gains respect but less fame.

Triggers: Delay + Contextualization + Evidence 14+, High Framing, Moderate Gravity



3. The Defense — Player defends the sect; local acceptance; national skepticism; personal integrity tested.

Triggers: High Gravity + Empathic Entry + Ritual Attunement



4. The Silent Protector — Player withholds the article; villagers safe; profession suffers; deeper personal meaning.

Triggers: Silence crossroad; Contextual Memory + Empathy high



5. The Saboteur / Legal Path — Player provokes legal action; some justice possibly served; community fractured.

Triggers: Condemnation + Evidence 12+ + Authority/Investigative Instinct high



6. The Convert — Player joins the measured path; different life, different narrative closure; player may leave journalism.

Triggers: Join crossroad; Gravity very high + Ritual Attunement high




Each cluster should have 3–6 micro-variations depending on NPC fates (e.g., Elias’ fate, the villager who collapsed, a cop’s reputation) so endings feel individualized.


---

# 6) Progression Metrics & Implementation Suggestions

Use simple numeric systems so writers and scripters can script thresholds easily.

Skills: 1–10 integer. Most advancement by +1 via major story beats, +0.5 via minor beats (implement as milestones).

Gravity: 0–100 integer. Change in chunks of 5–20 depending on rituals, confessions, betrayals.

Evidence Score: 0–20 integer. Count distinct interpreted clues (police doc = 1, personal journal = 1, ritual artifact = 1; multi-source inferences add +1).

NPC Trust: per NPC, 0–100; affects availability of private testimony/actions.


Suggested progression cadence (example):

Prologue → End Act I: Evidence 0 → 4; Skills 3–5; Gravity 30–60

Mid-game (Act II): Evidence 5 → 12; Skills 4–7 (one or two axes advance); Gravity diverges

Act III start: Evidence ≥ 12 or a major reveal; skills 6+ in chosen axes

Final report: Evidence 12–20 + at least one skill ≥ 8 to unlock premium framing/report levers


Balance tip: make some evidence convertible to “hard” only by high Critical Reason + Contextual Memory combo to reward analytical builds.


---

# 7) Example Encounters showing progression interaction

1. Kitchen Confession (early-mid)

Requirements: Charm ≥ 5 or Empathic Entry ≥ 6

Outcome: NPC reveals a childhood ritual story → +1 Evidence; Gravity +8 if handled empathetically; opens “secret journal” scene.



2. Midnight Pathway Rite (mid)

Requirements: Ritual Attunement ≥ 4 or Dreammind ≥ 5 + Gravity ≥ 50

Success (skill check): Gains unique symbol drawing (+2 Evidence), deep trust with a sect elder (NPC Trust +20). Failure: misinterprets symbol => Evidence +1 (misleading), Gravity -10, some NPCs distrust you.



3. Archive Forensics (late)

Requirements: Critical Reason ≥ 8 + Contextual Memory ≥ 7

Outcome: Timestamp proves a police misreport → converts soft evidence to a hard document (+2 Evidence), unlocks a judicial epilogue branch.





---

# 8) UI & UX suggestions for progression feedback

Progress Timeline bar (top-right) showing: Evidence / Gravity / Primary Skill focus (icon). Tapping expands to list collected evidence with verdict state (Discovered / Interpreted / Concluded).

Internal Voices Hotbar: shows which internal voices are currently active (based on skill tiers).

Trust Meter (per NPC): visible on NPC page; helps players plan who to press, who to protect.

Report Draft Preview: progressively unlocked sections (headline, lead, key quote, evidence citations, moral slider) that light up as prerequisites are met.



---

# 9) Quick design checklist to implement immediately

Wire up three meters (Skills, Gravity, Evidence) to scene gating.

Create 8–12 “evidence” items with multiple interpretation states.

Script 6 major crossroads as discrete nodes with requirements + fallout scripts.

Build the end-report editor UI with slots that require unlocking.

Create 4 example ritual scenes, each with branching outcomes tied to Ritual Attunement.

Draft 3–5 micro-epilogues for each major ending cluster to ensure variety.
