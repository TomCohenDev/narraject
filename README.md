# Narraject RPG

> *Roll dice to succeed. Roll YOUR die to matter.*

A narrative-focused TTRPG bridging tactile dice pools with Cypher-style narrative economies.

---

## Project Status

| Section | Status | Notes |
|---------|--------|-------|
| **Core Rules** | 🟢 Drafted | Identity Die mechanic in place |
| **Character Creation** | 🟡 In Progress | Types and Descriptors outlined |
| **Narrative Economy** | 🟢 Drafted | IPs, Intrusions, Injections defined |
| **Combat** | 🔴 Placeholder | Major decisions pending |
| **GM Section** | 🔴 Not Started | — |
| **Setting** | ⚪ Optional | System-agnostic by default |
| **Playtest** | 🔴 Not Started | Need alpha manuscript first |

---

## The Pitch

**For players** who want their character's identity to matter mechanically—not just narratively.

**For GMs** who want Cypher's easy prep and intrusion economy without the death spiral math.

**The hook:** Your signature trait gives you a **Step Die** (d8/d10/d12). When it shines, you define the moment. When it betrays you, the story takes a turn. Mastery isn't just "better odds"—it's *reliable identity*.

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
├── 01_manuscript/            # THE BOOK
│   ├── 00_intro/             # What is Narraject?
│   ├── 01_core_rules/        # Dice resolution, Step Die
│   ├── 02_character/         # Creation, Types, Foci
│   ├── 03_narrative/         # IPs, Intrusions, Injections
│   ├── 04_gm_section/        # Running the game
│   └── 05_setting/           # World lore (optional)
│
├── 02_assets/                # Book components
│   ├── diagrams/             # Flowcharts, probability charts
│   ├── illustrations/        # Character art
│   ├── layout/               # Fonts, CSS, logos
│   └── templates/            # Character sheet drafts
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

---

## Building the PDF

*(Coming soon — will use Pandoc or similar)*

```bash
# Placeholder
cd 01_manuscript
pandoc **/*.md -o ../dist/narraject_alpha.pdf
```

---

## License

TBD — Currently private development.

---

## Contact

Tom — End2End Startup  
*Building Narraject as a love letter to narrative gaming*
