# Middle Tepenia

**A top-down, isometric, turn-based sci-fi RPG and spiritual successor to old-school Fallout (1, 2 and New Vegas), set on post-war Mars after the ending events of the *Cryptograph Helix* novel series, in a society of humans, sentient robots, and the fragile nation they built together.**

This repo holds the game's **design documents**. The code lives in the companion repo, `MiddleTepeniaDEV`. The game will be built in **Godot** (whatever version is current by then, possibly 5.x).

**Status: concept.** The game comes out after the [*Inner Tepenia*](https://github.com/TerranLights/InnerTepeniaGDD) CRPG; its order relative to the *Cryptograph Helix* novels is not yet known. Because the novels' structure, events and ending are not yet written, the exact conditions the game's world lives in are still to be determined.

## Where it sits among the Tepenian games
| Game | Setting | Play |
|---|---|---|
| *Inner Tepenia* | Antarctica (Tepenia), after the Long Night War | Top-down, isometric, turn-based |
| ***Middle Tepenia*** | **Mars, after the *Cryptograph Helix*** | **Top-down, isometric, turn-based** |
| *Outer Tepenia* trilogy | Jupiter, Saturn, the Alpha/Proxima Centauri System | Real-time, 1st- and 3rd-person, open world |

**Mechanics are mostly, but not entirely, shared across the line.** A common core (for example the MACHINE stats) runs through every game. Mechanics particular to turn-based play live in the turn-based games and their counterparts in the real-time ones; mechanics particular to a top-down view live in the top-down games and their counterparts in the 1st- and 3rd-person ones. *Middle Tepenia* shares both its turn-based and its top-down mechanics with *Inner Tepenia*.

## Genre and style
* **Core loop:** tactical turn-based combat and exploration on an isometric grid, driven by a deep Action Point (AP) economy.
* **Tone and influences:** Fallout 1 and 2 meet Shadowrun and Torment: Tides of Numenera, with strong cyberpunk and philosophical undertones. Meaningful choices, character builds, faction politics and bittersweet consequences.
* **Scope:** single-player, focused on character progression, narrative reactivity and maximum player agency. Designed to be highly moddable.
* **The player character is a robot.**

## Setting
Following the ending events of the [*Cryptograph Helix*](https://github.com/TerranLights/TheCryptographHelixDD) novel series, the people of the game's world live on a post-war Mars. Its cultures descend from those of the Tepenian Federation and are drawn from the [Culture Library](https://github.com/TerranLights/CultureLibrary) (`Library/Mars/`), not from real-world research. Like every Tepenian work, the game draws on the same foundational data: canon and the universal design laws in the [Tepenian Universe Timeline](https://github.com/TerranLights/TepenianUniverseTimeline), and the methods for building characters, places and stories in [Derivation Mechanisms](https://github.com/TerranLights/DerivationMechanisms).

## Core mechanics (shared with *Inner Tepenia* as the starting point)

**Action Point system** (inspired by classic Fallout)
* A fresh AP pool every turn; unused AP are discarded at the end of the turn.
* **Base AP** = 6 + floor(Agility / 2)
* **Nerve modifier** = floor((Nerve - 5) / 2)
* **Engine** governs efficiency: it reduces movement costs, reloads and item use, and grants "free" movement tiles.
* Typical costs: movement (1 AP per tile), basic attack (4–6 AP), aimed or special attack (6–8 AP), reload or item (2–4 AP), hacking or complex action (6–10 AP), powerful abilities (8–15 AP).
* Perks, traits and cyberware further modify the system.

**MACHINE stats** (seven core attributes on a 1–10 scale; the Tepenian interpretation of Fallout's SPECIAL)
* **[M]ight:** raw physical power *(Fallout's Strength)*
* **[A]gility:** speed, reflexes, coordination *(as in Fallout)*
* **[C]alculation:** logic, problem-solving, optimization *(Fallout's Intelligence)*
* **[H]umanity:** empathy, social awareness, emotional intelligence *(close to Charisma; perception of people)*
* **[I]nvestigation:** pattern recognition, deduction, information gathering *(close to Perception; perception of the world)*
* **[N]erve:** mental resilience, willpower, companion influence *(no Fallout equivalent)*
* **[E]ngine:** operational endurance before burnout, and efficiency *(no Fallout equivalent)*

**Progression**
* Skill points per level = 2 + floor(Calculation / 2) + floor(Nerve / 2) + Investigation modifier (minimum 3)
* Tag 3 skills for a flat **+15** each at character creation
* A perk every 2 levels: 32 perk opportunities in the base game
* **Level cap: 64** in the base game; DLCs may raise it
* Traits: 1–2 double-edged starting choices that define a playstyle
* Re-speccing possible, at high cost and with heavy trade-offs
* Strong support for min-max and speedrun builds

**Combat:** grid-based, isometric and turn-based; damage thresholds, resistances and armor augmentations; signature abilities and targeting systems; deeply tied to the AP economy and the character's stats.

## Story and narrative
**Main quest hook:** not yet determined.

The structure is flexible (light gating; sequence-breaking possible). **There are no good endings:** every path leads to a **bittersweet ending** with real trade-offs, faction consequences, unrest, alliances and political shifts. Strong emphasis on side content, companion relationships, faction reputation and player-driven philosophy.

## Design pillars
* Deep, synergistic character builds with distinct playstyles
* Tactical, AP-driven combat and exploration
* A reactive world and narrative with real consequences
* Mod-friendly architecture (data-driven perks and items, script extensions, resource packs)
* Speedrun- and optimization-friendly while remaining accessible
* **No level-scaling:** the world has a fixed, designed difficulty that the player grows into
* **Realism wherever possible; where realism and fun truly cannot both be had, fun wins**

---

*Middle Tepenia is a thoughtful, systems-heavy sci-fi RPG in which every choice, from how you spend your Action Points to how you deal with a struggling society, carries weight.*
