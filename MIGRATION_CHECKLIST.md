# Migration Checklist

## Content Migration Status

### ✓ Fully Migrated

1. **00_intro/01_what_is_narraject.md** → `00_front_matter/01_the_pitch.md`
   - All content migrated ✓

2. **01_core_rules/01_building_the_pool.md** → Split into:
   - `01_core_rules/01_the_roll.md` (pool building, basic roll mechanics) ✓
   - `01_core_rules/04_the_ladder.md` (Golden Rule, ambition vs difficulty) ✓

3. **01_core_rules/02_resolution.md** → Split into:
   - `01_core_rules/02_the_step_die.md` (Step Die mechanics) ✓
   - `01_core_rules/03_the_economy.md` (post-roll IP spending) ✓
   - `04_the_ladder.md` (degrees of success/failure) ✓
   - Note: Edge cases and examples may need review

4. **01_core_rules/03_combat.md** → Split into:
   - `03_gameplay_loops/02_conflict.md` (combat mechanics) ✓
   - `03_gameplay_loops/03_consequences.md` (conditions system) ✓

5. **03_narrative/01_economy.md** → `01_core_rules/03_the_economy.md`
   - All content migrated ✓

6. **02_character/01_overview.md** → `02_characters/01_creation_flow.md`
   - All content migrated ✓

7. **02_character/02_focus.md** → `02_characters/06_focus.md`
   - All content migrated ✓ (just created)

8. **02_character/03_types.md** → `02_characters/03_packages.md`
   - Converted to Packages system ✓

9. **02_character/04_descriptors.md** → `02_characters/07_descriptors.md`
   - All content migrated ✓ (just created, adjusted for new system)

10. **04_gm_section/01_running_the_game.md** → `04_gm_toolkit/01_principles.md`
   - Was just a placeholder, new version is comprehensive ✓

11. **01_core_rules/99_quick_reference.md** → `99_back_matter/01_tables.md`
   - Tables migrated, some content in definitions and sheets ✓

### ⚠️ Items to Verify

- Edge cases from old resolution.md (tied results, no relevant focus, multiple characters helping)
- Examples from old files (may be incorporated but worth double-checking)

### ✅ New Content Added

- `02_characters/04_gear.md` (Tags system - new)
- `02_characters/05_progression.md` (Upgrade Wheel - new)
- `03_gameplay_loops/01_pacing.md` (Scenes vs Downtime - new)
- `04_gm_toolkit/03_the_toolbox.md` (Modular expansion system - new)
- `99_back_matter/02_definitions.md` (Glossary - new)
- `99_back_matter/03_sheets.md` (Character sheet reference - new)

## Old Files That Can Be Removed

### Safe to Delete (fully migrated):
- `00_intro/01_what_is_narraject.md` ✓
- `01_core_rules/01_building_the_pool.md` ✓
- `01_core_rules/02_resolution.md` ✓ (edge cases should be checked first)
- `01_core_rules/03_combat.md` ✓
- `01_core_rules/99_quick_reference.md` ✓ (tables migrated to back matter)
- `02_character/01_overview.md` ✓
- `02_character/02_focus.md` ✓
- `02_character/03_types.md` ✓
- `02_character/04_descriptors.md` ✓
- `03_narrative/01_economy.md` ✓
- `04_gm_section/01_running_the_game.md` ✓ (was placeholder)

### Empty/Unused Directories:
- `00_intro/` (can be removed if empty)
- `02_character/` (can be removed if empty)
- `03_narrative/` (can be removed if empty)
- `04_gm_section/` (can be removed if empty)
- Other empty directories: `01_core_loop/`, `02_character_creation/`, `03_playing_the_game/`, `05_reference/`, `00_frontmatter/`
