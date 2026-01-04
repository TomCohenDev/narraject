# Narraject RPG

> _Roll dice to succeed. Roll YOUR die to matter._

A narrative-focused TTRPG bridging tactile dice pools with Cypher-style narrative economies.

**Target:** 40-60 page rulebook  
**Status:** Alpha 0.1 — Restructured for tight, modular design

---

## Project Status

| Section | Status | Notes |
|---------|--------|-------|
| **Core Rules** | 🟢 Complete | The Roll, Step Die, Economy, Ladder |
| **Character Creation** | 🟢 Complete | Packages, Stats, Gear, Progression |
| **Gameplay Loops** | 🟢 Complete | Pacing, Conflict, Consequences |
| **GM Toolkit** | 🟢 Complete | Principles, NPCs, Modular Toolbox |
| **Back Matter** | 🟢 Complete | Tables, Definitions, Sheets |
| **Playtest** | 🔴 Not Started | Ready for alpha testing |

---

## The Pitch

**For players** who want their character's identity to matter mechanically—not just narratively.

**For GMs** who want Cypher's easy prep and intrusion economy without the death spiral math.

**The hook:** Your signature trait gives you a **Step Die** (d8/d10/d12). When it shines, you define the moment. When it betrays you, the story takes a turn. Mastery isn't just "better odds"—it's _reliable identity_.

---

## Repository Structure

```
narraject-rpg/
├── .cursorrules              # AI context instructions
├── .gitignore
├── README.md                 # You are here
│
├── 00_references/            # Research & Inspiration
│   ├── mechanics/            # Notes on other systems
│   ├── inspiration_imgs/     # Art direction, vibes
│   └── raw_pdfs/             # Rulebooks (gitignored if large)
│
├── 01_manuscript/            # THE BOOK (~50 pages)
│   ├── 00_front_matter/      # Title, Credits, Pitch (2-3 pages)
│   ├── 01_core_rules/        # The Engine (8-10 pages)
│   │   ├── 01_the_roll.md
│   │   ├── 02_the_step_die.md
│   │   ├── 03_the_economy.md
│   │   └── 04_the_ladder.md
│   ├── 02_characters/        # The Drivers (10-12 pages)
│   │   ├── 01_creation_flow.md
│   │   ├── 02_stats_and_capacity.md
│   │   ├── 03_packages.md
│   │   ├── 04_gear.md
│   │   └── 05_progression.md
│   ├── 03_gameplay_loops/    # Action (8-10 pages)
│   │   ├── 01_pacing.md
│   │   ├── 02_conflict.md
│   │   └── 03_consequences.md
│   ├── 04_gm_toolkit/        # The Director (10-12 pages)
│   │   ├── 01_principles.md
│   │   ├── 02_npcs_threats.md
│   │   └── 03_the_toolbox.md  # Modular expansion system
│   └── 99_back_matter/       # Reference (4-5 pages)
│       ├── 01_tables.md
│       ├── 02_definitions.md
│       └── 03_sheets.md
│
├── 02_assets/                # Book components
│   ├── diagrams/             # Flowcharts, probability charts
│   ├── illustrations/        # Character art
│   ├── layout/               # Fonts, CSS, logos
│   └── templates/            # Character sheet drafts
│
├── 02_design_notes/          # Not for the book
│   └── ideas_bin.md          # Future ideas, expansions
│
├── 03_playtest/              # Feedback loop
│   ├── session_logs/         # Actual play notes
│   └── feedback/             # Issues and suggestions
│
└── dist/                     # Final outputs
    ├── narraject_alpha.pdf   # Compiled PDF
    └── narraject_web/        # HTML version (optional)
```

---

## Quick Start for Contributors

1. **Read the manuscript** in `01_manuscript/` — that's the source of truth
2. **Check references** in `00_references/mechanics/` for design rationale
3. **Log playtest issues** in `03_playtest/feedback/`
4. **Use Cursor** with `.cursorrules` for AI-assisted editing

---

## Design Pillars

1. **The Step Die is the Star**  
   Your signature die represents identity, not just competence.

2. **Narrative Injection Economy**  
   Complications are offered, not imposed. Currency flows both ways.

3. **Dice Pools Over Math**  
   Add dice, not modifiers. Count successes, don't multiply.

4. **Separate Health from Action**  
   No death spirals. Getting hurt doesn't drain your skill pool.

5. **GM Prep Should Be Easy**  
   Single-number NPCs. Improvisation-friendly. Trust the table.

6. **Modular Expansion**  
   The Toolbox allows future expansions without rewriting the core.

---

## The Modular Toolbox

The **Toolbox** (`04_gm_toolkit/03_the_toolbox.md`) is your "Extension Cord" for future expansions.

Instead of writing a "Setting" chapter, you write modular rules that plug into the core:
- Magic systems
- Vehicles
- Horror mechanics
- Cyberware
- Social intrigue
- Crafting

Future expansions (e.g., "Narraject: Neon Streets") just add new modules to the Toolbox. The core game remains 50 pages.

---

## Building the PDF

*(Coming soon — will use Pandoc or similar)*

```bash
# Placeholder
cd 01_manuscript
pandoc **/*.md -o ../dist/narraject_alpha.pdf --toc
```

---

## License

TBD — Currently private development.

---

## Contact

Tom — End2End Startup  
_Building Narraject as a love letter to narrative gaming_
