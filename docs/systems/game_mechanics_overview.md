Below is a Game Mechanics Overview written as a real developer-facing design document. It stays aligned with your HNO and Core Pillars while setting a foundation for future systems design.


---

GAME MECHANICS OVERVIEW (GMO)

Working Title: The Narrow Path
Genre: Narrative RPG / Investigative Interactive Novel (Mobile)
Perspective: First-person prose + “Disco Elysium-like” skill checks and internal dialogues
Platform: Mobile (portrait & landscape compatibility)

---

## Table of Contents 

1. [Core Loop](#1.core-loop)
2. [Player Systems](#2.player-systems)
3. [World Systems](#3.world-systems)
4. [Reporting System](#4.reporting-system)
5. [Dialogue & Internal Monologue System](#5.dialogue--internal-monologue-system)
6. [Choice & Consequence Structure](#6.choide--consequence-structure)
7. [Symbol & Numerology Integration](#7.symbol--numerology-integration)
8. [Player Failure & Success States](#8.player-failure--success-states)
9. [Onboarding & UX](#9.onboarding--ux)

---

# 1. CORE LOOP

1.1 Player Core Loop

1. Explore
Move through the township, paths, interiors, forests, and archives. Trigger environmental storytelling, NPC encounters, clues, and numerological/pagan artifacts.


2. Investigate
Collect Evidence (notes, testimonies, numerological patterns, symbolic objects).
Perform Skill Checks to interpret, challenge, or contextualize information.


3. Reflect (Internal Dialogue)
Multiple internal “voices” pull the player toward different interpretations.
The player’s cognitive build influences how clues are processed.


4. Decide
Dialogue choices, moral stances, involvement level with sect rituals, and reporting style.


5. Shape Outcome
Report, expose, empathize, withdraw, join, sabotage, distort — each path changes the world state and final report.



This loop repeats until the player reaches a final editorial decision.


---

# 2. PLAYER SYSTEMS

2.1 Player “Cognitive Skills”

Like Disco Elysium, but shaped by your themes:
Each governs how the journalist interprets the world.

2.1.1 Skills List (Draft)

PERCEPTION CLUSTER

Detail Sense – Spot subtle environmental clues (symbols, patterns, behaviors).

Emotional Reading – Perceive NPC micro-reactions, sincerity, fear, shame.

Pattern Recognition – Detect numerological recurrences and symbolic structures.


INTELLECT CLUSTER

Critical Reason – Challenge pseudoscience, question motives.

Contextual Memory – Cross-reference earlier clues with new events.

Skeptic’s Edge – Resist sect influence, call out inconsistencies.


INTUITION CLUSTER

Numinous Sensitivity – Feel symbolic or ritual “pressure” in locations.

Dreammind – Interpret dreams and visions; unlock alternative clue chains.

Ritual Attunement – Understand pagan practices; makes rituals meaningful.


SOCIAL CLUSTER

Charm – Get locals to open up.

Authority – Push through resistance.

Empathic Entry – Gain trust by reflecting emotions back to NPCs.


MEDIA CLUSTER

Framing – Unlock unique dialogue choices in reporting contexts.

Moral Weighting – Re-evaluate consequences of exposure vs protection.

Investigative Instinct – Guides next rational step; reduces aimlessness.


Players pick a starting “bias triad” that boosts certain skills and colors early interpretations.


---

2.2 Evidence & Clue System

Evidence Types

Hard Evidence (documents, police reports, objects)

Soft Evidence (testimonies, rumors, interpretations)

Numerological Evidence (dates, numbers, cycles – requires Pattern Recognition)

Ritual Evidence (objects, symbols, arrangements – requires Ritual Attunement)


Clue States

Evidence evolves dynamically:

Discovered → Interpreted → Contextualized → Concluded


Different skill builds form different interpretations from the same object.


---

2.3 Influence System: “Gravity”

The cult has a psychological gravity that affects the player without brainwashing, but through:

Hospitality

Coherent worldview

Emotional resonance

Numerological synchronicities (engineered or accidental?)


Gravity Score tracks the journalist’s openness to the sect.

High Gravity → opens deeper content
Low Gravity → maintains critical distance
Very Low Gravity → blocks trust-based paths

Gravity never removes agency — it shapes what the world and sect offer the player.


---

2.4 Ritual Participation System

Optional rituals serve as:

Clue delivery mechanisms

Emotional bonding moments

Philosophical challenges


Rituals include:

New Moon Casting (intention-setting)

Pathway Rite (numerological self-revelation)

Harvest Vigil (communal moral test)

Wheel of Spirit Constellation (astrology-based personality interpretation)


Participation yields:

Insight unlocks

Bonding with sect members

Gravity Score increase

Possible mistrust from skeptics in town


Each ritual has:

1. Setting


2. Requirements


3. Mechanical Hook (skill check, interpretative choice, meaning extraction)


4. Outcome Variants




---

# 3. WORLD SYSTEMS

3.1 Open Area Exploration (Narrative Layered Map)

Each zone reveals:

Hidden numerology (e.g., benches arranged in 3-6-9 patterns)

Pagan iconography (Brigid knots, Wiccan circles, sun wheels)

Character routines

Environmental triggers causing internal dialogue skill checks


Zones unlock gradually depending on:

Gravity

Evidence thresholds

NPC trust



---

3.2 NPC Relationship System

NPC States

Every NPC has:

Trust

Openness

Bias (toward sect / against sect)

Stress Level

Willingness to Refute the Report


Interactions are shaped through:

Skill checks

Established Gravity

Player transparency (“off the record?”)

Alignment with their worldview


NPCs will sometimes:

Lie

Withhold

Test the player

Request favors

Challenge their assumptions


No NPC is purely right or wrong.


---

# 4. REPORTING SYSTEM (The “Final Weapon”)

The entire game is ultimately about how the player writes their piece.

4.1 Report Construction

At the end, the journalist assembles:

Headline

Opening paragraph

Key angle

Evidence cited

Photographs

Anonymous testimonies

Interpretation


Each section has multiple unlocked options based on:

What the player actually discovered

Their Gravity Score

Skills

NPC trust

Moral philosophy played out


4.2 Possible Report Themes

Expose the cult — sensationally

Expose the cult — respectfully

Defend the cult

Reframe “the incident” completely

Refuse to submit report

Submit a cryptic, symbolic editorial

Write a balanced but uncomfortable truth


The report becomes the ending screen, shaping epilogues for characters, the sect, and the township.


---

# 5. DIALOGUE & INTERNAL MONOLOGUE SYSTEM

Heavily inspired by Disco Elysium, but simplified for mobile.

5.1 Internal Voices

Voices represent the player’s cognitive skills, e.g.:

Critical Reason: “This doesn’t add up.”

Dreammind: “Do you hear it? Something hums beneath this story…”

Pattern Recognition: “Look. Another triad. Why three?”

Empathic Entry: “She’s afraid to lose someone.”


They:

Comment

Argue

Interfere

Provide skill checks


Sometimes conflicting voices override each other depending on Gravity.


---

# 6. CHOICE & CONSEQUENCE STRUCTURE

6.1 Types of Choices

World Choices: Where to go, who to speak to.

Interpretation Choices: What the player believes a clue means.

Ritual Choices: To participate or abstain.

Moral Choices: What truth means in this case.

Journalistic Choices: On/off record decisions.

Final Editorial Decisions: The ultimate shaping force.


6.2 Consequence Philosophy

Consequences are:

Mostly narrative

Sometimes emotional

Rarely mechanical


Example:
If the player interprets a symbol as threatening early on, NPCs later respond as though they are dealing with someone who projected threat onto them.

Interpretation becomes world-state.


---

# 7. SYMBOL & NUMEROLOGY INTEGRATION

7.1 The Sect’s Symbol (from earlier output)

The Triskelion of Elevation:
A three-armed spiral with an inner triangle made of 1-6-9 geometric proportions.
Represents:

Personal ascent

Cycles

Unity of numerology, astrology, and ritual


Mechanically, it appears throughout the world as:

Carved motifs

Arranged stones

Fire pits

Hidden graffiti

Bookmarks

Ritual diagrams


If the player spots it (Perception check), new clue branches unlock.


---

# 8. PLAYER FAILURE / SUCCESS STATES

Failure is narrative, not mechanical.

Fail a check → You learn something different, not nothing.

Misinterpretations accumulate → You get unique (often darker or misguided) paths.

Withhold asking the right questions → The story shrinks, becomes shallow.


Success grants depth, not superiority.


---

# 9. ONBOARDING & UX

Onboarding Goals

Introduce core loop quickly

Establish journalist identity

Give first taste of numerological symbolism (elevator: floors 1, 6, 9 only)

Present first ambiguous clue in the township

Let skills speak early


Mobile UX adapted for:

One-hand interaction

Minimal UI intrusion

Fast, readable prose
