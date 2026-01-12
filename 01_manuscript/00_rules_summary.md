# Narraject: Complete Rules Summary

_A condensed reference of all core mechanics. Edit this file to test rule changes before updating the full manuscript._

---

## Core Philosophy

**Success = Intent Happens. Period.**

If the dice say success, the reality you described becomes true. No "you hit but didn't do enough damage." No "you persuaded but they still won't do it."

**Roll only when:**
- The outcome is uncertain
- Failure has consequences
- Success isn't trivial

---

## The Core Roll

### The Formula

**Building Your Dice Pool:**
```
DICE POOL = Rating + Focus + Assets + Aspects
```

**Calculating Total Successes:**
```
TOTAL SUCCESSES = (Dice Successes from Pool) + Anchors - Burdens
```

**Important:**
- Only **ONE Anchor** applies per roll (choose most relevant) = +1, +2, or +3 successes
- Only **ONE Burden** applies per roll (GM chooses if applicable) = -1, -2, or -3 successes

### The Process
1. **Declare Intent:** "I want to [Goal] by [Approach]"
2. **GM Sets Difficulty:** Number of successes needed (Difficulty)
3. **Choose Anchor:** Select ONE most relevant Anchor (if any apply)
4. **GM Chooses Burden:** GM selects ONE applicable Burden (if any apply)
5. **Build Dice Pool:** Stat Rating + Focus + Assets + Aspects (d6s only)
6. **Roll:** Count 5-6 as successes from your dice pool
7. **Add Modifiers:** Dice successes + Anchor bonus - Burden penalty
8. **Compare to Difficulty:** Success if total successes ≥ Difficulty, fail otherwise

### Success Counting
- **d6:** 5-6 = 1 success
- Count dice successes, then add/subtract modifiers
- **Final Total = Dice Successes + Anchor - Burden**

### Example Roll

**Situation:** Intimidating a guard (Difficulty 3)

**Character has:**
- Persona Rating: 3
- Focus: 18/20 (shared pool, Persona Focus Cap: 5)
- Anchor: "Fearsome Reputation" (Moderate, +2 successes)
- Burden: "Obvious Lie" (Minor, -1 success) - applies because bluffing

**Building the Pool:**
1. Rating: 3d6 (Persona)
2. Focus: Spend 2 = +2d6
3. Assets: None applicable
4. Aspects: None
5. **Dice Pool: 5d6**

**Choosing Modifiers:**
- Anchor: "Fearsome Reputation" (Moderate) = +2 successes
- Burden: "Obvious Lie" (Minor) = -1 success

**Rolling:**
- Roll 5d6: [6, 5, 3, 2, 1]
- Dice successes: 2 (the 6 and 5)

**Calculating Total:**
- Dice: 2 successes
- +Anchor: +2 successes
- -Burden: -1 success
- **Total: 3 successes**

**Result:** Meets Difficulty 3 exactly → SUCCESS! The guard is intimidated despite the obvious lie.

---

## Difficulty Levels

