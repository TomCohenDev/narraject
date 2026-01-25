# Narrative Injection RPG

> _Tactical dice pools meet narrative authority_

A narrative-focused TTRPG that combines crunchy dice pool mechanics with player story authority and fast-paced collaborative storytelling.

**Core Rules:** Complete (v0.3)
**Status:** Playtesting & Framework Development

---

## Project Status

| Section | Status | Notes |
|---------|--------|-------|
| **Core Rules (v0.3)** | 🟢 Complete | Success rate 50%, Focus system, Stats, Anchors, Burdens |
| **Character Creation** | 🟢 Complete | Point buy, Anchors/Burdens, Level scaling |
| **Combat & Conflict** | 🟢 Complete | Stress track, Conditions, Damage formula |
| **Progression** | 🟢 Complete | NP economy, stat milestones |
| **GM Principles** | 🟢 Complete | Difficulty scaling, improvisation, cards system |
| **Frameworks** | 🟡 In Progress | Wyrdwood (Dark Norse) complete, more in development |
| **Playtest** | 🟡 Active | v0.3 system rebalance testing |

---

## The Pitch

**For players** who want tactical, crunchy gameplay with cool abilities AND fast-paced narrative play where they have real story authority.

**For GMs** who want easy prep, improvisation-friendly rules, and dramatic conflicts without death spirals or complex math.

**The hook:** Roll dice pools (4-5-6 = success), spend Focus after rolling to push through failures, and use your once-per-session **Narrative Injection** to inject story facts that the GM must honor. Character identity comes from Anchors (skills/competencies) and Burdens (flaws/vulnerabilities), not classes. Play in any setting with modular **Frameworks** that add genre-specific flavor.

---

## Repository Structure

```
Run By Null/
├── README.md                 # You are here
├── RULES_SUMMARY.md          # Complete core rules (v0.3) - Single comprehensive reference
│
├── 00_references/            # Research & Inspiration
│   ├── mechanics/            # Notes on other systems
│   └── inspiration_imgs/     # Art direction, vibes
│
├── 01_manuscript/            # Structured manuscript sections
│   ├── 00_front_matter/      # Title, Credits, Pitch
│   ├── 01_core_rules/        # Core mechanics
│   ├── 02_characters/        # Character creation
│   ├── 03_gameplay_loops/    # Pacing, conflict, consequences
│   ├── 04_gm_toolkit/        # GM principles and tools
│   └── 99_back_matter/       # Reference tables
│
├── 02_assets/                # Visual components
│   ├── diagrams/             # Flowcharts, probability charts
│   └── templates/            # Character sheet drafts
│
├── 02_design_notes/          # Design rationale
│   └── ideas_bin.md          # Future ideas, expansions
│
├── 03_playtest/              # Playtest feedback
│   ├── session_logs/         # Actual play notes
│   └── feedback/             # Issues and suggestions
│
├── 04_frameworks/            # 🆕 Setting-specific expansions
│   ├── README.md             # Framework overview and guidelines
│   ├── WYRDWOOD.md           # Dark Norse fantasy framework (complete)
│   └── WYRDWOOD_SUMMARY.md   # Quick reference for Wyrdwood
│
└── dist/                     # Final outputs
    └── (PDF builds will go here)
```

---

## Quick Start

### To Play
1. **Read RULES_SUMMARY.md** — Complete core rules in one file
2. **Choose a Framework** (optional) — Start with `04_frameworks/WYRDWOOD.md` for dark Norse fantasy, or play setting-agnostic
3. **Create characters** — Follow character creation in the rules
4. **Play!**

### To Contribute
1. **Read RULES_SUMMARY.md** — Source of truth for current rules
2. **Check playtest feedback** in `03_playtest/feedback/`
3. **Create or improve Frameworks** — See `04_frameworks/README.md` for guidelines

---

## Core Design Principles

1. **Tactical Meets Narrative**
   Crunchy dice pools for combat, narrative authority for story direction.

2. **Dice Pools, Not Modifiers**
   Add dice (d6s), count successes (4-5-6), no complex math.

3. **Focus After Rolling**
   Spend Focus AFTER seeing the roll to add successes. No wasted resources.

4. **No Death Spirals**
   Stress track buffers damage. Conditions don't stack. Health ≠ action economy.

5. **Easy GM Prep**
   Single-number NPCs (Level = Difficulty). Improvisation-friendly. Trust the table.

6. **Modular Frameworks**
   Core rules work for any setting. Frameworks add genre-specific flavor, Paths (character options), and special rules.

---

## Frameworks System

**Frameworks** are setting-specific expansions that plug into the core rules. Each Framework includes:
- Setting lore and worldbuilding
- **Paths** - Character progression options (like classes, but flexible)
- Gear and equipment for that setting
- Special rules (magic, technology, etc.)
- Bestiary and NPCs
- GM principles for that genre

### Available Frameworks

**Wyrdwood** (Dark Norse Fantasy) — Complete
- 6 Paths: Drengr (Warrior), Seiðr (Seer), Úlfheðinn (Berserker), Skáld (Bard), Völva (Witch), Outcast (Survivor)
- Grim mythology, psychosis mechanics, realm-crossing, blood oaths
- Inspired by Hellblade, Mörk Borg, Viking Age history

**Coming Soon:**
- Neon Shadows (Cyberpunk)
- Starborne (Space Opera)
- Classic Fantasy
- Post-Apocalyptic
- Superhero

See `04_frameworks/` for details.

---

## Key Features

### Core Mechanics
- **50% Success Rate:** 4-5-6 on d6 counts as success
- **Focus System:** Shared 0-6 pool, spend AFTER rolling to add successes
- **Anchors & Burdens:** Define your character through competencies and flaws, not classes
- **Narrative Injection:** Once-per-session story authority to inject facts into the narrative
- **Stress Track:** 3-point buffer before taking Conditions

### Character Progression
- **Stats:** Might, Agility, Intellect, Persona (only increase through narrative milestones)
- **Anchors:** Skills/competencies (+1d6 to +3d6), upgrade with Narrative Points (NP)
- **Burdens:** Flaws/vulnerabilities (-1d6 to -3d6), reduce with NP
- **Level ≈ Highest Stat ÷ 2:** Easy power scaling for GMs

### Combat & Conflict
- **Damage = Difficulty - Successes:** Simple, clear calculation
- **NPCs Don't Roll:** Players always roll (attacking or defending)
- **Conditions:** Physical/Mental tracks, only highest applies (no stacking)
- **No Death Spirals:** Getting hurt doesn't reduce your dice pools

---

## Version History

**v0.3 (2026-01-16)** - Major System Rebalance
- Success rate changed from 33% (5-6) to 50% (4-5-6)
- Character levels rebalanced (Level ≈ Highest Stat ÷ 2)
- Stats only increase via narrative milestones
- Frameworks & Paths system introduced
- Wyrdwood framework released

**v0.2** - System Refinements
- Focus system implemented
- Gear made fully situational
- Terminology changes (Traits → Anchors, Flaws → Burdens)
- Currency unified to NP

**v0.1** - Initial comprehensive rules summary

---

## License

TBD — Currently private development.

---

## Contact

Tom Cohen — End2End Startup
_Building Narrative Injection as a love letter to tactical narrative gaming_
