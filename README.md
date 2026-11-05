# Middle Tepenia

> **Global reference:** [`Game-Mechanics/Universal_Rules.md`](Game-Mechanics/Universal_Rules.md) — game-wide binding rules that apply across all systems. Consult this first when a rule's scope is unclear.

**A top-down, isometric, turn-based Sci-Fi RPG and spiritual successor to old-school Fallout (1, 2, and New Vegas) set on Mars, following the events of the Cryptograph Helix novel series, in a society of humans, sentient robots, and the fragile nation they built together.**

### Genre & Style
* **Core Loop:** Tactical turn-based combat and exploration on an isometric grid, driven by a deep Action Point (AP) economy.
* **Tone & Influences:** Fallout 1/2 meets Shadowrun and Torment: Tides of Numenera with strong cyberpunk and philosophical undertones. Emphasis on meaningful choices, character builds, faction politics, and bittersweet consequences.
* **Scope:** Single-player RPG focused on character progression, narrative reactivity, and maximum player agency. Designed to be highly moddable.

### Setting & Lore (Bird's-Eye)

Following the ending events of the [Cryptograph Helix](github.com/TerranLights/TheCryptographHelixDD) novel series, the denizens of the in-game world live on a post-war Mars. At this time, the exact, precise current conditions that the characters in the in-game world live in are yet TBD (as at the time of this writing and commit, the exact, precise, structure, course-of-events, and outcome of the novel series has yet to be written). For a stylistic and/or thematic basis-of-reference, consult the [Inner Tepenia game design docs](github.com/TerranLights/InnerTepeniaGDD) repo.

### Core Gameplay Mechanics
**Action Point System** (inspired by classic Fallout, future-proofed for real-time sequels)
* Fresh AP pool every turn.
* **Base AP** = 6 + floor(Agility / 2)
* **Nerve Modifier** = floor((Nerve - 5) / 2)
* **Engine** governs efficiency: reduces movement costs, reloads, item use, and grants “free” movement tiles.
* Typical costs: Movement (1 AP/tile), Basic Attack (4–6 AP), Aimed/Special (6–8 AP), Reload/Item (2–4 AP), Hacking/Complex (6–10 AP), Powerful Abilities (8–15 AP).
* Perks, traits, and cyberware further modify the system. Unused AP are discarded at end of turn.

**MACHINE Stats** (7 core attributes on a 1–10 scale; the Tepenian interpretation of Fallout's SPECIAL system)
* **[M]ight:** Raw physical power *(Fallout Strength equivalent)*
* **[A]gility:** Speed, reflexes, coordination *(Fallout-identical)*
* **[C]alculation:** Logic, problem-solving, optimization *(Fallout Intelligence equivalent)*
* **[H]umanity:** Empathy, social awareness, emotional intelligence *(Fallout Charisma-adjacent, Perception of Humans)*
* **[I]nvestigation:** Pattern recognition, deduction, information gathering *(Fallout Perception-adjacent, Perception of the world)*
* **[N]erve:** Mental resilience, willpower, companion influence *(no Fallout equivalent)*
* **[E]ngine:** Operational endurance before burnout / efficiency *(no Fallout equivalent)*

**Progression**
* Skill points per level = 2 + floor(Calculation / 2) + floor(Nerve / 2) + Investigation modifier (minimum 3)
* Tag 3 skills for a flat **+15** bonus to each at character creation
* Perks earned every 2 levels — 32 total perk opportunities in the base game
* **Level cap: 64** (base game). DLCs may raise the cap beyond 64.
* Traits: 1–2 double-edged starting choices that define playstyle
* Re-speccing available with high costs and heavy trade-offs
* Strong support for minmax / speedrun builds

**Combat**
* Grid-based isometric turn-based
* Damage thresholds, resistance, armor augmentations
* Signature abilities, targeting systems
* Deep integration with AP economy and character stats

### Story & Narrative
**Main Quest Hook:** [currently undetermined]
Players make high-stakes decisions across modular chapters on:
* [currently undetermined]
* [more to come, currently undetermined]

Structure is flexible (light gating, sequence-breaking possible). There are no good endings. All paths lead to **bittersweet endings** with meaningful trade-offs, faction consequences, unrest, alliances, and political shifts.

Strong emphasis on side content, companion relationships, faction reputation, and player-driven philosophy.

### Key Features & Design Pillars
* Deep, synergistic character builds with distinct playstyles
* Tactical AP-driven combat and exploration
* Reactive world and narrative with real consequences
* Mod-friendly architecture (data-driven perks/items, script extensions, resource packs)
* Speedrun / optimization friendly while remaining accessible
* Continuity with planned “Outer Tepenia” real-time games (same stat/AP philosophy)

### Current Focus Areas (from GDD priorities)
* Questline design
* Character development — companion personalities, named Doll backstories, Enneagram completion pass
* World and faction design
* Location completion — location documentation template and demonyms TBD
* Game mechanics — first 50 remaining perks, Might/Nerve design pass

---

**Middle Tepenia** is a thoughtful, systems-heavy sci-fi RPG where every choice: from how you spend your Action Points to how you interact with a struggling society — carries weight.

*Details are actively being expanded across the folders in this repository (Game-Mechanics, Storyline, Worldspace, etc.).*
