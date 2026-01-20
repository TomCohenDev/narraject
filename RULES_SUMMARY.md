# Narraject: Complete Rules Summary

**Version:** Working Draft v0.5
**Purpose:** Comprehensive rules reference for playtesting and iteration
**Last Updated:** 2026-01-20

## Changelog

### v0.5 (2026-01-20)
- **MAJOR MECHANIC OVERHAUL: Anchors, Burdens & Conditions**
- **Anchors:** No longer add dice. Instead, shift success threshold to 3-4-5-6 (66.7% per die)
- **Burdens:** No longer remove dice. Instead, shift success threshold to 5-6 only (33.3% per die)
- **Conditions Reworked:** Minor (-1d6), Moderate (5-6 only), Severe (6 only = 16.7% per die)
- **Binary Application:** Anchors/Burdens are now binary (apply or don't), no tiers
- **One Per Roll:** Only ONE Anchor and ONE Burden can apply per roll
- **Cancellation:** If both apply, they cancel out (use normal 4-5-6)
- **Rule of Balance:** Unchanged - 1 Burden per 1 Anchor owned
- **Dice Pool Simplified:** Pool = Stat + Gear + Aspects - Minor Conditions
- **Eliminated:** Anchor tiers (Basic/Advanced/Master), Burden tiers (Minor/Moderate/Severe)
- **Progression Updated:** NP now adds new Anchors (must add Burden) or removes Burdens

### v0.4 (2026-01-20)
- **Damage Formula Rework:** NPCs now have Attack (difficulty) and Damage (how hard they hit) as separate values
- **Enemy Archetypes:** Enabled slow devastators, fast harassers, etc.
- **Focus Recovery:** Rest now restores to 3, not max
- **Assist Rules:** Added - helpers grant +1d6 or lend their Anchor
- **Contested Rolls:** Added - both roll, higher wins, tie = stalemate
- **Degrees of Success/Failure:** Made core (removed Optional label)
- **GM Burden Invocation:** GM can invoke player Burdens (player earns NP)
- **Starting Templates:** Added Street/Standard/Heroic character packages
- **Encounter Balancing:** Added threat budget guidance
- **Social Rolls:** Added clarification (difficulty scales with request)
- **Narrative Injection:** Added optional categories (Contact, Preparedness, Fact, Twist, Reframe)
- **Stress Spillover:** Clarified - excess damage is ignored

### v0.3 (2026-01-16)
- **MAJOR SYSTEM REBALANCE:**
- **Success Rate Changed:** 5-6 → 4-5-6 (33% → 50% per die)
- **Character Level Scale Adjusted:** Level now ≈ Highest Stat ÷ 2 (was ÷ 3)
- **Stat Ratings Rebalanced:** Level 1 = 2-3 highest stat (was 3-5), Level 3 = 6-7 (was 9-11)
- **Stat Distribution Simplified:** Removed minimum spread formula (÷3 rule), only requirement is each stat ≥ 1
- **Power Levels Table Updated:** All 10 levels rebalanced for new success rate
- **Dice Pools Reduced:** Typical specialty pools now 6-12d6 (was 9-18d6)
- **Initiative System:** Changed from Popcorn to "What Makes Sense" (narrative-based)
- **Stress Track Added:** 3-point buffer before taking Conditions
- **Damage Formula:** Damage = Difficulty - Successes
- **Conditions Don't Stack:** Only highest relevant Condition applies
- **NPC Scale Updated:** Level = Difficulty, can have specific action levels
- **Stats via Milestones Only:** Cannot buy stats with NP, only through narrative progression
- **Frameworks & Paths Added:** Section 14 explaining setting-specific content structure

### v0.2 (2026-01-14)
- **Major Change:** Replaced Reserve/Effort system with Focus (0-6 shared pool)
- **Focus Mechanics:** Spend Focus AFTER rolling to add Successes (1 Focus = +1 Success)
- **Focus Timing:** Spend after seeing roll result - never wasted!
- **Focus Limit:** Cannot spend more Focus than your Stat Rating
- **Character Creation:** Simplified to Name + Descriptor, GM-driven process
- **Terminology Changes:** "Traits" → "Anchors", "Flaws" → "Burdens"
- **Currency Unification:** Unified to Narrative Points (NP) only
- **NP Uses:** Progression and gambling for Focus recovery
- **Gear System:** Fully situational, no fixed tiers
- **Armor Redesign:** Situational defense bonuses
- **Failure Impact:** Added rule that failures still create progress

### v0.1 (2026-01-13)
- Initial comprehensive rules summary created
- Consolidated all core mechanics from manuscript

---

## Table of Contents

1. [Core Mechanics](#1-core-mechanics)
2. [Character Stats & Focus](#2-character-stats--focus)
3. [Character Creation](#3-character-creation)
4. [Anchors](#4-anchors)
5. [Burdens (Flaws)](#5-burdens-flaws)
6. [Gear & Equipment](#6-gear--equipment)
7. [Narrative Injection](#7-narrative-injection)
8. [Combat & Conflict](#8-combat--conflict)
9. [Condition Tracks & Consequences](#9-condition-tracks--consequences)
10. [Progression & Narrative Points](#10-progression--narrative-points)
11. [Power Levels & Point Buy](#11-power-levels--point-buy)
12. [Pacing & Session Structure](#12-pacing--session-structure)
13. [GM Principles](#13-gm-principles)
14. [Frameworks & Paths](#14-frameworks--paths-setting-specific-content)

---

## About This Game

Hi. I'm Tom Cohen, and this is **Narraject**.

I've been running and playing tabletop RPGs for years now, and I kept running into the same problem: I wanted tactical, crunchy gameplay with cool abilities and meaningful choices, but I also wanted fast-paced narrative play where the story moves forward and players have real authorship. And I couldn't find a system that gave me both.

See, here's the thing: most narrative games are great at giving players story authority, but they feel... mushy. There's no crunch. No tactical depth. No moment where you go "holy shit, I have THIS ability that does THIS thing and only I can do it." It's all just description. And that's fine! But it's not what I wanted.

On the other hand, tactical games - games with classes and abilities and cool powers - those games often turn into tactical miniatures games where the narration becomes secondary. You're not describing your character inspiring the troops, you're saying "I use my Inspiring Presence ability to give +2 to attack rolls within 30 feet." The mechanics overshadow the fiction.

**I wanted both.** I wanted the tactician to feel as cool and unique as the wizard. I wanted players who are good at narration to still benefit from having specific abilities on their sheet. I wanted fast, flowing gameplay that doesn't bog down in rules, but still has meaningful tactical choices.

So I made Narraject.

### The Core Problem I'm Solving

Here's the design challenge that keeps me up at night: **How do you make a character with no magic feel as impactful as a character with magic?**

In most narrative games, a clever player can just narrate being tactical. They can describe rallying the troops, creating diversions, coordinating attacks - all without any mechanical support. Which is great! Except it means there's no reason to play "the tactician" when you could play "the wizard who also narrates tactical stuff."

The wizard gets spells - third-party mechanical elements that do things you can't just narrate. But what does the tactician get? What makes them special besides description?

This is the problem Narraject solves. Every Path (my term for classes/jobs/roles) gets abilities that affect the narrative in ways you can't just describe. The tactician doesn't just inspire people with words - they spend resources to make their allies' actions more impactful in concrete, mechanical ways. The investigator doesn't just look for clues - they have abilities that let them inject information into the scene that the GM has to honor.

Your character sheet matters. Your choices matter. And the story still moves fast.

### What This System Does

**Narraject is designed to:**

1. **Give every character type mechanical teeth** - Whether you're slinging spells or leading troops, you have unique abilities that matter
2. **Keep narrative authority shared** - Players can inject story facts once per session, failures still create progress, description still matters
3. **Move fast** - Roll once, get a result, move on. No attack rolls AND damage rolls. No initiative tracking. No death spirals.
4. **Support any genre** - The core rules are setting-agnostic. Frameworks (setting supplements) add magic, tech, psychic powers, whatever.
5. **Scale elegantly** - Works for street-level noir, epic fantasy, cosmic horror, whatever. The math stays simple.

**The key innovation** is Focus - a resource you spend AFTER seeing your roll to guarantee success. It feels good because you never waste it, but your stats cap how much you can spend, so your choices during character creation matter.

The other key innovation is that success means your stated intent happens. Period. No "you hit but don't do enough damage." If you say "I want to kill the guard" and you succeed, the guard dies. This keeps play moving and makes every roll meaningful.

### Who This Is For

This game is for people who:
- Love narrative games but want more crunch
- Love tactical games but want faster play
- Want every character to feel unique and powerful
- Trust their players to be co-authors
- Want to run games in multiple genres without learning new systems

If you like games like Blades in the Dark, Fate, or Cortex, but wish they had more tactical depth and specific abilities, this might be for you.

If you like games like D&D or Draw Steel, but wish combat was faster and more narrative, this might be for you.

If you're tired of systems where "good at narration" is more powerful than anything on your character sheet, this might be for you.

### A Note on Experience Level

**This is not designed as an entry-level system.**

Look, I'm going to be honest with you: this game puts a lot of pressure on the GM. The narrative play style requires you to think on your feet, improvise constantly, track multiple story threads, and make failures interesting. You're not just running encounters from a book - you're co-creating a story with your players in real-time.

That doesn't mean new players and GMs can't play this game and have fun. They absolutely can! But when I designed Narraject, I designed it with **experienced players in mind**. Players who are comfortable with narrative authority. GMs who can improvise and don't need rigid structure.

If you're an experienced GM looking for something that gives you tools without boxing you in, this might be exactly what you need.

### The Design Philosophy

I believe that **mechanics should enable fiction, not replace it**.

Your Anchor (skill/background) in "Combat Training" doesn't say exactly what you do in combat - it adds dice when you describe fighting. Your Burden "Haunted by the Dead" doesn't have a rigid penalty - it removes dice when the GM agrees it's relevant to the scene.

But your Path abilities? Those are concrete. Specific. When the Tactician uses "Coordinated Strike," their ally's next attack is MORE EFFECTIVE in a way that's mechanically real, not just described. When the Mentalist uses "Read Surface Thoughts," they get information the GM must provide, not just permission to ask.

This creates a beautiful space where description and mechanics dance together. You describe how you do things (fiction), and your character sheet determines what you can achieve (mechanics).

### What's In This Document

This is the **complete core rules** - everything you need to run Narraject in any setting. Character creation, core mechanics, combat, progression, GM principles, everything.

Later sections include **Frameworks** - setting-specific rules and Paths (character classes) for fantasy, sci-fi, horror, and more. Each Framework is modular. Use one, use many, or ignore them and make your own.

This is version 0.3. It's ready for playtesting. Things will change based on feedback. If you playtest this and have thoughts, I want to hear them.

### A Note on Inspiration

I owe massive debts to games that came before: Blades in the Dark for player agency, Fate for aspect-based play, Cortex for flexible dice pools, and Draw Steel for heroic resource management. I'm standing on the shoulders of giants here, and I'm not pretending otherwise.

The goal isn't to revolutionize the hobby. The goal is to make the game I wanted to play, and share it with people who might want the same thing.

If that's you, welcome. Let's tell some stories.

— Tom Cohen

---

## 1. Core Mechanics

### The Roll

**When to Roll:**
- The outcome is uncertain
- Failure has consequences
- Success isn't trivial

**Don't roll when:**
- The task is routine
- There's no pressure
- Failure just means "nothing happens"

### The Core Loop

1. **Declare Intent:** "I want to [Goal] by [Approach]"
2. **Set Difficulty:** GM tells you how many Successes you need
3. **Build Hand:** Gather d6s from Rating + Gear + Aspects
4. **Determine Threshold:** Check if Anchors or Burdens apply
5. **Roll:** Count Successes based on threshold
6. **Decide to Focus (Optional):** If you failed, you can spend Focus to add Successes (1 Focus = +1 Success)
7. **Result:** Succeed or Fail - Reality changes

### Success Thresholds

| State | Success On | Chance Per Die |
|-------|------------|----------------|
| **Normal** (no modifiers) | 4, 5, 6 | 50% |
| **With Anchor** (relevant skill) | 3, 4, 5, 6 | 66.7% |
| **With Burden** (relevant weakness) | 5, 6 only | 33.3% |
| **Moderate Condition** (relevant injury) | 5, 6 only | 33.3% |
| **Severe Condition** (relevant injury) | 6 only | 16.7% |

**Note:** Minor Conditions remove -1d6 from pool instead of shifting threshold.

**Key Rules:**
- Anchors and Burdens don't add or remove dice - they shift what counts as success
- If both an Anchor AND a Burden apply, they cancel out (use normal 4-5-6)
- Only ONE Anchor can apply per roll (pick the most relevant)
- Only ONE Burden can apply per roll (GM picks if multiple could apply)
- Only the WORST Condition applies per roll (Severe > Moderate > Minor)

### The Golden Rules

**SUCCESS = INTENT HAPPENS (PERIOD)**
- No "you hit but didn't do enough damage"
- No "you persuaded him but he still won't do it"
- If the dice say success, what you described becomes true

**AMBITION SETS DIFFICULTY**
- Want to distract the dragon? Moderate (2 Successes)
- Want to one-shot the dragon with a fork? Mythic (10+ Successes)
- The GM never says "you can't try" - they just set the difficulty

**SOCIAL ROLLS CLARIFICATION**

"Success = intent" is not mind control. The GM sets difficulty based on both what's being asked AND the NPC's motivations:

| Request | Typical Difficulty |
|---------|-------------------|
| Persuade guard to let you pass | 3 (Challenging) |
| Persuade guard to look the other way while you steal | 5 (Very Hard) |
| Persuade guard to abandon their post | 6-7 (Heroic) |
| Persuade guard to betray their family | 8+ or impossible |

Unreasonable requests have unreasonable difficulties. Asking someone to act against their core values may simply be impossible - no roll allowed.

### Building Your Dice Pool

```
DICE POOL = Stat Rating + Gear + Aspects - Conditions
```

**Sources of Dice:**
1. **Stats (Rating):** Base dice you always have (1d6 per Rating point)
2. **Gear:** Weapons, tools, equipment (+1d6 to +3d6)
3. **Aspects:** Situational advantages (+1d6 to +2d6)

**Removing Dice:**
- **Minor Conditions:** -1d6 to relevant rolls

**Modifying Success Threshold (Conditions):**
- **Moderate Conditions:** 5-6 only = success for relevant rolls
- **Severe Conditions:** 6 only = success for relevant rolls

**Modifying Success Threshold (not dice):**
- **Anchors:** If relevant, 3s also count as success (3-4-5-6)
- **Burdens:** If relevant, only 5-6 count as success

**Adding Successes After Rolling:**
- **Focus:** Spend AFTER rolling if you failed (1 Focus = +1 Success, up to Stat Rating limit)

### Assisting Other Characters

Before another character rolls, you may **Assist** them:

1. **Describe how you help** - What are you doing to contribute?
2. **GM agrees it's relevant** - Your assistance must make sense in the fiction
3. **Benefit:** The rolling character gains **+1d6** to their pool

**Lending Your Anchor:** If you have a relevant Anchor and the lead character doesn't, your assistance can grant them the Anchor's benefit (3-4-5-6 threshold) instead of +1d6. You're effectively lending your expertise.

**Best Stat Option:** Sometimes the most capable character should lead, with others assisting:
- Example: Shoving a heavy metal door - the strongest character uses their Might
- Other characters add +1d6 each to that character's roll
- The group uses the best stat for the task; assistants contribute dice

**Example:**
- Kira (Might 2) wants to break down a door
- Marcus (Might 5, has "Combat Training" Anchor) offers to lead instead
- Kira assists Marcus, adding +1d6 to his roll
- Marcus rolls 6d6 with the Anchor threshold (3-4-5-6 = success)

### Focus in Action: Complete Example

**Situation:** You need to hack a secured system (Difficulty 4 - Hard).

**Your Stats:** Intellect Rating 3, Current Focus: 5

**Your Pool:** Rating 3 (3d6) + "Hacker" Anchor Advanced (2d6) + Quality Laptop (2d6) = **7d6 total**

**You Roll:** 7d6 and get `[6, 5, 4, 3, 2, 2, 1]` = **3 Successes** (the 6, 5, and 4)

**You Failed!** You needed 4 Successes but only got 3. You're 1 Success short.

**Decision Point - Do You Focus?**

**Option A: Accept the Failure**
- You failed, but per the rules, failure still has impact
- Maybe you partially crack the system, alert security, or learn something valuable
- Keep your 5 Focus for later challenges

**Option B: Spend 1 Focus (Focusing to Succeed)**
- You're 1 short, so spend 1 Focus to add +1 Success
- Your Intellect Rating is 3, so you CAN spend up to 3 Focus on this roll
- Your 3 Successes + 1 Focus = 4 Successes = SUCCESS!
- You now have 4 Focus remaining
- **This feels good:** You only spent Focus because you needed it

**Option C: What if you rolled 1 Success?**
- You'd be 3 short, so you could spend 3 Focus (your max for Intellect 3)
- 1 Success + 3 Focus = 4 Successes = SUCCESS!
- You'd have 2 Focus remaining

**Option D: What if you rolled 0 Successes?**
- You'd be 4 short, but can only spend 3 Focus (your Rating limit)
- 0 Successes + 3 Focus = 3 Successes = STILL FAILED (needed 4)
- You'd have to accept failure (spending Focus on a failed roll is allowed but wasteful)
- **This is why you don't rely on Focus for dump stats!**

**The Strategic Choice:** Focus is never wasted because you spend it AFTER seeing the roll. You know exactly how much you need. But your Rating still caps how much you can spend, so invest in stats you care about!

### Success Counting

**For d6s:** Roll all dice. Count 4s, 5s, and 6s as Successes.

Compare total Successes to Difficulty:
- **Successes ≥ Difficulty:** SUCCESS - You achieve your intent
- **Successes < Difficulty:** FAILURE - You don't get what you wanted

**Each die has a 50% chance of Success** (rolling 4, 5, or 6).

### Difficulty Scale

| Successes | Difficulty  | Example                                        |
| --------- | ----------- | ---------------------------------------------- |
| **0**     | Trivial     | No roll needed                                 |
| **1**     | Easy        | Climb a ladder, spot obvious clue              |
| **2**     | Moderate    | Pick simple lock, persuade neutral stranger    |
| **3**     | Challenging | Hit moving target, hack secured system         |
| **4**     | Hard        | Scale sheer wall in rain, convince hostile NPC |
| **5-6**   | Very Hard   | Near-impossible shot, walk on fire             |
| **7-8**   | Heroic      | Feats that define legends                      |
| **9-10**  | Legendary   | Once-in-a-lifetime achievements                |
| **10+**   | Mythic      | Feats of gods                                  |


### Degrees of Success

**Excess Successes** make your success better:

| Margin | Effect |
|--------|--------|
| +1-2 Successes | **Solid Success** - Clean execution, maybe a small bonus |
| +3-4 Successes | **Strong Success** - Exceptional result, GM describes extra benefit |
| +5+ Successes | **Triumph** - You narrate something impressive |

### Degrees of Failure

**Important:** Failure doesn't mean "nothing happens." Your actions still have impact - just not the outcome you intended.

| Result | Effect |
|--------|--------|
| 1-2 Successes short | **Near Miss** - Almost had it, GM may offer cost for partial success |
| 3+ Successes short | **Clear Failure** - It didn't work, but you made progress |
| 0 Successes | **Catastrophic Failure** - Backfired significantly |

### Failure Still Creates Impact

Even when you fail, your actions affect the world. The GM should describe how:

**Combat Example - "I want to kill the guard":**
- **Success (4+):** Guard dies
- **Failure (2-3):** You don't kill him, but he's wounded (takes a Condition), loses his weapon, or retreats
- **Catastrophic (0-1):** Your attack misses entirely and alerts others, or you drop your weapon

**Social Example - "I want to persuade the merchant to give us supplies":**
- **Success (3+):** Merchant agrees and gives you supplies
- **Failure (1-2):** He refuses now, but you've planted a seed - he might reconsider later, or he respects your argument even if unconvinced. Future negotiations with him are easier (+1d6 Aspect: "Made an impression")
- **Catastrophic (0):** He's offended and raises prices, or calls the guards

**Investigation Example - "I want to find the secret passage":**
- **Success (3+):** You find it
- **Failure (1-2):** You don't find it, but you notice architectural oddities that suggest there IS a hidden passage somewhere. You've narrowed down where to look
- **Catastrophic (0):** You trigger a trap while searching, or waste so much time that the enemy arrives

### GM Guidance on Failed Rolls

When a player fails, ask yourself:

1. **What did they learn?** Even failures reveal information
2. **What changed?** Their action had consequences, even if not intended
3. **What opportunity emerged?** How can this failure create new story possibilities?

**Good Failure Outcomes:**
- You soften the target for the next attempt
- You learn something valuable
- You create an opening for allies
- You change the situation (even if not as planned)
- You set up future success

**Bad Failure Outcomes:**
- "Nothing happens, try again"
- "You fail completely with zero impact"
- "Everything is exactly as it was before"

**The Principle:** Every roll should move the story forward, whether success or failure. Failure means you didn't achieve your intent, but it doesn't mean you had no effect.

### Contested Rolls

When two characters directly oppose each other:

1. **Both characters roll** using their relevant stats and modifiers
2. **Compare Successes** - higher total wins
3. **On a tie** - nothing changes, stalemate (neither side gains advantage)

**Examples:**
- Arm wrestling: Both roll Might, higher wins
- Opposed persuasion: Both roll Persona, higher wins
- Chase scene: Both roll Agility, higher wins (or gains/loses ground)
- Grappling: Both roll Might or Agility (depending on approach)

**Note:** Most NPC interactions don't use contested rolls - NPCs set a Difficulty and players roll against it. Contested rolls are primarily for PvP or special dramatic moments.

### Stats Determine Approach

Actions aren't locked to specific stats. You use the stat that matches your description:

| Stat | Domain |
|------|--------|
| **Might** | Physical power, endurance, melee combat, resisting harm |
| **Agility** | Speed, reflexes, coordination, stealth, balance, ranged combat |
| **Intellect** | Knowledge, perception, reasoning, technical skills |
| **Persona** | Social influence, willpower, presence, deception |

**Example - Opening a Locked Door:**
- **Might:** Kick the hinge until it snaps
- **Agility:** Slide a lockpick into the tumbler
- **Intellect:** Hotwire the electronic keypad
- **Persona:** Shout "Open up!" and hope they listen

**Example - Getting Past a Guard:**
- **Might:** Knock them out with a headbutt
- **Agility:** Cartwheel behind them while they're distracted
- **Intellect:** Memorize their patrol pattern and time your approach perfectly
- **Persona:** Confidently walk past carrying a clipboard like you belong there

**Example - Finding a Hidden Clue:**
- **Might:** Smash every piece of furniture until something falls out
- **Agility:** Feel along the walls for hidden switches
- **Intellect:** Deduce where someone would logically hide something
- **Persona:** Convince the NPC who hid it to just tell you where it is

**Example - Escaping from Prison:**
- **Might:** Bend the bars with your bare hands
- **Agility:** Squeeze through the ventilation shaft
- **Intellect:** Hack the electronic lock with a smuggled chip
- **Persona:** Seduce the guard into letting you out

**Example - Stopping a Runaway Cart:**
- **Might:** Grab it and dig your heels in
- **Agility:** Leap onto it and pull the brake
- **Intellect:** Calculate the trajectory and build a barricade where it'll hit
- **Persona:** Yell "STOP!" really, really loud and hope the cart listens

**Example - Learning the Villain's Plan:**
- **Might:** Grab them by the collar and demand they talk
- **Agility:** Pickpocket their secret documents
- **Intellect:** Piece it together from context clues and overheard conversations
- **Persona:** Pretend you already know everything and trick them into confirming it

---

## 2. Character Stats & Focus

### The Four Stats

Each character has four stats: **Might**, **Agility**, **Intellect**, **Persona**

Each stat has two values:

1. **Rating** - Your innate capability (determines base dice)
2. **Focus** - Your shared pool of concentration and determination (0-6 points)

### Rating

Your Rating determines:
- Minimum dice you roll (Rating = Xd6)
- Your core capability in that stat

**Rating ranges from 1-5** for most characters (legendary characters can go to 6-10).

### Focus

**Focus** is a shared resource pool representing your character's concentration, determination, and will to push beyond their limits.

**Focus Capacity:** All characters have a Focus pool of **0-6 points** (shared across all stats).

**How Focus Works:**

When you make a roll, you can spend Focus **AFTER seeing the result** to add Successes:

- **Spend 1 Focus = Add 1 Success to your roll**
- You can spend multiple Focus on a single roll
- **LIMIT: Cannot spend more Focus than the Stat Rating you're using**
- You only spend Focus if you failed - it's never wasted

**Why Spend After Rolling?**
- You know exactly how many Successes you're short
- You only spend what you need
- No risk of "wasting" Focus on a roll that would have succeeded anyway
- Still feels risky because your Rating caps how much you can spend

**Example:**
- Task requires 4 Successes (Hard difficulty)
- Your Intellect Rating is 3
- You roll and get 2 Successes - you're 2 short
- You spend 2 Focus to add +2 Successes → 4 total = SUCCESS!
- If you had rolled 1 Success (3 short), you could spend 3 Focus (your max) to succeed
- If you had rolled 0 Successes (4 short), you could only spend 3 Focus (your Rating limit) and would still fail by 1

**Why This Matters:**
- A character with Persona 1 can only add 1 Success with Focus on social rolls
- They cannot "auto-win" hard conversations by burning all 6 Focus
- Your natural talent (Rating) determines how much you can push
- Specialists can recover from bad rolls in their areas of expertise
- Focus is never wasted because you spend after seeing the roll

### Recovering Focus

Focus is precious and limited. You recover it in two ways:

#### 1. Rest and Narrative Downtime

**Narrative Long Rest** (full night's sleep, eating, interacting with each other):
- **Restores Focus to 3** (not to maximum)
- Getting above 3 Focus requires the NP gamble (see below)
- **This requires actual downtime** - sleeping, eating, meaningful character interaction

**GM Guidance:** Use Focus recovery as a pacing tool. If players are rushing, they burn Focus. If they take time to rest and roleplay, reward them with Focus recovery. The cap at 3 ensures Focus remains a meaningful resource even after rest.

#### 2. Converting Fresh NP to Focus (The Gamble)

When you **just earned** fresh Narrative Points (NP) in the current scene, you can attempt to convert that NP into Focus:

**The Process:**
1. Immediately after earning NP, declare you want to attempt Focus recovery
2. Choose one of the NP you just earned (you can only gamble fresh NP, not stored NP)
3. Roll 1d6
4. **If the result is HIGHER than your current Focus pool:** Gain 1 Focus, consume the NP
5. **If the result is EQUAL TO or LOWER than your current Focus:** Keep the NP, gain no Focus

**Example:**
- You currently have 4 Focus
- You just earned 1 NP for great roleplay
- You roll 1d6 and get a 5
- 5 > 4, so you gain 1 Focus (now at 5) and lose the NP
- If you had rolled 1-4, you would keep the NP and gain no Focus

**Important Restrictions:**
- Can only gamble **fresh NP earned this scene** (not stored NP from previous sessions)
- Can only attempt the roll once per NP earned (no re-rolling)
- If you fail the roll, you keep the NP - it wasn't wasted
- Maximum Focus is always 6 (if already at 6, you can't gain more)

**Strategic Choice:** Do you save NP for character advancement, or gamble it for immediate Focus recovery? The higher your current Focus, the harder it is to recover more (you need to roll higher than your current Focus).

### Why This Matters

**Focus creates meaningful choices:**
- Do you spend Focus now to guarantee success, or save it for later?
- Do you gamble your hard-earned NP for Focus recovery, or save it for progression?
- Do you push forward exhausted, or take time to rest and recover?

**Focus creates narrative pacing:**
- Characters who rest and interact recover Focus
- Characters who rush burn through Focus and become vulnerable
- Big moments require spending Focus - making them feel significant

### The Desperation Roll

If your Focus is empty, no traits apply, no gear helps, and GM grants nothing:

**You roll your Stat Rating in d6s.** That's it. You're never completely helpless.

### Increasing Stats: Narrative Milestones Only

**Stats cannot be purchased with NP.** They represent innate capability and only change through story.

**How Stats Increase:**
1. **GM discretion at narrative milestones** (major story beats, character arcs resolved)
2. GM awards X rating points to distribute as player chooses
3. **Setting-specific roles/abilities** (future content)

**Examples of Stat Increase Moments:**
- Completing a major training arc with a master
- Surviving a transformative ordeal (near-death, spiritual awakening)
- Achieving a significant character goal
- GM-defined milestones (every 10 sessions, major campaign arcs, etc.)

**When GM awards stat points:**
- "You've completed your training with the master. Gain 1 rating point to distribute."
- "After surviving that ordeal, you've fundamentally changed. Gain 2 rating points."
- Player decides which Stat(s) to increase

**Why narrative milestones?**
- Stats represent innate capability, not learned skills
- Makes stat increases feel epic and meaningful
- Prevents stat-stacking through NP grinding
- Keeps character progression focused on Anchors and Burdens
- Leaves room for setting-specific advancement systems

---

## 3. Character Creation

### Your Character Concept

Your character has two simple elements:

> **[Name]** - What you're called
> **[Descriptor]** - One line that captures who you are, what you are, and what you do

**The Descriptor** can be anything that helps define your character:
- A profession: "Grizzled detective," "Street rat turned noble," "Wandering chef"
- A concept: "Haunted by past mistakes," "Always looks for the peaceful solution," "Too clever for their own good"
- A vibe: "Chaotic energy incarnate," "The responsible one," "Mysterious stranger with a dark past"
- A goal: "Seeking revenge for her murdered family," "Trying to prove himself worthy," "Running from a terrible secret"

**Examples:**
- **Marcus Kane** - Former corporate spy turned revolutionary
- **Kira** - Sniper who never misses, but always hesitates
- **Doc** - Combat medic with a drinking problem
- **Zephyr** - Thief with a heart of gold and sticky fingers
- **The Professor** - Knows everything, understands nothing

### The Creation Process

**Work with your GM throughout character creation.** The GM will help incorporate your character into the story and set appropriate power levels for the campaign.

**The GM decides:**
- How many stat points to distribute
- How many Anchors/Burdens you start with
- What gear is available or appropriate
- How many Focus points you begin with
- The overall power level expectations

**There are no clear-cut character levels**, but the GM uses a power level scale (see Power Levels section) to balance the game and set expectations for what difficulties should feel achievable.

**Steps:**

1. **Come up with Name and Descriptor** - Who are you? Work with GM to fit the story
2. **Assign Stat Ratings** - GM tells you how many points to distribute among Might, Agility, Intellect, Persona
3. **Select starting Anchors** - GM tells you how many (typically 3-5). What are you good at?
4. **Balance with Burdens (Rule of Balance: 1 Burden per 1 Anchor)** - What complicates your life?
5. **Choose starting Gear** - Select from GM's available options or campaign-appropriate equipment
6. **Start with Focus** - All characters start with Focus 3

**Time to Create:** 15-20 minutes (10 for experienced players)

### Starting Character Templates

For GMs who want guidance, use these default starting packages:

| Template | Stat Points | Suggested Distribution | Anchors | Burdens | Starting Focus |
|----------|-------------|------------------------|---------|---------|----------------|
| **Street** (Level 1) | 6 | 3/1/1/1 or 2/2/1/1 | 2-3 (1 Advanced, 1-2 Basic) | 2-3 | 3 |
| **Standard** (Level 2) | 10 | 4/3/2/1 or 4/2/2/2 | 4 (2 Advanced, 2 Basic) | 4 | 3 |
| **Heroic** (Level 3) | 14 | 6/4/2/2 or 5/4/3/2 | 5-6 (3 Advanced, 2-3 Basic) | 5-6 | 3 |

**Street Level:** Civilians, rookies, ordinary people thrust into danger. Struggles against Level 2+ threats.

**Standard:** Experienced operatives, trained professionals, starting adventurers. The recommended default for most campaigns.

**Heroic:** Elite professionals, legendary figures, characters with significant backstory achievements.

**Note:** These are recommendations. The GM has final say on starting resources.

---

## 4. Anchors

### What Are Anchors?

**Anchors** are skills, backgrounds, training, connections and experiences that shift your success threshold when relevant.

**Mechanically:** When an Anchor applies, **3s also count as successes** (3-4-5-6 instead of just 4-5-6). This increases your success rate from 50% to 66.7% per die.

**Narratively:** Who you are, what you've done, story hooks for the GM

### The Rule of Balance

**You must have 1 Burden for every 1 Anchor you possess.**

If you have 4 Anchors, you must have 4 Burdens. Gain a new Anchor = gain a new Burden (or deepen existing).

### How Anchors Work

| Without Anchor | With Anchor | Effect |
|----------------|-------------|--------|
| 4, 5, 6 = Success | 3, 4, 5, 6 = Success | +16.7% per die |
| 50% per die | 66.7% per die | ~33% more successes |

**Example:** Rolling 6d6
- Without Anchor: expect ~3 successes
- With Anchor: expect ~4 successes

### When Anchors Apply

An Anchor applies when the fiction supports it.

**Important:** Only ONE Anchor applies per roll, even if multiple seem relevant. Pick the most fitting one.

### Broad vs. Specific Anchors

**Broad Anchors:**
- Apply to many situations
- Examples: Athletics, Combat, Social, Technology
- Pros: Frequent use
- Cons: Less narrative flavor

**Specific Anchors:**
- Apply to narrower situations
- Examples: Expert Marksman, Cat Burglar, Forensic Pathologist
- Pros: Memorable, create story hooks
- Cons: Come up less often

**The Sweet Spot:** Specific enough to be interesting, broad enough to be useful.

**Guideline:** Good anchors are invoked 4-6 times per session.

### Creating Good Anchors

**Start with Fiction:**
- What have they done for a living?
- What training or skills?
- What hobbies or passions?
- What reputation?
- What organization shaped them?

**Make It Evocative:**
- Boring: "Shooting"
- Better: "Marksman"
- Best: "Sniper, Never Misses, Deadeye"

**Think About Relationships:**
- Organizations: "Guild Assassin," "Corporate Heir"
- Reputations: "Famous Detective," "Wanted Outlaw"
- Mentors/Rivals: "Trained by Master Chen"
- Cultural Ties: "Daughter of the Wastes"

**Vary Your Portfolio:**
- Don't make all anchors the same type
- Mix: Combat, social, knowledge, technical, physical
- Give GM lots of ways to involve your character

### Common Mistakes

**1. Anchors That Are Just Stats:**
- Bad: "Strong" (that's Might), "Smart" (that's Intellect)
- Good: "Olympic Wrestler," "Engineering Degree"

**2. Boring Anchors Always On:**
- Bad: "Lucky," "Determined," "Competent"
- If it applies to EVERY roll, it's not an anchor

**3. Anchors That Are Really Burdens:**
- Bad: "Hotheaded," "Overconfident," "Haunted"
- Anchors ONLY help, never hinder

---

## 5. Burdens (Flaws)

### What Are Burdens?

**Burdens** are vulnerabilities you create for your character - narrative hooks and weaknesses that the GM can use to make the story personal.

**Think of them as knives:** You forge them and hand them to the GM to stab you with.

**Mechanically:** When a Burden applies, **only 5s and 6s count as successes** (instead of 4-5-6). This decreases your success rate from 50% to 33.3% per die.

**Narratively:** Give the GM ammunition to make your character's story matter

### The Rule of Balance

**You must have 1 Burden for every 1 Anchor you possess.**

### How Burdens Work

| Without Burden | With Burden | Effect |
|----------------|-------------|--------|
| 4, 5, 6 = Success | 5, 6 only = Success | -16.7% per die |
| 50% per die | 33.3% per die | ~33% fewer successes |

**Example:** Rolling 6d6
- Without Burden: expect ~3 successes
- With Burden: expect ~2 successes

**Important:** Only ONE Burden applies per roll. If multiple could apply, GM picks the most relevant.

### Types of Burden (11 Categories as example)

**1. People You Care About:**
- Living or dead, named NPCs GM can threaten
- Examples: Sibling who thinks you're dead, mentor you betrayed
- Effect: Minor to Moderate penalty when threatened/present

**2. Phobias and Trauma:**
- Things that make you freeze, panic, lose control
- Examples: Claustrophobia, fire, heights, darkness
- Effect: Moderate to Severe penalty in trigger situations

**3. Mysteries in Your Past:**
- Unanswered questions that haunt you
- Examples: Unknown parents, missing time, prophecy
- Effect: Usually narrative, sometimes penalties when relevant

**4. Enemies and Rivals:**
- Named antagonists who want you dead/captured/broken
- Examples: Crime boss you testified against, rival seeking revenge
- Effect: Minor penalty when near, narrative complications

**5. Obligations and Loyalties:**
- Debts, oaths, commitments that constrain you
- Examples: Owe a favor, sworn to protect, must follow code
- Effect: Penalties when violating, complications when conflicts

**6. Failed Obligations:**
- Promises you broke, duties you abandoned
- Examples: Mission you failed, person you couldn't save
- Effect: Moderate penalty in situations that remind you

**7. Crimes and Secrets:**
- Things you've done, things you're hiding
- Examples: Murder, desertion, theft, betrayal
- Effect: Severe penalty if exposed, complications when threatened

**8. Discrimination Experienced:**
- Prejudice, marginalization, systemic barriers
- Examples: Fantasy racism, social class barriers, persecution
- Effect: Minor to Moderate penalty in hostile social situations

**9. Prized Possessions:**
- Items you'll risk everything to protect/recover
- Examples: Family heirloom, last gift from dead loved one
- Effect: Minor penalty when separated, narrative hooks when threatened

**10. Physical Limitations:**
- Disabilities, injuries, conditions that hinder you
- Examples: Missing limb, chronic pain, poor vision, addiction
- Effect: Moderate to Severe penalty on relevant actions

**11. Personality Burdens:**
- Character traits that get you in trouble
- Examples: Overconfident, cowardly, greedy, impulsive, arrogant
- Effect: Minor to Moderate penalty when trait causes poor decisions

### When Burdens Apply

A Burden applies when:
- The situation directly triggers your weakness
- Your fear/limitation would realistically hinder you
- The narrative benefit outweighs the mechanical penalty

**Players can invoke their own Burdens** to earn Narrative Points (NP).

### Earning NP from Burdens

When a Burden **meaningfully complicates your life** - causes failure, forces difficult choice, or creates dramatic tension - the GM can award **1 NP**.

**Who Can Invoke Burdens:**
- **Players** can invoke their own Burdens for dramatic effect
- **GMs** can invoke a player's Burden at any time
- When GM invokes a Burden, the player still earns NP

**GM Invocation:** If the GM notices a Burden never triggers naturally, they can force it into play. This prevents "paper Burdens" that players take but never engage with.

**When to Award NP (Good Stab):**
- Player roleplays the complication honestly
- Failure creates dramatic tension
- Difficult choice emerges
- Character relationships deepen
- The moment matters to the table

**When NOT to Award NP (Boring Stab):**
- Burden applies mechanically but creates no drama
- Just a tax on the dice pool
- Routine penalty, no difficult choice
- No memorable moment created

### Variety Matters

Don't make all Burdens the same type. Mix:
- Mechanical penalties (phobias, limitations)
- Narrative hooks (enemies, secrets, obligations)
- Both mechanical and narrative (people, possessions)

### Forging Your Burdens

**Collaborate with GM before play:**
- Which Burdens are mechanical? Which are narrative?
- How severe is each?
- When do they apply?
- Can GM introduce without warning?
- Are any topics off-limits?

### Starting Burdens

Most starting characters have **3-5 Burdens** (matching 3-5 Anchors):
- Mix of severities (Minor, Moderate, maybe 1 Severe)
- Mix of types (mechanical, narrative, both)
- Specific and evocative

---

## 6. Gear & Equipment

### Gear is Situational

**There are no fixed tiers or tags for gear.** Instead, gear can be anything and provides bonuses based on how it's used in the situation.

**The same piece of gear might:**
- Add +1d6 in one scenario
- Add +2d6 in another scenario where it's particularly suited
- Add nothing in a third scenario where it doesn't help
- Remove -1d6 in situations where it hinders

**General Guideline:** Most relevant gear adds **+1d6** when it applies. The GM decides when gear is relevant and how much it helps.

### Special or Superior Gear

If a player acquires **narratively special** gear (legendary sword, high-tech rifle, masterwork tool), the GM may note that it provides higher bonuses:
- **Superior:** +2d6 when relevant
- **Exceptional:** +3d6 when relevant

The gear description should note this, along with any specific abilities it grants.

### Example: Weapons

A sword adds dice when you attack with it. How many?
- **Basic sword:** +1d6 to attack rolls
- **Well-crafted blade:** +2d6 to attack rolls (if the GM says it's special)
- **Legendary ancestral weapon:** +3d6 to attack rolls + special narrative abilities

The weapon doesn't have a "tier" - its bonus depends on what the GM and player agree it represents in the story.

### Armor in Combat

Armor provides **situational defense bonuses** rather than reducing Condition severity.

**Light Armor (Leather, Padded, Cloth):**
- **Agile armor** - prioritizes mobility
- +1d6 to defense rolls against **Agility-based attacks** (arrows, daggers, quick strikes)
- No bonus against **Might-based attacks** (heavy weapons, crushing blows)
- **Penalty:** None to stealth or movment

**Heavy Armor (Plate, Chainmail, Full Armor):**
- **Protective armor** - prioritizes defense
- +1d6 to defense rolls against **Might-based attacks** (swords, axes, crushing blows)
- No bonus against **Agility-based attacks** (can't dodge well in heavy armor)
- **Penalty:** -1d6 to Agility rolls and stealth attempts

**Examples in Play:**

**Scenario 1: Archer shoots arrow at you**
- Wearing Light Armor: +1d6 to your dodge roll (agile, can evade)
- Wearing Heavy Armor: No bonus (too slow to dodge arrows)

**Scenario 2: Knight swings greatsword at you**
- Wearing Light Armor: No bonus (cloth won't stop a blade)
- Wearing Heavy Armor: +1d6 to your defense roll (plate deflects the blow)

**Scenario 3: Sneaking past guards**
- Wearing Light Armor: No penalty
- Wearing Heavy Armor: -1d6 to stealth roll (clanking and heavy)

### Consumables and Time-Limited Gear

**Narrative Injection Philosophy:** We believe time-limited gear encourages adaptive, dynamic play.

**Why Time-Limited Gear?**
- Forces players to **use** powerful items instead of hoarding them
- Creates meaningful tactical choices ("Do I use this now or save it?")
- Introduces complex, adaptive play patterns
- Prevents static "optimal loadout" syndrome

**Types of Limits:**
- **One-time use:** Consumed when used (potions, grenades, scrolls)
- **Durability:** Breaks after X uses or specific circumstances
- **Narrative limits:** "Can only carry 2 magic scrolls due to dark energy interference"
- **Scene-based:** "This disguise only works once before they recognize you"
- **Cooldown:** "The artifact needs time to recharge"

**Examples:**

**One-Time Consumables:**
- Medkits (bonus to healing rolls or clear Minor Condition)
- Ammo (reload ranged weapons, limited supply)
- Magic scrolls (+3d6 to one roll, then consumed)
- Explosives (create environmental advantage, one use)
- Antidotes (clear poison Condition, single use)

**Narrative-Limited Items:**
- **"You can only carry 2 dark magic scrolls at once"** - forces choice between which scrolls to bring
- **"The disguise kit works once per location"** - can't reuse same trick
- **"The holy water damages undead, but you only have 3 vials"** - resource management

**Time-Pressured Gear:**
- **"This potion expires in 24 hours"** - use it or lose it
- **"The hacked security pass only works until they notice"** - creates urgency
- **"The blessing lasts until sunrise"** - scene-limited buff

The GM decides what consumables do, when they're useful, and what limits apply. **Encourage use, not hoarding.**

---

## 7. Narrative Injection

### What Is Narrative Injection?

**Narrative Injection** is your ability - **once per session** - to inject a story element, context, or fact into the narrative at any moment.

Think of it as your "story authorship token."

### When to Use It

**You can use it:**
- Before a roll to establish helpful context
- After a roll to reframe the outcome
- After a failure to introduce a complication that changes the situation
- Between scenes to establish facts about the world
- During combat to reveal a crucial detail
- At any dramatic moment to create a twist

### How It Works

1. **Declare Your Injection:** Describe the story element you want to inject
2. **GM Evaluates:** GM decides if reasonable and interesting
3. **Reality Changes:** If approved, the injection becomes truth

**No roll required.** Pure narrative authority.

**No cost** (usually). Free to use, one per session automatically.

### Examples

**Desperate Situations:**
- "I know a herbalist not far from here who can help"
- "This is the alley where I grew up - I know every escape route"

**Creating Opportunities:**
- "One of the cult members is an old friend I haven't seen in years"
- "I remember reading about this symbol in an ancient text"

**Reframing Failure:**
- "The bullet ricochets and hits the control panel, causing chaos"
- "My argument fails, but catches attention of someone else who agrees"

**Establishing Facts:**
- "My character has a safe house in this city"
- "I've dealt with this crime boss before - we have history"
- "I prepared for this scenario. I have flashbangs in my coat"

### Optional Categories

For players who want guidance, here are common types of Narrative Injections:

| Category | What It Does | Example |
|----------|--------------|---------|
| **Contact** | Introduce an NPC connection | "I know someone here who owes me a favor" |
| **Preparedness** | Establish you planned ahead | "I brought flashbangs - I planned for this" |
| **Fact** | Declare a world/location detail | "This building has a back entrance through the basement" |
| **Twist** | Add a complication or connection | "One of the cultists recognizes me - we have history" |
| **Reframe** | Change the meaning of an event | "The bullet ricochets and hits the control panel" |

**Note:** These categories are guidance, not restrictions. You can inject anything the GM approves.

### What Makes a Good Injection?

**✅ Good Injections:**
- Connect to your character background
- Add complications, not just solutions
- Create drama
- Make the story more interesting

**❌ Bad Injections:**
- Too convenient ("I have a rocket launcher in my pocket")
- No narrative grounding ("Aliens appear and solve our problem")
- Removes all stakes ("I'm actually invincible")
- No connection to character or story

### GM Guidance

**Say YES when:**
- Connects to character's background/established story
- Makes the scene more interesting
- Creates new complications or opportunities
- Respects table's tone and established fiction

**Say NO (or negotiate) when:**
- Breaks established fiction or contradicts known facts
- Removes all tension or stakes
- Too meta or disconnected from narrative
- Would trivialize important challenges

### Why Only One Per Session?

- Save it for moments that matter
- Don't spam reality-warping every scene
- When you use it, feels significant
- Other players get their moment too

**Your Narrative Injection resets each session.** If you never use it, you're wasting a powerful tool.

### Creating Aspects and Advantages

Beyond Narrative Injection, you can create **Aspects** (beneficial conditions or advantages) through regular play:

**Through Narration:**
- Describe how your actions create advantages for yourself or others
- "I flip the table to create cover" → Aspect: "Behind Cover" (+1d6 to defense)
- "I deliver an inspiring speech" → Aspect: "Motivated" (+1d6 to next ally's action)

**Through Actions:**
- Use your turn to create an advantage instead of attacking
- Roll to set up a beneficial situation
- Success creates an Aspect that you or allies can use

**Aspect Examples:**
- **Tactical:** "High Ground" (+1d6 to attacks from above)
- **Environmental:** "Slippery Floor" (-1d6 to enemy movement)
- **Social:** "Gained Their Trust" (+1d6 to social rolls with them)
- **Situational:** "Studied Their Moves" (+1d6 to predict their actions)

**How Aspects Work:**
- **Typical Bonus:** +1d6 when relevant
- **Duration:** Until the situation changes or scene ends (GM discretion)
- **Anyone can use:** If the Aspect makes sense for their action
- **No roll required:** If it makes narrative sense, the GM can grant it

**The GM decides:**
- When an Aspect is created
- How much it helps (+1d6 or +2d6 for exceptional circumstances)
- How long it lasts
- Who can benefit from it

---

## 8. Combat & Conflict

### The Combat Loop

Combat uses the same core loop as any other action:

1. **DECLARE** - State your intent (what you want to achieve)
2. **ROLL** - Build your pool, roll, count Successes
3. **RESOLVE** - Success means intent happens
4. **ASSESS** - Update Conditions, describe results

**No separate attack and damage rolls.**

### Initiative: What Makes Sense

**Initiative goes by what makes sense narratively.**

- Who would act first in this situation?
- Who has the advantage or surprise?
- What does the fiction suggest?

The GM decides the order based on the scene, then adjusts as needed when circumstances change.

**No initiative rolls. No complex turn order. Just common sense.**

If it's unclear or contested, the GM can:
- Ask for an Agility roll to see who's faster
- Let the player with the idea go first
- Start with whoever has narrative momentum

### Taking Damage

**NPCs have two combat values:**
- **Attack** - Difficulty to defend against (defaults to NPC Level)
- **Damage** - How much damage they deal (defaults to NPC Level)

**Damage Formula:**
```
Final Damage = NPC Damage - Player's Successes (minimum 0)
```

Player successes always reduce damage, even on a "failed" defense. Partial defense helps.

**Examples:**

**Example 1: Defending Against Attack**
- NPC (Attack 4, Damage 4) attacks you
- You roll defense vs Difficulty 4, get 3 Successes
- **Final Damage: 4 - 3 = 1 Stress point**

**Example 2: Barely Defending**
- NPC (Attack 5, Damage 5) attacks you
- You roll defense vs Difficulty 5, get 2 Successes
- **Final Damage: 5 - 2 = 3 Stress points (fills Stress Track)**

**Example 3: Complete Defense**
- NPC (Attack 3, Damage 3) attacks you
- You roll defense vs Difficulty 3, get 4 Successes
- **Final Damage: 3 - 4 = 0 (no damage)**

**Example 4: Slow Devastator**
- NPC (Attack 2, Damage 5) - slow but hits hard
- You roll defense vs Difficulty 2, get 1 Success
- **Final Damage: 5 - 1 = 4 Stress points** (easy to dodge, devastating if caught)

**Example 5: Fast Harasser**
- NPC (Attack 5, Damage 2) - quick but weak hits
- You roll defense vs Difficulty 5, get 3 Successes
- **Final Damage: 2 - 3 = 0** (even partial defense negates weak attacks)

**Note on Failed Attacks:** When a player fails an attack roll, they simply miss. The NPC does not automatically counterattack - that would be a separate NPC action requiring another defense roll.

### Static Damage

Some NPCs or special attacks deal **static damage** regardless of the roll difference.

```
ASSASSIN'S POISONED BLADE
Attack: 4
Special: Poison (if attack succeeds, target takes 2 Stress regardless of roll margin)
```

**How it works:**
- Player defends, gets 3 Successes (would normally take 1 Stress)
- Because of "Poison" special ability, takes 2 Stress instead
- Static damage overrides normal damage calculation

**Other static damage examples:**
- "Brutal Strike: deals 3 Stress on any successful hit"
- "Explosive Blast: deals 2 Stress to everyone in area, no defense roll"
- "Mental Assault: deals 1 Mental Stress, ignores physical defenses"

### Attack Resolution

**Declaring Intent:**
Be specific. Your intent determines both Difficulty and outcome.

- "I slash at his arm to disarm him" → Moderate (2 Successes) → weapon drops
- "I stab him in the heart to kill him" → Hard (4 Successes) → he dies
- "I shoot the gun out of his hand" → Challenging (3 Successes) → weapon flies away

### NPCs and Monsters

**IMPORTANT: NPCs and monsters DON'T ROLL DICE.**

Players always roll - whether attacking or defending. The NPC's Level determines the Difficulty.

**Simple NPCs:**

```
GANG ENFORCER
Level: 3
Motivation: Protect the boss
Special: Pack tactics (+1 to all rolls with allies)
```

**Level determines:**
- Successes needed to affect them (usually Level = Difficulty)
- Threat they pose when attacking (Level = Difficulty to defend)

**Players roll for everything:**
- **Attacking the NPC:** Roll to hit, Difficulty = NPC's Level
- **NPC attacks player:** Player rolls to defend, Difficulty = NPC's Level
- **Players ALWAYS roll, NPCs NEVER roll**

### Specific Action Levels

**GMs have total control over NPC power through specific action levels.**

Instead of one Level for everything, you can give NPCs **different Levels for different actions:**

```
ELITE SWORDMASTER
Attack: 6 (very deadly with a blade)
Defense: 2 (overconfident, leaves openings)
Motivation: Prove superiority
Special: Riposte (if player fails to hit, player takes Minor Physical Condition)
```

```
ANCIENT DRAGON
Physical Attacks: 8 (claws, bite, tail - nearly unstoppable)
Breath Weapon: 10 (legendary destructive power)
Defense vs Physical: 7 (armored scales)
Defense vs Mental: 3 (arrogant, can be tricked)
Motivation: Hoard treasure, crush lesser beings
Special: Fear Aura (first time seeing dragon = Mind check, Diff 5)
```

```
NERVOUS GUARD
Attack: 3 (trained but hesitant)
Defense: 4 (good armor, cautious)
Intimidate: 1 (easily scared)
Motivation: Get through shift without trouble
```

**This gives infinite possibilities:**
- Glass cannon NPCs (high attack, low defense)
- Tank NPCs (low attack, high defense)
- Specialists (high in one stat, low in others)
- Situational threats (deadly in specific circumstances)

**How it works:**
- Player attacks Elite Swordmaster → Roll vs Difficulty 2 (Defense)
- Elite Swordmaster attacks player → Player rolls defense vs Difficulty 6 (Attack)
- Player tries to intimidate Nervous Guard → Roll vs Difficulty 1 (Intimidate)

### NPC Conditions

Most NPCs have **1-3 Conditions** before they're out. Bosses might have more.

NPCs use the same Condition system as players, but simpler:
- **Minor Condition:** -1d6 (if GM tracks NPC pools at all)
- **Moderate Condition:** 5-6 only = success
- **Severe Condition:** 6 only = success, or out of fight (dead, unconscious, fleeing)

**Simple tracking:** Many GMs just use "hits to take down" instead of tracking Conditions:
- Minion: 1 hit
- Tough NPC: 2-3 hits
- Boss: 4-6 hits

### Creating NPCs On The Fly

**NPCs are extremely easy to improvise.**

Worst case scenario: just assign a Level and all rolls are against that Level.

```
RANDOM BOUNCER
Level: 3
```

Done. Players roll vs Difficulty 3 for everything involving this character.

### Encounter Balancing

Use this threat budget system to create balanced encounters:

**Formula:** Compare Total NPC Levels to Sum of Party Levels

| Difficulty | NPC Level Budget | Example (4 Level 2 PCs = 8 total) |
|------------|------------------|-----------------------------------|
| **Easy** | ~50% of party | 4 levels (4× Level 1, or 2× Level 2) |
| **Challenging** | ~100% of party | 8 levels (4× Level 2, or 2× Level 3 + 1× Level 2) |
| **Hard** | ~150% of party | 12 levels (4× Level 3, or 1× Level 5 + 2× Level 3 + minions) |
| **Deadly** | ~200% of party | 16 levels (4× Level 4, or 1× Level 6 boss + Level 3-4 elites) |

**Considerations:**
- Many weak enemies = more actions, can overwhelm through numbers
- One strong enemy = simpler but can be focus-fired down quickly
- Mix of boss + minions often works best for dramatic fights
- High-Damage low-Attack enemies are dangerous but avoidable
- High-Attack low-Damage enemies are consistent chip damage

**Note:** This is a guideline. Terrain, tactics, surprise, and player resources (Focus) all affect actual difficulty.

### Understanding NPC Scale

**What do Levels mean in terms of player capability?**

With the new 50% success rate (4-5-6 = Success), players need approximately 2 dice per Success.

To reliably succeed against an NPC, players need:

| NPC Level | Dice Pool Needed | What This Means |
|-----------|------------------|-----------------|
| **1** | ~2 dice | Trivial opponent - starting characters handle easily |
| **2** | ~4 dice | Moderate opponent - requires some investment or teamwork |
| **3** | ~6 dice | Serious opponent - requires Anchors, gear, or Focus |
| **4** | ~8 dice | Dangerous opponent - requires specialization and preparation |
| **5** | ~10 dice | Very dangerous - requires multiple advantages and Focus |
| **6+** | ~12+ dice | Deadly opponent - requires full optimization and smart play |

**Example: Level 3 NPC**

A Level 3 NPC requires ~3 Successes to defeat. A Level 3 PC can achieve this with:
- Base Stat 6-7 (6-7d6)
- Relevant gear (+1d6)
- Aspect (+1d6)
- **Total: 8-9 dice**
- With Anchor (3-4-5-6 threshold): ~5-6 Successes average
- Without Anchor (4-5-6 threshold): ~4-4.5 Successes average
- Comfortable margin or may need Focus if unlucky

**This means most "standard" NPCs should be Level 1-3.** Higher levels are bosses, experts, and serious threats.

**Design Tip:** Don't inflate NPC levels. A Level 5 opponent is VERY dangerous. A Level 8 opponent requires extraordinary measures to defeat.

---

## 9. Condition Tracks & Consequences

### Instead of Hit Points

Characters track harm through **Condition Tracks**. 

### The Two Core Tracks

| Track | What It Represents | Affects |
|-------|-------------------|---------|
| **Physical** | Bodily harm, injury, exhaustion | Might and Agility rolls (typically) |
| **Mental** | Psychological stress, trauma, confusion | Intellect and Persona rolls (typically) |

**Optional Third Track:**
- **Social:** Reputation damage, trust loss, social standing (for political/intrigue campaigns)

### Condition Slots

Each track has **three slots**: Minor, Moderate, and Severe.

```
PHYSICAL CONDITION TRACK
□ Minor (-1d6)           _______________
□ Moderate (5-6 only)    _______________
□ Severe (6 only)        _______________

MENTAL CONDITION TRACK
□ Minor (-1d6)           _______________
□ Moderate (5-6 only)    _______________
□ Severe (6 only)        _______________
```

**Standard (Gritty):** 1 Minor, 1 Moderate, 1 Severe per track (3 slots total)

### Stress Track: The Buffer

Before you take a Condition, damage fills your **Stress Track** first.

```
STRESS TRACK (shared for Physical and Mental)
□ □ □  (3 points)
```

**How Stress Works:**

1. When you take damage, mark Stress points first
2. When all 3 Stress boxes are filled, the **next damage** gives you a Condition
3. The **type of that final damage** determines the Condition type (Physical or Mental)
4. After taking a Condition, **reset the Stress Track** to empty

**Example:**
- You take 2 Physical damage → Mark 2 Stress (1 box left)
- You take 1 Mental damage → Fill Stress Track (3/3)
- You take Physical damage → Take a Physical Condition, reset Stress to 0/3

**Stress is a buffer.** It absorbs minor hits before you take lasting harm.

**Excess Damage Is Ignored:** If damage exceeds your remaining Stress, the excess is lost.
- You have 1 Stress remaining, take 3 damage
- Fill Stress Track (uses 1 of the 3 damage)
- Take a Condition (severity based on the attack, NOT overflow amount)
- Reset Stress to 0
- The remaining 2 damage is ignored

**One hit = one Condition maximum.** This keeps combat simpler and less lethal.

### How Condition Tracks Work

**Taking a Condition:**

1. Fill Stress Track (3 points)
2. Next damage determines Type (Physical or Mental - whatever the damage type was)
3. Determine Severity (Minor, Moderate, or Severe based on attack)
4. Mark a Slot (check box and name the Condition)
5. Apply Penalty (see Condition Severity below)
6. Reset Stress Track to 0/3

### Condition Severity

| Severity | Effect | Success Rate |
|----------|--------|--------------|
| **Minor** | -1d6 to relevant rolls | Reduces pool |
| **Moderate** | 5-6 only = success for relevant rolls | 33.3% per die |
| **Severe** | 6 only = success for relevant rolls | 16.7% per die |

**Example:** Slashed by sword. Your Stress Track is full (3/3). GM says "That's a Moderate Physical hit."

You mark Moderate Physical slot and write: **"Deep gash in shoulder"**. Reset Stress Track to 0/3.

From now on, when that Condition applies, only 5s and 6s count as successes.

### Naming Your Conditions

When you mark a Condition, **you name it**. Mechanical tier stays same, narrative flavor is yours.

**Physical Examples:**
- Minor: "Bruised ribs," "Sprained ankle," "Exhausted"
- Moderate: "Broken arm," "Concussed," "Deep wound"
- Severe: "Bleeding out," "Shattered leg," "Critical burns"

**Mental Examples:**
- Minor: "Rattled," "Distracted," "Frustrated"
- Moderate: "Terrified," "Paranoid," "Can't focus"
- Severe: "Broken will," "Traumatized," "Losing grip on reality"

**Why Name Conditions:**
- Memorable ("Broken ribs" sticks better than "Moderate Physical #2")
- Guides recovery (suggests how it heals)
- Narrative weight ("Bleeding out" feels urgent)

### When Conditions Apply

**Physical Conditions:**
- Typically affect Might and Agility rolls
- Can affect all rolls when severe enough ("Bleeding out" affects everything)
- GM discretion on when they realistically hinder

**Mental Conditions:**
- Typically affect Intellect and Persona rolls
- Examples: "Rattled" makes it hard to concentrate or stay calm
- Can affect physical rolls in some cases ("Panicked" makes hands shake)

### Being Taken Out

**When One Track Fills:**
All slots marked = **vulnerable** in that area. Can still act, but:
- Physical Track Full: Next Physical consequence takes you out (unconscious, dying, captured)
- Mental Track Full: Next Mental consequence takes you out (catatonic, fleeing, broken)

**Taking Consequences with Full Tracks:**

### Conditions Don't Stack
1
**Only the highest relevant Condition applies to a roll.**

If you have multiple Conditions that would affect the same action, use only the one with the **worst** penalty.

**Severity Hierarchy:** Severe (6 only) > Moderate (5-6 only) > Minor (-1d6)

**Example 1:** You have "Slashed arm" (Minor, -1d6) and "Broken leg" (Moderate, 5-6 only).

You're trying to run away (Agility). Both are Physical Conditions that could apply, but only the **worst** applies: "Broken leg" (5-6 only threshold).

**Example 2:** You have "Broken ribs" (Moderate, 5-6 only) and "Rattled" (Minor, -1d6).

You're climbing a wall (Agility). The Physical Condition applies (5-6 only). The Mental Condition doesn't affect this physical task, so it's ignored.

**Example 3:** You have "Broken ribs" (Moderate, 5-6 only) and "Terrified" (Moderate, 5-6 only).

You're trying to convince someone while injured and scared (Persona). Both could apply (physical pain + mental state affect your composure). They're the same severity, so just use one: 5-6 only threshold.

**Exception:** If Conditions affect completely different aspects of the roll, the GM might rule both apply. But this should be rare.

### Recovery

Conditions don't heal automatically.

**Physical Recovery:**
- **Short Rest (10 min):** May clear Minor Physical (GM discretion)
- **Medical Care:** Successful Intellect roll (Diff 2-4) can clear/downgrade Conditions
- **Full Rest (8 hours):** Clears one Physical Condition
- **Extended Downtime (days/weeks):** Clears all but Severe

**Mental Recovery:**
- **Short Break:** May clear Minor Mental
- **Therapy/Support:** Social scenes, can downgrade Mental Conditions
- **Full Rest (8 hours):** Clears one Mental Condition
- **Time and Resolution:** Some require narrative resolution

### Death and Dying

**The Death Spiral:**
When all Physical slots marked, next Physical consequence takes you out.

**Taken Out doesn't always mean dead:**
- Unconscious
- Captured
- Fleeing in terror
- Dying (but can be saved)

**Actual Death:**
- Usually requires player consent OR clear narrative setup
- GMs should telegraph lethal threats
- Death should be rare, meaningful, dramatic - not random

**Alternatives to Death:**
- Accept permanent Burden to survive
- Use Narrative Injection to reframe outcome
- Surrender or retreat before death

---

## 10. Progression & Narrative Points

### Narrative Points (NP)

**NP** is the universal currency of Narrative Points. You earn it through exceptional play and can spend it on:
- **Character progression** (upgrading Anchors, removing Burdens)
- **Gambling for Focus recovery** (converting fresh NP to Focus during play)

**Note:** Stats cannot be increased with NP. They only increase through narrative milestones at GM discretion (see Section 2).

**NP is earned through narrative engagement**, not just mechanical success.

### Earning Narrative Points

You earn **1 NP** when you:
- Play a Burden in a way that creates compelling drama
- Use your Narrative Injection creatively and meaningfully
- Create a "holy shit" story moment
- Drive narrative forward through roleplay, tactics, storytelling
- Achieve Story Goal or personal character milestone
- Demonstrate exceptional play that enriches session
- GM's discretion

**Important:** NP awarded for **engaging with the system**, not just having Burdens or using mechanics. The goal of Narraject is to create good epic stories

### Who Can Award NP?

**Option 1: GM Awards (Simple)** - GM awards when sees great play

**Option 2: Group Recognition (Collaborative)** - Any player can nominate another

### NP Distribution Guidelines

**Model 1: Capped Per Player (Recommended)**
- Each player can earn 1 NP. Only after everyone has gotten 1, players can get 2nd and so on.
- If all earn at least 1 NP, everyone gets bonus +1 NP
- This makes constant progression between players and reinforces team collaboration to progress.

**Example Session (Model 1):**

Party has 4 players: Alice, Bob, Charlie, Dana

1. **Alice** plays her Burden "Overconfident" and charges into danger, creating drama → Earns 1 NP
2. **Charlie** uses Narrative Injection creatively to save the mission → Earns 1 NP
3. **Bob** has great roleplay moment with enemy NPC → Earns 1 NP
4. **Dana** hasn't earned NP yet, so the group can't award 2nd NP to anyone until Dana gets 1
5. **Dana** engages her Burden "Hunted by the Syndicate" creating story tension → Earns 1 NP
6. Now **everyone has 1 NP**, so bonus +1 NP to all!
7. **Final result:** Alice 2, Bob 2, Charlie 2, Dana 2 (everyone progresses together)

**What if Dana never earned NP?**
- Alice 1, Bob 1, Charlie 1, Dana 0
- No bonus +1 for anyone because not everyone got 1 NP
- This incentivizes helping Dana get involved and earn her NP

**Model 2: Uncapped (Experienced Groups)**
- No limits on NP awards
- Risk of imbalance
- This can reward good players but leave behind unbalanced progression if there are less experienced players
- To allow for narrative progression and better team dynamics we recommend to allow players to share their NP's with others. This can be done via interaction with each other or helping each other. If they give narrative justification for the transfer of NP then it can be done.

**Example Session (Model 2):**

Party has 4 players: Alice, Bob, Charlie, Dana

1. **Alice** has 3 great moments → Earns 3 NP
2. **Bob** has 1 moment → Earns 1 NP
3. **Charlie** has 2 moments → Earns 2 NP
4. **Dana** is quiet, learning the game → Earns 0 NP
5. **Final result:** Alice 3, Bob 1, Charlie 2, Dana 0 (imbalanced progression)

**With NP Sharing:**
- Alice gives 1 NP to Dana: "I teach you combat techniques during downtime"
- Bob gives 1 NP to Dana: "I help you study the arcane texts we found"
- **Final result:** Alice 2, Bob 0, Charlie 2, Dana 2 (more balanced through mentorship)

**For new groups:** Start with Model 1.

### Spending Narrative Points

NP can be spent **between sessions**, during **in-game downtime**, or **during play** (for Focus).

**NP Uses:**

| Use | NP Cost | When |
|-----|---------|------|
| **Add/Upgrade Anchor** | 2 NP | Between sessions or downtime |
| **Reduce/Remove Burden** | 2 NP | Between sessions or downtime |
| **Gamble for Focus** | 1 NP (fresh) | During play |

**Note:** Stats (Mighty, Agility, Intellect, Persona) **cannot be increased with NP**. See "Increasing Stats: Narrative Milestones Only" in the Character Stats & Focus section.

### Progression: Anchors and Burdens

**Add New Anchor (2 NP):**
- Add a new Anchor to your character
- Must also add a new Burden (Rule of Balance)
- Requires narrative justification

**Remove Burden (2 NP):**
- Remove a Burden entirely
- Requires narrative resolution (how did you overcome it?)

**Note:** Anchors and Burdens are binary - they either apply or don't. There are no tiers to upgrade.

### Narrative Justification Required

Can't just spend NP and claim advancement. Must narrate how character earned it.

**Examples:**

**Anchors:**
- "During downtime, I trained with the veteran soldier. Upgrading Combat Training Basic → Advanced."
- "I've been studying the ancient texts we found. Adding 'Ancient History' as Basic Anchor."
- "After months of practice, my swordsmanship has reached mastery. Upgrading Swordplay Advanced → Master."

**Burdens:**
- "After nearly dying in that fire, I've faced my fear. Removing 'Fear of Fire' Burden."
- "I've reconciled with my brother. Removing 'Estranged Family' Burden."
- "Therapy and time have helped me process the trauma. Removing 'Traumatized' Burden."

**Note:** Burdens are binary - they either apply or they don't. Spend NP to remove them entirely through narrative development.

### Milestone Advancement (Optional)

GMs can grant **milestone advancements** independent of NP:
- Completing major story arcs
- Defeating significant threats
- Achieving personal character goals

**Milestone rewards:**
- Free Anchor upgrade (no NP cost)
- Bonus NP (beyond session cap)
- Unlocking unique abilities
- Narrative advancements (reputation, titles, resources)

---

## 11. Power Levels & Point Buy

### Understanding Character Levels

**Character Level is a reference point for power level, not a literal number on your sheet.**

There is no "level up" system. Characters progress by gaining Anchors, removing Burdens, and occasionally increasing Stats through narrative milestones.

**Character Level = Highest Stat Rating divided by 2 (approximately)**

A character's level roughly equals their highest stat divided by 2. This helps GMs balance challenges:

- **Level 3 character** has highest stat ~6-7 (3-3.5 Successes statistically from base dice)
- With Anchors, gear, and Aspects, they typically roll 9-11 dice in their specialty
- Tasks at their level (Difficulty 3) should be fairly easy
- Tasks 1 level below (Difficulty 2) should be almost automatic
- Tasks 1 level above (Difficulty 4) are harder
- Tasks 2+ levels above (Difficulty 5+) are very difficult

### Power Levels Table

| Level  | Highest Stat | Total Points | Example Distribution     | Expected Anchors | Expected Dice | Can Handle | Campaign Use                     |
| ------ | ------------ | ------------ | ------------------------ | ---------------- | ------------- | ---------- | -------------------------------- |
| **1**  | 2-3          | 5-6          | (3,1,1,1) or (2,2,1,1)   | 2-3              | 5-7d6         | Diff 1-2   | Street-level, rookies, civilians |
| **2**  | 4-5          | 8-10         | (5,2,1,1) or (4,3,1,1)   | 3-4              | 7-9d6         | Diff 2-3   | Standard starting characters     |
| **3**  | 6-7          | 12-14        | (7,3,2,1) or (6,4,2,1)   | 4-5              | 9-11d6        | Diff 3-4   | Experienced operatives           |
| **4**  | 8-9          | 16-18        | (9,5,2,1) or (8,6,2,1)   | 5-6              | 11-13d6       | Diff 4-5   | Elite professionals              |
| **5**  | 10-11        | 20-22        | (11,6,3,1) or (10,7,3,1) | 6-7              | 13-15d6       | Diff 5-6   | Masters, legendary NPCs          |
| **6+** | 12+          | 24+          | (13,8,4,1) or higher     | 7+               | 15+d6         | Diff 6+    | Heroes of legend, demigods       |

**Note:** Anchors no longer add dice - they shift success threshold to 3-4-5-6 (66.7% per die). "Expected Dice" is pool size from Stats + Gear + Aspects.

**"Expected Dice in Specialty"** assumes: Base Rating + Gear (+1d6 to +2d6) + Aspect (+1d6)

**Success rates:**
- Without Anchor: 50% per die (4-5-6 = success)
- With Anchor: 66.7% per die (3-4-5-6 = success)
- With Burden: 33.3% per die (5-6 only = success)

### Stat Distribution Rules

**1. Every stat must be at least 1** (no 0 stats allowed)

**2. Distribute stat points however you want**

There are no other restrictions on stat distribution. You can specialize heavily or spread points evenly.

Examples:
- Specialist: (6,2,1,1) - Master of one area, weak elsewhere
- Balanced: (3,3,2,2) - Competent in multiple areas
- Two-stat: (4,4,1,1) - Good at two things, weak at others

**Trade-offs:**
- **Specialists** excel in their area but must narrate all actions through their specialty
- **Generalists** have more options but are never exceptional
- **Your choice** - both are valid playstyles

### Effective Character Level: Gear and Aspects Matter

**Important:** A character's effective level can be higher or lower than their base stats suggest, depending on gear and Aspects.

**Example:**
- Character has Intellect 4 (Level 2 character, ~2 Successes base)
- Has special robes that grant +3d6 to all Intellect rolls
- Effectively rolls 7d6 for Intellect (~3.5 Successes)
- **This character is effectively Level 3 for Intellect tasks**

**What this means:**
- Character level is fluid based on gear, Anchors, and Aspects
- A Level 2 character with great gear can perform at Level 3
- A Level 3 character without gear/Anchors might perform at Level 2
- GMs should consider total dice pools when balancing, not just base stats

**Balancing Considerations:**
- If a character consistently rolls +5d6 more than their base stat, treat them as ~1-2 levels higher for challenge balancing
- Powerful gear/Aspects can elevate a character's effective level significantly
- This is intentional and OK! It just means their "level" shifts with their equipment
- Losing that gear means losing that effective level

### What Character Level Tells You

**Being Level 3 means:**
- Highest stat is around 6-7
- With gear/Anchors, typically rolls 10-12 dice in specialty
- Expected Successes in specialty: 5-6 Successes
- Difficulty 3 tasks should be fairly easy (~80%+ success)
- Difficulty 1-2 tasks should almost always succeed (95%+)
- Difficulty 4-5 tasks are harder (~60-70% success)
- Difficulty 6+ tasks are challenging (~40-50% success, may need Focus)

**GM Guidance:**
- Use character level to set baseline difficulty
- Add +1-2 Difficulty if they have powerful gear/Aspects
- Subtract 1-2 Difficulty if they lack gear/Anchors
- Character level is a guideline, not a hard rule
- Remember: 50% success rate per die (4-5-6 counts as Success)

---

## 12. Pacing & Session Structure

### Scenes vs. Downtime

Narraject alternates between **Scenes** (action, risk, rolls) and **Downtime** (recovery, planning, roleplay).

**A Scene** is a discrete unit of action with clear stakes.

**When to start a Scene:**
- Something is happening
- There's conflict or risk
- Players want to act

**When to end a Scene:**
- Immediate conflict resolved
- Stakes have changed
- Table needs a break

**Downtime** is space between Scenes for:
- Remove Conditions (requires rest or medical care)
- Plan next moves
- Roleplay character moments

### Scene Structure

1. GM sets the scene (what's happening? what's at stake?)
2. Players declare actions (what are you trying to do?)
3. Roll dice when it matters (build pool, roll, count Successes)
4. GM narrates outcome (success, failure, or in between)
5. Repeat or transition to Downtime


---

## 13. GM Principles

### When to Roll

**Roll when:**
- Outcome is uncertain
- Failure has consequences
- Success isn't trivial

**Don't roll when:**
- Task is routine
- No time pressure or opposition
- Failure would just mean "roll again"

**Golden Rule:** If failure wouldn't be interesting, don't call for roll. Just say yes.

### Setting Difficulty

GM determines how many Successes needed.

Use the Difficulty Scale (see Section 1) to match task ambition to Successes required.

Can state exact number ("That's 4 Successes") or describe ("That's very hard").

### The Golden Rule: Success = Intent

**If you succeed on roll, your Intent happens. Period.**

When player declares intent, set Difficulty that matches ambition.

**Don't say:** "You can't kill a dragon with a fork"

**Do say:** "That's Legendary - 10 Successes. If you succeed, fork pierces its eye and kills it"

Player then decides: try for 10 Successes, or aim for something achievable?

### Adjudicating Actions

1. Listen to the intent (what does player want?)
2. Determine the stat (which stat applies to approach?)
3. Set the difficulty (how ambitious is intent?)
4. Let them roll (don't gatekeep - let dice decide)
5. Narrate outcome (success means intent happens, failure means it doesn't)

### Improvisation

Narraject designed for improvisation. Don't need to prep everything.

**Single-number NPCs:** Level determines everything

**Yes, and / Yes, but:** Build on player ideas

**Trust the table:** Players help create story

### Your Job as GM

Trust the system. Trust the table. Have fun.

### Using Cards (Optional Tool)

**Cards are an optional organizational tool** to help track Aspects and gear during play. They are not required, but many groups find them helpful.

**What to write on cards:**
- **Scene Aspects** - Environmental features, situational elements
- **Character Aspects** - Personal traits, conditions, temporary effects
- **Gear** - Especially recurring equipment like armor, weapons, or important items
- **GM Aspects** - Threats, environmental hazards, plot elements

**How to use cards:**

1. **Write the Aspect or gear name on the card** (front side)
2. **Add mechanical effect** (e.g., "+2d6 to Stealth", "Cover: +1d6 to Defense")
3. **When using it in play, place the card on the table** - This makes it clear to everyone what's affecting the scene
4. **GM can play cards too** - Place threat cards, environmental aspects, or complications on the table
5. **Remove cards when no longer relevant** - When the Aspect ends or gear is no longer in play

**Why use cards?**

- **Visual organization** - Everyone can see what's affecting the scene at a glance
- **Reminder system** - Don't forget about that armor bonus or environmental aspect
- **Clear communication** - When a card is on the table, it's "active" and can affect rolls
- **Similar to Fate's aspect cards** - If you're familiar with Fate, this will feel natural

**Examples:**
- Player places "Combat Armor" card on table during firefight (+2d6 to Defense)
- GM places "Heavy Rain" card on table (all Perception rolls at -1d6)
- Player places "Injured Leg" Burden card to remind everyone it's affecting their Movement
- GM places "Sniper on Rooftop" threat card to track the active danger

**This is completely optional.** Some groups prefer tracking everything mentally or with notes. Use cards if they help your table stay organized.

---

## 14. Frameworks & Paths (Setting-Specific Content)

### What Are Frameworks?

**Frameworks** are setting-specific supplements that add flavor, rules, and options to Narraject's core system.

Think of them as plug-and-play expansions:
- "Narraject with the Fantasy Framework"
- "Narraject with the Sci-Fi Framework"
- "Narraject with the Terra World Framework"
- "Narraject with the Horror Framework"
- "Narraject with the Alien Framework"
- "Narraject with the Zombie Apocalypse Framework"

Each Framework is tailored to its genre and can include:
- **Setting lore and worldbuilding**
- **New gear, equipment, or technology**
- **Special rules or subsystems** (magic, cybernetics, psychic powers)
- **Character progression options** (often called Paths)
- **Setting-appropriate terminology and flavor**

**Frameworks are optional.** The core rules work for any setting. Frameworks add genre-specific polish and mechanics.

### What Are Paths?

**Paths** are character progression options within a Framework. They represent specializations, vocations, classes, or character archetypes specific to that setting.

**Examples:**
- **Fantasy Framework:** Path of the Berserker, Path of the Mage, Path of the Rogue
- **Sci-Fi Framework:** Path of the Sniper, Path of the Pilot, Path of the Engineer
- **Horror Framework:** Path of the Investigator, Path of the Occultist, Path of the Survivor
- **Psychic Framework:** Path of the Mentalist, Path of the Empath, Path of the Telekinetic

**What Paths typically provide:**
- Specific Anchors or Anchor progressions unique to that Path
- Special abilities or mechanics (spells, tech, powers)
- Narrative stat increase milestones tied to Path advancement
- Setting-appropriate gear or starting resources
- Story hooks and setting connections

**Paths are the default structure**, but not all Frameworks use them. Some Frameworks might use different systems or terminology entirely.

### Framework Flexibility

**Important:** Each Framework defines its own rules and structure.

- Some Frameworks use Paths extensively
- Some might rename them (Vocations, Callings, Specializations, Roles, Classes...)
- Some might not have character options at all (just setting rules and gear)
- Some might have completely different progression systems

**The Framework decides how it works.**

### Creating Your Own Framework

If you're creating a Framework for your own setting:

1. **Choose your structure** - Will you use Paths? Something else? Nothing at all?
2. **Use "Paths" terminology if possible** - It's the suggested default and helps consistency
3. **Define what your options provide** - Anchors? Special abilities? Stat progressions?
4. **Add setting flavor** - Terminology, lore, and genre-specific feel

**We suggest using "Paths" terminology** when designing character progression options for your Framework. This helps players recognize the structure across different Frameworks, but you're free to rename them to fit your setting.

### Where to Find Frameworks

**Core rulebook includes several Frameworks:**

Each Framework in this book provides everything needed to play in that setting:
- Complete setting information and lore
- Character options (Paths or equivalent)
- Special rules and subsystems
- Setting-specific gear and equipment
- GM guidance for that genre

**Future expansion Frameworks:**
- Additional settings and genres as separate supplements
- Community-created Frameworks
- Third-party Framework support

**Included Frameworks are complete and ready to play.** Choose the one that fits your game, or use the core rules without any Framework for maximum flexibility.

### Using Frameworks with Core Rules

**Frameworks extend, not replace:**
- Core rules (stats, Focus, Anchors, Burdens, etc.) remain unchanged
- Frameworks add on top of the core system
- You can use multiple Frameworks together if they're compatible
- GMs decide what fits their game

**Example in play:**
- Core rules: Stats, Focus, Anchors, Burdens, Narrative Injection
- Fantasy Framework adds: Magic system, fantasy Paths, setting-specific gear
- Players still use the same core mechanics, now with fantasy flavor

---

## Quick Reference Tables

### Success Thresholds
| Condition | Success On | Chance Per Die |
|-----------|------------|----------------|
| **Normal** | 4, 5, 6 | 50% |
| **With Anchor** | 3, 4, 5, 6 | 66.7% |
| **With Burden** | 5, 6 only | 33.3% |
| **Moderate Condition** | 5, 6 only | 33.3% |
| **Severe Condition** | 6 only | 16.7% |

Roll dice, count Successes based on threshold, compare to Difficulty.

**Note:** Minor Conditions remove -1d6 instead of shifting threshold.

### Difficulty Scale
| Successes | Difficulty  | Example Task |
|-----------|-------------|--------------|
| 1 | Easy | Climb ladder, spot obvious clue |
| 2 | Moderate | Pick simple lock, persuade neutral person |
| 3 | Challenging | Hit moving target, hack secured system |
| 4 | Hard | Scale sheer wall in rain, convince hostile NPC |
| 5-6 | Very Hard | Near-impossible shot, sway hostile crowd |
| 7-8 | Heroic | Feats that define legends |
| 9-10 | Legendary | Once-in-a-lifetime achievements |
| 10+ | Mythic | Feats of gods |

### The Four Stats
| Stat          | Domain                                                  |
| ------------- | ------------------------------------------------------- |
| **Might**     | Physical power, endurance, melee combat, resisting harm |
| **Agility**   | Speed, reflexes, coordination, stealth, ranged combat   |
| **Intellect** | Knowledge, perception, reasoning, technical skills      |
| **Persona**   | Social influence, willpower, presence, deception        |

### Character Levels
| Level | Highest Stat | Total Points | Expected Dice in Specialty | Can Handle Easily |
|-------|--------------|--------------|---------------------------|-------------------|
| 1 | 2-3 | 5-6 | 6-7d6 | Difficulty 1-2 |
| 2 | 4-5 | 8-10 | 8-10d6 | Difficulty 2-3 |
| 3 | 6-7 | 12-14 | 10-12d6 | Difficulty 3-4 |
| 4 | 8-9 | 16-18 | 12-14d6 | Difficulty 4-5 |
| 5 | 10-11 | 20-22 | 14-16d6 | Difficulty 5-6 |

**Note:** Character Level ≈ Highest Stat ÷ 2

### Focus
- **Capacity:** 0-6 points (shared across all stats)
- **Spend:** After rolling, add 1 Success per Focus spent
- **Limit:** Cannot spend more than your Stat Rating for that roll
- **Recovery:** Long Rest (restores to 3, not max) or Gamble fresh NP (roll 1d6, success if > current Focus)

### Anchors (Skills & Competencies)
**Note:** Anchors no longer add dice - they shift your success threshold to 3-4-5-6 (66.7% per die instead of 50%).

| Action | Cost |
|--------|------|
| Add new Anchor | 2 NP (must also add a Burden per Rule of Balance) |

### Burdens (Flaws & Vulnerabilities)
**Note:** Burdens no longer have severity tiers - they shift your success threshold to 5-6 only (33.3% per die instead of 50%).

| Action | Cost |
|--------|------|
| Remove a Burden | 2 NP (requires narrative justification) |

### Condition Tracks
**Two Core Tracks:** Physical, Mental (Social is optional)

**Slots:** Minor (-1d6), Moderate (5-6 only), Severe (6 only)

**Stress Track:** 3 points buffer before taking Conditions. When full, next damage triggers a Condition (type = damage type that broke the buffer). Resets after taking Condition.

**Only highest relevant Condition applies** (they don't stack)

### Damage Formula
**Final Damage = NPC Damage - Player's Successes** (minimum 0)

NPCs have Attack (difficulty to defend) and Damage (how much they deal). Player successes always reduce damage.

**Example:** NPC (Attack 4, Damage 4) attacks, you roll defense and get 2 Successes → Take 4 - 2 = 2 Stress

### Gear
- **Situational:** GM decides bonus per scenario
- **Typical:** +1d6 when relevant
- **Superior/Special:** +2d6 or +3d6 if narratively significant

**Armor:**
- **Light:** +1d6 vs Agility-based attacks, no stealth penalty
- **Heavy:** +1d6 vs Might-based attacks, -1d6 to Agility/stealth

### Narrative Points (NP)
**Earning:** 1 NP for exceptional play (Burdens creating drama, creative Narrative Injection, story moments)

**Spending:**
- Add/Upgrade Anchor: 2 NP
- Reduce/Remove Burden: 2 NP
- Gamble for Focus: 1 NP (fresh only, roll 1d6)

**Stats:** Cannot be bought with NP. Only increase through narrative milestones at GM discretion.

### NPCs
- **Don't roll dice** - Players always roll
- **Level = Difficulty** for rolls against them
- **Can have specific action levels** (Attack 6, Defense 2, etc.)
- **Simple tracking:** 1-3 hits to take down (minions to tough enemies)

### Stat Distribution Rules
1. **Every stat must be at least 1**
2. **Distribute points however you want** (no other restrictions)
3. Examples: (6,2,1,1) specialist, (3,3,2,2) generalist, (4,4,1,1) two-stat

### Quick Dice Math
- **~2 dice per Success** (50% success rate)
- Level 3 character with gear/Anchors: ~10-12 dice = ~5-6 Successes
- Focus adds Successes after rolling (max = your Rating in that stat)

---

## Glossary

**Anchors:** Character competencies (skills, backgrounds, training, connections). When relevant, shift success threshold to 3-4-5-6 (66.7% per die).

**Aspects:** Temporary beneficial conditions created through play (+1d6 typically). Examples: "High Ground," "Behind Cover," "Studied Their Moves."

**Burdens:** Character vulnerabilities (fears, enemies, obligations, flaws). When relevant, shift success threshold to 5-6 only (33.3% per die).

**Condition Tracks:** Physical, Mental, and (optionally) Social tracks for harm. Slots: Minor (-1d6), Moderate (5-6 only), Severe (6 only).

**Focus:** Shared resource pool (0-6 points) representing concentration and determination. Spend after rolling to add Successes (1 Focus = +1 Success, max = Stat Rating).

**Narrative Injection:** Once-per-session ability to inject story facts.

**Narrative Points (NP):** Progression currency earned through exceptional play, spent between sessions or gambled for Focus recovery.

**Rating:** Your base capability in a stat. Determines minimum dice (Rating = Xd6).

**Successes:** A d6 showing 4, 5, or 6 counts as 1 Success (50% chance per die).

**Stress Track:** 3-point buffer that fills before taking Conditions. Resets when Condition is taken.

---

## Design Philosophy

### Core Pillars

**1. Success = Intent Happens (Period)**
- No "you hit but low damage"
- If you succeed on the roll, your stated intent becomes reality
- Ambition determines difficulty, not possibility

**2. Ambition Sets Difficulty**
- Want to do something small? Easy difficulty
- Want to do something epic? High difficulty
- Players choose their own risk level by declaring intent

**3. Dice Pools Over Math**
- Add dice together, roll them, count Successes
- No multiplication, subtraction of modifiers, or complex math
- 50% success rate per die (4-5-6 counts as Success)

**4. Separate Health from Action**
- No death spirals from damage
- Conditions affect specific actions, not your entire dice pool
- Focus separate from Conditions - getting hurt doesn't drain your concentration pool
- Only highest relevant Condition applies (no stacking)

**5. Failure Still Moves Story Forward**
- Even failures create impact and progress
- Wounded enemies, planted seeds, learned information
- GM makes every roll matter

**6. Focus Feels Good**
- Spend Focus AFTER seeing the roll result
- Never wasted - you know exactly what you need
- Capped by your Rating - specialists shine in their areas

**7. Narrative First**
- Story authority shared between players and GM
- Narrative Injection gives players once-per-session co-authorship
- Burdens create personal stakes and earn progression

**8. Stats Through Story**
- Can't buy stat increases with currency
- Stats only increase through narrative milestones
- Keeps progression focused on skills (Anchors) and character development

**9. Modular & Flexible**
- Core game is setting-agnostic
- Future expansions add pluggable modules (magic systems, cybernetics, setting-specific roles)
- Easy to adapt to any genre

**10. GM Prep is Easy**
- Single-number NPCs (just assign a Level)
- Theater of mind combat with narrative zones
- Improvisational tools built into the system

---

## Glossary (Alphabetical)

**Anchors:** Character competencies - skills, backgrounds, training, connections, and experiences. When relevant, shift success threshold to 3-4-5-6 (66.7% per die instead of 50%). Cost 2 NP to add new Anchor (must also add Burden per Rule of Balance).

**Aspects:** Temporary beneficial conditions created through play that add dice to rolls (+1d6 typically). Examples: "High Ground," "Behind Cover," "Studied Their Moves." Last until situation changes or scene ends.

**Burdens:** Character vulnerabilities - fears, enemies, obligations, flaws, and narrative hooks. When relevant, shift success threshold to 5-6 only (33.3% per die instead of 50%). Cost 2 NP to remove (requires narrative justification).

**Character Level:** Reference point for power level, not a literal stat. Approximately equals Highest Stat ÷ 2. Used by GMs to balance challenges.

**Condition Tracks:** Harm tracking system with separate tracks for Physical, Mental, and (optionally) Social damage. Each track has three slots: Minor (-1d6), Moderate (5-6 only), Severe (6 only). Only worst relevant Condition applies to any given roll.

**Difficulty:** Target number of Successes needed to accomplish a task. Set by GM based on ambition of the declared intent. Scale: 1 (Easy) to 10+ (Mythic).

**Focus:** Shared resource pool (0-6 points) representing concentration, determination, and will to push beyond limits. Spend AFTER rolling to add Successes (1 Focus = +1 Success). Limited by your Stat Rating for that roll. Recovered through Long Rest or gambling fresh NP.

**Narrative Injection:** Once-per-session player ability to inject a story fact, context, or element into the narrative. Can be used before or after rolls, or between scenes.

**Narrative Points (NP):** Universal progression currency earned through exceptional play (engaging Burdens dramatically, creative story moments, great roleplay). Spent between sessions to improve Anchors/Burdens, or gambled during play for Focus recovery.

**NPCs:** Non-player characters. Don't roll dice - players always roll against their Level. Can have simple single Level or specific action levels (Attack 6, Defense 2, etc.).

**Rating:** Your base capability in a stat (Might, Agility, Intellect, Persona). Determines base dice pool (Rating = Xd6). Also caps how much Focus you can spend on that stat's rolls.

**Stats:** The four core attributes - Might, Agility, Intellect, Persona. Cannot be increased with NP; only through narrative milestones at GM discretion.

**Stress Track:** 3-point buffer that fills before taking Conditions. When full, next damage triggers a Condition (type determined by the damage type that broke the buffer). Resets after Condition is taken.

**Successes:** A d6 showing 4, 5, or 6 counts as 1 Success (50% chance per die). Compare total Successes to Difficulty to determine outcome.

---

## Version Notes

This rules summary is a working document for playtesting and rules iteration. It consolidates all core mechanics into one reference file.

**Not included in this summary:**
- Specific setting content (future expansions)
- Extended examples of play
- Detailed GM toolkit (NPCs, threats, toolbox modules)
- Advanced optional rules

For those elements, refer to the full manuscript in `/01_manuscript/`.

**Purpose of this file:**
- Central reference for all core rules
- Easy to modify and playtest changes
- Can be updated independently of main rulebook
- Once finalized, changes can be implemented back into manuscript

---

**End of Rules Summary**