| Successes Needed | Dice to guarantee success | Difficulty  | Example                                     |
| ---------------- | ------------------------- | ----------- | ------------------------------------------- |
| 0                |                           | Trivial     | No roll needed                              |
| 1                | 3                         | Easy        | Climb a ladder, spot obvious clue           |
| 2                | 6                         | Moderate    | Pick simple lock, persuade neutral stranger |
| 3                | 9                         | Challenging | Hit moving target, hack secured system      |
| 4                | 12                        | Hard        | Scale sheer wall in rain, convince hostile  |
| 5-6              | 18                        | Very Hard   | Near-impossible shot, walk on fire          |
| 7-8              | 24                        | Heroic      | Feats that define legends                   |
| 9                | 27                        | Legendary   | Once-in-a-lifetime achievements             |
| 10+              | 30+                       | Mythic      | Feats of gods                               |
Character Tier represents what difficulty level should be easy for them. for example a character that throughs regularly 6 die on his main stats and actions is a tier 2 character (doesn't matter where those bonuses come from)
that means that assets can make character go up the tiers, losing assets can make characters go down tiers. 
character tier doesn't have any real implications, its just for scaling references and balance references for GM's to develop encounters or conflicts

---

## Stats: Rating and Focus

Every character has **4 Stats:** Might, Agility, Intellect, Persona

Each stat has a **Rating** (base dice). All stats share one **Focus pool** (resource).

### 1. Rating (Base Dice)
- Your baseline competence in that stat
- **Always roll this many d6** when using the stat
- Range: 1-5 (standard), up to 10 (legendary campaigns)

### 2. Focus (Shared Resource Pool)
- **ONE total pool shared across all stats**
- Use it to add dice to any roll (any stat)
- Track as "Current / Maximum" (e.g., 18/30)

**Starting Focus:** Total stat points × 2

**Example:** Character with Might 2, Agility 3, Intellect 2, Persona 3 = 10 total stat points = Starting Focus of 20

### 3. Focus Cap (Per-Stat Spending Limit)
- Maximum Focus you can spend on **one roll** with that stat
- **Formula:** Rating + 2
- Each stat has its own cap based on its Rating

**Focus Cap by Stat Rating:**

| Stat Rating | Focus Cap (Max per Roll) |
|-------------|--------------------------|
| 1           | 3                        |
| 2           | 4                        |
| 3           | 5                        |
| 4           | 6                        |
| 5           | 7                        |
| 6           | 8                        |
| 7           | 9                        |
| 8           | 10                       |
| 9           | 11                       |
| 10          | 12                       |

**Example:** You have Might 3, Agility 4, Intellect 2, Persona 2, and 18 Focus remaining.
- On a Might roll: Can spend up to 5 Focus (Might's cap)
- On an Agility roll: Can spend up to 6 Focus (Agility's cap)
- On an Intellect roll: Can spend up to 4 Focus (Intellect's cap)
- All spending depletes the same shared pool of 18 Focus

### Using Focus (Focusing)
- **"I'm focusing on this" = spending Focus to add dice**
- **1 Focus = +1d6 to your dice pool**
- Spend from your shared Focus pool
- Cannot exceed the Focus Cap for the stat you're using
- Deduct spent Focus from your total

**Example:** "I'm focusing everything on this shot" = spending 5 Focus on an Agility roll (if Agility 3 allows cap of 5)

### Recovery
- **Short Rest (10 minutes):** Recover 1d6 Focus
- **Long Rest (8 hours):** Recover all Focus to maximum

### Stat Domains

| Stat       | Domain                                                      |
|------------|-------------------------------------------------------------|
| **Might**     | Physical power, endurance, melee combat, resisting harm  |
| **Agility**   | Speed, reflexes, coordination, stealth, balance          |
| **Intellect** | Knowledge, perception, reasoning, technical skills       |
| **Persona**   | Social influence, willpower, presence, deception         |

**Important:** Your APPROACH determines which stat you use, not a fixed skill list.

---

## Anchors (Strengths)

**What:** Training, background, skills, expertise that add **guaranteed successes** to your total

**Mechanic:** Add successes (not dice) when relevant, based on impact level

### Impact Levels

| Impact       | Bonus         | What It Represents                          |
|--------------|---------------|---------------------------------------------|
| **Minor**    | +1 success    | Relevant background, training, or skill     |
| **Moderate** | +2 successes  | Specialized expertise or significant talent |
| **Major**    | +3 successes  | Exceptional mastery, world-class ability    |

### Anchor Rules
- ✅ **Only ONE Anchor applies per roll** (choose the most relevant)
- ✅ Anchors ONLY help, never hinder
- ✅ Can be Broad ("Combat") or Specific ("Expert Marksman")
- ✅ Must be narratively justified to apply

### Examples
- Street Fighter (Major, +3 successes)
- Lockpicking (Moderate, +2 successes)
- First Aid (Minor, +1 success)
- Corporate Insider (Moderate, +2 successes)
- Ancient Historian (Minor, +1 success)

---

## Burdens (Weaknesses)

**What:** Narrative complications, fears, physical limitations that remove **successes** from your total

**Mechanic:** Subtract successes (not dice) when they apply, based on impact level

### Impact Levels

| Impact       | Penalty       | What It Represents                     |
|--------------|---------------|----------------------------------------|
| **Minor**    | -1 success    | Minor complication or limitation       |
| **Moderate** | -2 successes  | Significant weakness or trauma         |
| **Major**    | -3 successes  | Severe limitation or debilitating flaw |

### Burden Rules
- ✅ **Only ONE Burden applies per roll** (GM chooses if applicable)
- ✅ Burdens ONLY hinder, never help
- ✅ When played well, earn Narrative Points

### The Rule of Balance
**You must have 1 Burden for every 1 Anchor you possess.**

If you have 4 Anchors, you must have 4 Burdens. Gaining a new Anchor requires gaining a new Burden.

### Burden Categories
1. **People You Care About** (threatenable NPCs)
2. **Phobias and Trauma** (fear of fire, heights, etc.)
3. **Mysteries** (unknown past, prophecy)
4. **Enemies and Rivals** (named antagonists)
5. **Obligations** (debts, oaths, codes)
6. **Failed Obligations** (broken promises)
7. **Crimes** (wanted, hunted)
8. **Discrimination** (prejudice faced)
9. **Possessions** (cursed item, addiction)
10. **Physical Limitations** (missing limb, chronic pain)
11. **Personality Flaws** (arrogance, recklessness)

### Examples
- Hot-Headed (Minor, -1 success)
- Fear of Fire (Moderate, -2 successes)
- Wanted by the Law (Major, -3 successes)
- Haunted by Failure (Moderate, -2 successes)

---

## Assets (Equipment)

**What:** Tools, weapons, armor, vehicles that add dice or provide special effects

**Mechanic:** Add d6 based on quality level

### Quality Levels

| Quality      | Bonus | What It Represents                     |
|--------------|-------|----------------------------------------|
| **Standard**   | +1d6  | Common tool that enables the action    |
| **Quality**    | +2d6  | Superior craftsmanship or technology   |
| **Masterwork** | +3d6  | Exceptional, rare, or master-crafted   |

### Asset Rules
- Multiple Assets can apply if narratively justified
- Some Assets hinder certain rolls (tags like "Heavy")
- Assets can break, be lost, or require upkeep

### Examples
- Lockpicks (Standard, +1d6)
- Quality Sniper Rifle (Quality, +2d6)
- Masterwork Sword (Masterwork, +3d6)
- Heavy Armor (Quality, +2d6 to defense BUT -1d6 to Agility rolls)

---

## Aspects (Narrative Elements)

**What:** Established facts in the fiction that can add dice

### Three Types

#### 1. Character Injections
Elements on your character sheet:
- Anchors (add dice)
- Burdens (remove dice)
- Assets (add dice)
- Conditions (remove dice - see Stress & Conditions)

#### 2. Scene Injections
Environmental factors created through actions:
- "High ground"
- "Smoke-filled room"
- "Cover from the barricade"
- "Tactical advantage"

**How they're created:** Players create them through successful actions or Narrative Injection

**Bonus:** +1d6 or +2d6 when GM judges significant advantage

#### 3. Story Injections
Ongoing narrative elements established through play:
- "The city is under martial law"
- "The curse weakens magic users"
- "The corporation controls all communication"

**Bonus:** Varies based on relevance (usually +1d6)

---

## Narrative Injection (Special Player Ability)

**What:** Once per session, inject a story fact without rolling or spending resources

**How It Works:**
1. Declare a fact about the world, scene, or story
2. GM can veto if unreasonable
3. If accepted, that fact is now true

**Examples:**
- "There's an herbalist shop nearby" (in a city)
- "I prepared an escape route before coming here"
- "The guard captain is an old friend from my military days"
- "I studied this type of lock before"

**Limits:**
- Can't directly solve the current problem
- Can't contradict established facts
- Can't negate another player's moment
- GM has final say on reasonableness

**Tracking:** Mark on character sheet when used (resets each session)

---

## Stress & Conditions (Damage System)

### Two-Layer System

**Layer 1: Stress** (buffer that absorbs hits)
**Layer 2: Conditions** (lasting wounds that impose penalties)

### Stress Tracks

**Every character has:**
- **Physical Stress:** 3 boxes (fixed)
- **Mental Stress:** 3 boxes (fixed)

**What Stress Represents:** Stamina, near-misses, glancing blows, ability to keep going

**Recovery:**
- Short Rest (10 min): All Stress boxes clear
- Long Rest (8 hours): Automatic full recovery

### Taking Damage

**Step 1:** Determine damage amount (GM or attack damage)

**Step 2:** Mark Stress boxes equal to damage
- Armor reduces damage (Light -1, Medium -2, Heavy -3)

**Step 3:** Check for Overflow
- If damage > remaining Stress = Take a Condition
- **Overflow amount determines severity:**
  - 1-2 overflow = Minor Condition (-1d6)
  - 3-4 overflow = Moderate Condition (-2d6)
  - 5+ overflow = Major Condition (-3d6)

**Step 4:** Reset Stress to 0 after taking Condition

### Conditions

**What:** Named, narrative wounds or trauma

**Slots:** Standard = 1 Minor / 1 Moderate / 1 Major per track

#### Condition Tracks

**Physical Conditions** (affect Might/Agility rolls typically):
- Minor: "Bruised ribs," "Winded," "Sprained ankle"
- Moderate: "Broken arm," "Deep wound," "Concussed"
- Major: "Bleeding out," "Shattered leg," "Critical burns"

**Mental Conditions** (affect Intellect/Persona rolls typically):
- Minor: "Rattled," "Distracted," "Frustrated"
- Moderate: "Terrified," "Paranoid," "Can't focus"
- Major: "Broken will," "Traumatized," "Losing grip"

**When Conditions Apply:**
- GM determines when relevant to the roll
- Multiple Conditions can stack on the same roll
- Player names the Condition when taken

**Player Choice:**
- Can shift Conditions between tracks with justification
- Can split overflow into multiple smaller Conditions
- Choose how to take damage narratively

**Recovery:**
- Short Rest: May clear Minor with GM approval
- Medical Care: Intellect roll (Difficulty 2-4) to clear/downgrade
- Long Rest: Clear one Condition
- Extended Downtime: Clear all but Major

### When All Tracks Are Full

If you overflow when tracks are full = **Taken Out**
- Unconscious
- Captured
- Fleeing
- Dying (but can be saved)

**Actual Death:** Requires player consent OR clear setup

### Power Level Variants

| Power Level | Stress      | Condition Slots     |
|-------------|-------------|---------------------|
| Gritty      | 3/3         | 1/1/1 per track     |
| Standard    | 3/3         | 1/1/1 per track     |
| Heroic      | 3/3         | 2/1/1 per track     |
| Epic        | 3/3         | 2/2/1 per track     |

---

## Combat & Conflicts

### Core Principle: Players Roll Everything

Enemies don't roll. Players roll to attack AND defend.

### Enemy Difficulty

Every enemy has a **Difficulty** rating for actions against them

- Attack enemy = Difficulty to hit
- Defend against enemy = Difficulty to avoid their attack
- Other contested actions = usually Difficulty

### Building Enemies

#### 1. Difficulty (Required)
Base difficulty for actions against them

**Guidelines:**
- Diff 1: Untrained civilians, basic threats
- Diff 2: Trained professionals
- Diff 3: Veteran specialists, dangerous
- Diff 4: Elite warriors, formidable
- Diff 5: Legendary fighters
- Diff 6+: World-class threats, bosses

#### 2. Stress Capacity (Required)
- Minions: 3 Physical, 3 Mental
- Standard: 3-6 Physical, 3-6 Mental
- Bosses: 6-9 Physical, 6-9 Mental

#### 3. Condition Slots (Required)
- Minions: 1 slot (any Condition = taken out)
- Standard: 2-3 slots
- Bosses: 4-6 slots

#### 4. Armor (Optional)
- Light: -1 Stress
- Medium: -2 Stress
- Heavy: -3 Stress

#### 5. Attack Damage (Required)
**Formula:** Difficulty + 1 to Difficulty + 2 Stress

| Enemy Difficulty | Typical Damage | Boss Damage |
|------------------|----------------|-------------|
| Diff 1           | 2-3 Stress     | 3-4 Stress  |
| Diff 2           | 3-4 Stress     | 4-5 Stress  |
| Diff 3           | 4-5 Stress     | 5-6 Stress  |
| Diff 4           | 5-6 Stress     | 6-7 Stress  |
| Diff 5           | 6-7 Stress     | 7-8 Stress  |
| Diff 6           | 7-8 Stress     | 8-9 Stress  |

#### 6. Special Modifiers (Optional)
Adjust Difficulty for specific situations

**Format:** Descriptor (modifier)

Examples:
- "Heavily Armored (Diff +1 vs Physical attacks)"
- "Slow (Diff -1 vs Agility actions)"
- "Pack Tactics (Diff +1 when allies present)"

### GM Combat Workflow

1. **Set the scene** - Describe environment, Scene Injections
2. **Players declare actions** - What + how
3. **Set difficulty** - Enemy Difficulty + modifiers
4. **Players roll** - Build pool, count successes
5. **Resolve** - Success = intent happens, failure = GM move
6. **Track damage** - Mark Stress, check overflow
7. **Repeat** until conflict resolved

### Encounter Balancing

**Match Enemy Difficulty to Party Power Level for balanced fights:**
- Easy: Diff = Power Level - 1
- Moderate: Diff = Power Level
- Hard: Diff = Power Level + 1
- Boss: Diff = Power Level + 2

**Example:** Power Level 3 party
- Easy: Diff 2 bandits
- Moderate: Diff 3 guards
- Hard: Diff 4 elite soldiers
- Boss: Diff 5 master assassin

---

## Progression (Narrative Points)

### Earning Narrative Points (NP)

**Award 1-2 NP per session** for:
- Good roleplay
- Playing Burdens honestly
- Advancing the story
- Clever problem-solving
- Group/GM recognition

**Maximum 5 NP cap** (forces spending)

### Spending NP (Between Sessions)

All spending requires narrative justification.

| Advancement                     | NP Cost | Notes                                 |
|---------------------------------|---------|---------------------------------------|
| Upgrade Anchor (Minor → Moderate) | 2 NP    | Justify training/experience           |
| Upgrade Anchor (Moderate → Major) | 3 NP    | Requires significant story moment     |
| Add New Minor Anchor            | 2 NP    | Explain how you learned this          |
| Add New Moderate Anchor         | 4 NP    | Justify starting at this level        |
| Reduce Burden (Major → Moderate) | 3 NP    | Requires narrative resolution         |
| Reduce Burden (Moderate → Minor) | 3 NP    | Requires narrative resolution         |
| Remove Minor Burden             | 3 NP    | Story must address this meaningfully  |
| Increase Stat Rating            | 3 NP    | Represents deep training, max 5       |

**Stat Increases:**
- Cost: 3 NP
- Effect: +1 Rating, increased Focus pool maximum (+2), increased Focus Cap for that stat (+1)
- Max Rating: 5 (standard campaigns)

**New Anchors:**
- Must add matching Burden (Rule of Balance)
- Must justify how you learned it

---

## The Economy (Narrative Points System)

### Core Concept

**Narrative Points (NP)** are the ONLY currency for progression.

**Not used for:**
- Tactical advantages during play
- Rerolls or dice bonuses
- "Buying" success

**Used for:**
- Character advancement (between sessions)
- Must have narrative justification

### Distribution Models

**Recommended: Capped Per Player**
- Each player tracks their own NP
- Award 1-2 per session
- 5 NP maximum cap
- Forces regular spending

**Alternative: Shared Pool**
- Party shares one pool
- Requires coordination
- Can create drama

### Earning Guidelines

Award NP for:
- ✅ Playing Burdens in ways that create drama
- ✅ Excellent roleplay moments
- ✅ Advancing group goals
- ✅ Clever solutions
- ✅ Taking narrative risks

Don't award for:
- ❌ Just showing up
- ❌ Successful rolls
- ❌ Killing enemies
- ❌ Avoiding Burdens

### Spending Requirements

**Every NP expenditure requires:**
1. Narrative justification ("I've been training with...")
2. Connection to recent events
3. GM approval

**Example:**
"I want to upgrade 'Combat Training' from Minor to Moderate. We've fought in 5 brutal battles, and I've been sparring with the veteran mercenary between missions. I spend 2 NP."

---

## Quick Reference Tables

### Probability Table (d6 pools)

| Pool Size | Diff 1 | Diff 2 | Diff 3 | Diff 4 | Diff 5 | Diff 6 |
|-----------|--------|--------|--------|--------|--------|--------|
| 3d6       | 70%   | 35%   | 11%   | 2%    | —     | —     |
| 4d6       | 87%   | 59%   | 28%   | 9%    | 2%    | —     |
| 6d6       | 95%   | 79%   | 51%   | 26%   | 11%   | 3%    |
| 8d6       | 99%   | 91%   | 70%   | 44%   | 23%   | 10%   |
| 10d6      | ~100% | 96%   | 83%   | 61%   | 37%   | 20%   |
| 12d6      | ~100% | 99%   | 91%   | 74%   | 52%   | 32%   |
| 15d6      | ~100% | ~100% | 97%   | 87%   | 70%   | 50%   |

### Power Level Examples

| Power Level | Stat Points | Typical Pool (Optimized) | Fairly Easy Diff |
|-------------|-------------|--------------------------|------------------|
| 1           | 4-6         | 4-6d6                    | Diff 1           |
| 2           | 8-12        | 7-9d6                    | Diff 2           |
| 3           | 12-16       | 10-12d6                  | Diff 3           |
| 4           | 16-20       | 13-15d6                  | Diff 4           |
| 5           | 20-24       | 16-18d6                  | Diff 5           |

---

## Key Design Principles

1. **Fiction First:** The narrative drives mechanics, not the other way around
2. **Success = Intent:** No partial success on successful rolls
3. **Players Roll Everything:** GM describes, players resolve
4. **One Anchor/One Burden:** Prevents stacking, forces meaningful choice
5. **Focus Is Precious:** Limited resource for important moments
6. **Conditions Tell Stories:** "Broken Ribs" > "6 damage"
7. **Stress Prevents One-Shots:** Buffer before lasting harm
8. **NP Requires Narrative:** All progression tied to story

---

## Common Edge Cases

### Multiple Anchors Apply
**Rule:** Choose ONE most relevant Anchor per roll

**Example:** "Street Fighter" and "Brawling Expert" both seem relevant
**Resolution:** Player chooses which is MORE applicable to this specific action

### No Applicable Anchor
**Rule:** Roll with just Rating + Focus + Assets + Aspects

**This is called a "Desperation Roll"** - still possible to succeed

### Can I Use Focus on Any Stat?
**Yes.** Focus is ONE shared pool you can spend on any stat roll.

**But:** You're limited by that stat's Focus Cap (Rating + 2).

**Example:** You have Focus 18/20. Using Agility (Rating 3, Focus Cap 5)? You can spend up to 5 Focus on this roll, even though you have 18 available.

### Can Assets Stack?
**Yes,** if narratively justified.

**Example:** Using lockpicks (+1d6) AND night vision goggles (+1d6) to pick a lock in darkness = both apply = +2d6

### Can I Use Narrative Injection to Avoid a Roll?
**No.** Narrative Injection creates facts, not outcomes.

**Bad:** "I inject that the lock is already open"
**Good:** "I inject that I studied this lock type last week" (might grant bonus dice)

### What If I Run Out of Focus?
**Roll with just Rating + Assets + Aspects (for dice pool)**

Then add your Anchor successes and subtract Burden penalties.

Focus is optional. You can always attempt actions without spending it.

### What's the Difference Between Focus and Anchors?
**Focus:** Adds **dice** to your pool (probabilistic)
- 1 Focus = +1d6
- Still need to roll 5-6 to get successes
- Uncertain outcome

**Anchors:** Add **guaranteed successes** to your total (deterministic)
- Moderate Anchor = +2 successes always
- No roll needed
- Certain outcome

**Example:** Spending 2 Focus gives +2d6 (might get 0-2 successes). Having a Moderate Anchor gives +2 successes guaranteed.

---

## Designer Notes

### Why d6 Only?
- Ubiquitous, easy to find
- Simple success threshold (5-6)
- Linear scaling
- Fast counting

### Why Fixed Stress (3 boxes)?
- Easy to remember
- Future-proofing for abilities that increase it
- Prevents stat-driven HP bloat
- Keeps fights dangerous

### Why a Shared Focus Pool with Per-Stat Caps?
- **Simpler tracking:** One number to manage instead of four
- **Flexible tactics:** Spend where you need it most
- **Prevents spam:** Focus Cap prevents dumping everything into your best stat
- **Strategic depletion:** Using Focus heavily early means less for later encounters
- **Natural pacing:** Caps encourage spreading Focus usage across different stats

### Why No Anchor/Burden Stacking?
- Prevents auto-win scenarios (+6 successes before rolling)
- Forces meaningful choice ("Which Anchor is MOST relevant?")
- Keeps dice relevant
- Maintains tension
- Creates interesting decisions

### Why Anchors/Burdens Give Successes (Not Dice)?
- **More impactful:** Guaranteed successes feel meaningful
- **Dice stay relevant:** Still need to roll well with your pool
- **Clear player agency:** "I have +2 successes locked in"
- **Balances against Focus:** Focus = probabilistic (dice), Anchors = deterministic (successes)
- **Simpler math:** Don't remove dice, just add/subtract from final count

### Why Focus Adds Dice (Not Successes)?
- Maintains uncertainty
- Dice still matter
- Doesn't trivialize Difficulty
- Feels like "pushing harder" not "guaranteeing"

---

_End of Rules Summary_

**Remember:** This is your master reference. Test changes here before updating the full manuscript.
