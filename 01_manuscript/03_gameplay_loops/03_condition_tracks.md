# Stress & Conditions

Instead of hit points, characters track harm through **Stress** (a quick-recovery buffer) and **Condition Tracks** (lasting narrative wounds). Damage is separate from your stat Reserves—getting hurt doesn't drain your abilities, but it does make everything harder.

---

## The Two-Layer System

### Layer 1: Stress (The Buffer)
**Stress** represents your ability to absorb hits, dodge at the last second, take glancing blows, or power through pain without serious injury. It's your combat stamina and resilience.

### Layer 2: Conditions (The Wounds)
**Conditions** are actual injuries, trauma, and lasting harm. They're narrative, they're named, and they stick around until properly treated.

**Why both?**
- **Stress** prevents one-shot Conditions from lucky hits
- **Conditions** create meaningful narrative consequences
- Together, they create tension without HP bloat

---

## Stress Tracks

Each character has two **Stress Tracks** with capacity based on their stats:

### Physical Stress
**Capacity = Might Rating + 3**

| Might Rating | Stress Capacity |
| ------------ | --------------- |
| 1            | 4 boxes         |
| 2            | 5 boxes         |
| 3            | 6 boxes         |
| 4            | 7 boxes         |
| 5            | 8 boxes         |

### Mental Stress
**Capacity = Persona Rating + 3**

| Persona Rating | Stress Capacity |
| -------------- | --------------- |
| 1              | 4 boxes         |
| 2              | 5 boxes         |
| 3              | 6 boxes         |
| 4              | 7 boxes         |
| 5              | 8 boxes         |

**Character Sheet Layout:**
```
PHYSICAL STRESS (Might 3 = 6 boxes)
□ □ □ □ □ □

MENTAL STRESS (Persona 2 = 5 boxes)
□ □ □ □ □
```

---

## Taking Damage: How It Works

When you take damage (physical or mental), follow this flow:

### Step 1: Determine Damage Amount
The GM determines how much damage you take based on:
- Attack difficulty (Easy = 1, Moderate = 2, Hard = 4, etc.)
- Enemy weapon/ability
- Narrative circumstances

### Step 2: Mark Stress Boxes
Mark Stress boxes equal to the damage amount.

**Example:** You take 3 Physical damage. Mark 3 Physical Stress boxes.
```
PHYSICAL STRESS (Might 3 = 6 boxes)
■ ■ ■ □ □ □
```

### Step 3: Check for Overflow
If damage exceeds your remaining Stress capacity, you **overflow** into a Condition.

**Overflow Formula:**
- **Damage > Remaining Stress** = Take a Condition
- **Overflow Amount** determines Condition severity:
  - **1-2 overflow** = Minor Condition (-1d6)
  - **3-4 overflow** = Moderate Condition (-2d6)
  - **5+ overflow** = Severe Condition (-3d6)

After taking a Condition, **reset Stress to 0** for that track.

---

## Example: Taking Damage with Stress

**Setup:** Character has Might 3 (6 Physical Stress boxes). Currently at 3/6 Stress.

```
PHYSICAL STRESS (Current: 3/6)
■ ■ ■ □ □ □
```

**Scenario 1: Damage Within Capacity**
Takes 2 damage → Mark 2 more boxes (now at 5/6)
```
PHYSICAL STRESS (Current: 5/6)
■ ■ ■ ■ ■ □
```
**Result:** No Condition. Absorbs the hit.

---

**Scenario 2: Damage Overflows**
Takes 4 damage:
- 3 remaining Stress absorbs 3 damage
- 1 overflow → Minor Physical Condition

```
PHYSICAL STRESS (Current: 0/6 - RESET)
□ □ □ □ □ □

PHYSICAL CONDITIONS
■ Minor (-1d6): "Bruised ribs"
□ Moderate (-2d6)
□ Severe (-3d6)
```

---

**Scenario 3: Massive Overflow**
At 4/6 Stress, takes 7 damage:
- 2 remaining Stress absorbs 2 damage
- 5 overflow → Severe Physical Condition

```
PHYSICAL STRESS (Current: 0/6 - RESET)
□ □ □ □ □ □

PHYSICAL CONDITIONS
□ Minor (-1d6)
□ Moderate (-2d6)
■ Severe (-3d6): "Bleeding out"
```

---

## Condition Tracks

When Stress overflows, you take a **Condition**—a named, narrative injury or trauma.

### The Two Core Tracks

| Track        | What It Represents                      | Affects                                 |
| ------------ | --------------------------------------- | --------------------------------------- |
| **Physical** | Bodily harm, injury, exhaustion         | Mighty and Agility rolls (typically)    |
| **Mental**   | Psychological stress, trauma, confusion | Intellect and Persona rolls (typically) |

**Optional Third Track:** Some campaigns may add a **Social** track for reputation damage. Recommended for intrigue campaigns.

### Condition Slots

```
PHYSICAL CONDITION TRACK
□ Minor (-1d6)     _______________
□ Moderate (-2d6)  _______________
□ Severe (-3d6)    _______________

MENTAL CONDITION TRACK
□ Minor (-1d6)     _______________
□ Moderate (-2d6)  _______________
□ Severe (-3d6)    _______________
```

**Standard (Gritty):** 1 Minor, 1 Moderate, 1 Severe per track (3 slots total)

**Heroic Variant:** 2 Minor, 2 Moderate, 1 Severe per track (5 slots total)

---

## Naming Your Conditions

When you take a Condition, **you name it**. The mechanical tier stays the same, but the narrative flavor is yours.

**Physical Examples:**
- Minor: "Bruised ribs," "Sprained ankle," "Winded"
- Moderate: "Broken arm," "Concussed," "Deep wound"
- Severe: "Bleeding out," "Shattered leg," "Critical burns"

**Mental Examples:**
- Minor: "Rattled," "Distracted," "Frustrated"
- Moderate: "Terrified," "Paranoid," "Can't focus"
- Severe: "Broken will," "Traumatized," "Losing grip on reality"

**Why Name Conditions?**
- **Memorable:** "Broken ribs" sticks better than "Moderate Physical #2"
- **Guides recovery:** Named Conditions suggest how they heal
- **Narrative weight:** "Bleeding out" feels urgent

---

## When Conditions Apply

### Physical Conditions
**Typically affect:** Mighty and Agility rolls

**Can affect all rolls when severe enough:**
- "Bleeding out" affects everything—you're dying
- "Exhausted" makes all actions harder
- "Broken leg" primarily affects movement

**GM discretion:** Apply when they would realistically hinder the action.

### Mental Conditions
**Typically affect:** Intellect and Persona rolls

**Examples:**
- "Rattled" (-1d6) makes it hard to concentrate
- "Terrified" (-2d6) affects decision-making and social confidence
- "Traumatized" (-3d6) impacts all mental/social actions

**Can affect physical rolls sometimes:**
- "Panicked" might make your hands shake
- "Distracted" could affect aim

---

## Player Choice: Shifting Conditions

Players have agency in **how** they take Conditions.

**When overflow creates a Condition, you can:**

1. **Take it straight:** Mark the appropriate slot
2. **Split it across slots** (if available):
   - Moderate overflow → Mark 2 Minor slots instead
   - Preserves higher slots for later
3. **Shift to another track** (with narrative justification):
   - Physical overflow → Mental Condition ("The pain broke me")
   - Mental overflow → Physical Condition ("Stress gave me a migraine")

**Rule:** Must make narrative sense. GM can veto if absurd.

**Why allow this?**
- Players get tactical choice
- Encourages creative consequence interpretation
- Some characters prefer mental strain over physical (or vice versa)

---

## Being Taken Out

### When Stress AND Conditions Are Full

**Physical Track Example:**
```
PHYSICAL STRESS: 6/6 (full)
PHYSICAL CONDITIONS: All 3 slots marked
```

You're **critically vulnerable**. The next Physical damage takes you out:
- Unconscious
- Dying (can be saved)
- Captured
- Fleeing

### Taking Damage with Full Tracks

**Option 1: Shift to another track** (with justification)
- Physical full, Mental available? Take it as Mental trauma

**Option 2: Overflow = Taken Out**
- If all appropriate tracks are full, you're out of the scene

---

## Stacking Conditions

Multiple Conditions can apply to the same roll. They stack.

**Example:** You have:
- Physical Stress: 5/6 (tiring)
- Physical: "Broken ribs" (-2d6)
- Mental: "Rattled" (-1d6)

You're climbing a wall (Agility + concentration). Both Conditions apply.
**Total penalty:** -3d6 from Conditions (Stress doesn't penalize, it just absorbs damage)

**Important:** Stress boxes don't penalize rolls—they only track how much buffer you have left before taking Conditions.

---

## Recovery

### Stress Recovery (Fast)
Stress recovers quickly—it's bruises, adrenaline dumps, and near-misses.

- **Short Rest (10 minutes):** Recover ALL Stress boxes
- **Catch Your Breath (1 minute):** Recover 1 Stress box (in combat downtime)
- **Full Rest (8 hours):** Automatically full

**Stress is meant to reset between fights.** It's the buffer that lets you keep going.

### Condition Recovery (Slow)
Conditions are real injuries—they need care.

#### Physical Recovery
- **Short Rest (10 minutes):** May clear Minor Physical at GM discretion
- **Medical Care:** Intellect roll (Difficulty 2-4)
  - Success: Clear or downgrade one Condition
- **Full Rest (8 hours):** Clear one Physical Condition
- **Extended Downtime (days/weeks):** Clear all but Severe

#### Mental Recovery
- **Short Break:** May clear Minor Mental
- **Therapy/Support:** Social scenes, talking it through
  - Can downgrade Mental Conditions
- **Full Rest (8 hours):** Clear one Mental Condition
- **Narrative Resolution:** Some require story resolution

**GM Tip:** Conditions should linger, but not forever. Recovery is part of pacing.

---

## Death and Dying

### The Death Spiral

When all Physical Stress AND Conditions are maxed, you're in danger.

**Taken Out doesn't always mean dead:**
- Unconscious
- Captured
- Fleeing in terror
- Dying (but can be saved)

**Actual Death:**
- Usually requires player consent OR clear narrative setup
- GMs should telegraph lethal threats: "This next hit could kill you"
- Death should be rare, meaningful, and dramatic—not random

**Alternatives to Death:**
- Accept a permanent Burden to survive
- Use Narrative Injection to reframe the outcome
- Surrender or retreat before death occurs

---

## Armor and Damage Reduction

Armor **reduces Stress damage** before it's marked.

| Armor Type | Effect                                  |
| ---------- | --------------------------------------- |
| Light      | -1 Stress damage per hit                |
| Medium     | -2 Stress damage per hit                |
| Heavy      | -3 Stress damage per hit                |

**Example:** You take 4 Physical damage. You're wearing Medium armor (-2).
- 4 damage - 2 armor = 2 Stress marked

**If damage is reduced to 0, you take no Stress and no Condition.**

**Armor typically only applies to Physical damage.** Mental and Social damage bypass armor.

---

## Attack Resolution (For GMs)

When an attack succeeds, determine damage:

### Base Damage by Intent
| Attack Intent             | Base Damage |
| ------------------------- | ----------- |
| "I want to distract them" | 1 Stress    |
| "I want to hurt them"     | 2 Stress    |
| "I want to injure them"   | 4 Stress    |
| "I want to take them down"| 6 Stress    |

**Excess Successes** can increase damage:
- +1 Success over needed = +1 Stress damage
- +2 Successes = +2 Stress damage
- Etc.

**Example:** Player declares "I want to hurt the bandit" (2 Stress base). Needs 2 Successes, rolls 4. That's 2 excess = 4 Stress damage total.

---

## Power Level Variants

Adjust Stress capacity and Condition slots for campaign tone:

| Power Level | Physical Stress   | Mental Stress     | Condition Slots     | Tone         |
| ----------- | ----------------- | ----------------- | ------------------- | ------------ |
| **Gritty**  | Might + 2         | Persona + 2       | 1/1/1 per track     | Deadly, tense|
| **Standard**| Might + 3         | Persona + 3       | 1/1/1 per track     | Balanced     |
| **Heroic**  | Might + 4         | Persona + 4       | 2/1/1 per track     | Resilient    |
| **Epic**    | Might + 5         | Persona + 5       | 2/2/1 per track     | Pulp action  |

Standard characters can absorb 4-6 hits of Stress before risking Conditions.

---

## Optional: Social Stress & Conditions

For intrigue-heavy campaigns:

```
SOCIAL STRESS (Persona + 3)
□ □ □ □ □ □

SOCIAL CONDITION TRACK
□ Minor (-1d6)     _______________
□ Moderate (-2d6)  _______________
□ Severe (-3d6)    _______________
```

**Examples:**
- Minor: "Embarrassed," "Awkward moment"
- Moderate: "Publicly shamed," "Reputation damaged"
- Severe: "Exiled," "Completely discredited"

**When to use:** Failed social rolls, reputation attacks, political maneuvering

**Recovery:** Requires public redemption, reputation repair, or time

---

## Quick Reference

**Stress Tracks:**
- Physical: Might + 3 boxes
- Mental: Persona + 3 boxes
- Recovers: 10 minutes (all boxes)

**Condition Tracks:**
- Physical: Mighty/Agility penalties
- Mental: Intellect/Persona penalties
- Slots: Minor (-1d6), Moderate (-2d6), Severe (-3d6)
- Recovers: Medical care, rest, narrative resolution

**Taking Damage:**
1. Mark Stress boxes
2. If overflow → Take Condition based on overflow amount
3. Reset Stress to 0 after Condition

**Armor:** Reduces Stress damage (Light -1, Medium -2, Heavy -3)

**Players choose:** Where to take Conditions (with justification)

**Taken Out:** When Stress + Conditions both maxed, next hit ends you

---

## Example in Play

**Setup:** Rook has Might 3 (6 Physical Stress). Currently at 2/6 Stress. No Conditions yet.

```
PHYSICAL STRESS (Current: 2/6)
■ ■ □ □ □ □
```

---

**Round 1: Minor Hit**

**GM:** "The thug swings a pipe at your head. Make an Agility roll to dodge."

**Rook:** *Rolls, fails*

**GM:** "It connects, but you roll with it. Take 2 Physical Stress damage."

**Rook:** *Marks 2 more boxes (now at 4/6)*

```
PHYSICAL STRESS (Current: 4/6)
■ ■ ■ ■ □ □
```

**No Condition yet.** Still in the fight, feeling the pressure.

---

**Round 2: Harder Hit**

**GM:** "He follows up with a gut punch. You're hit. That's 4 Stress damage."

**Rook:** "I only have 2 Stress boxes left. I'm overflowing."

**GM:** "Right. 2 boxes absorb 2 damage, then 2 overflow = Minor Physical Condition. Name it."

**Rook:** *Marks last 2 Stress boxes, overflows, takes Minor Condition, resets Stress*

```
PHYSICAL STRESS (Current: 0/6 - RESET)
□ □ □ □ □ □

PHYSICAL CONDITIONS
■ Minor (-1d6): "Winded and bruised"
□ Moderate (-2d6)
□ Severe (-3d6)
```

---

**Round 3: Armored Defense**

**GM:** "Another attack coming. This one's 5 Stress damage if it hits."

**Rook:** "I'm wearing Light armor (-1 Stress). If I fail to dodge, it's 4 Stress damage."

**GM:** "Correct. Roll to dodge."

**Rook:** *Rolls, fails* "Damn."

**GM:** "You take 4 Stress damage. You're at 0 Stress, so that's all overflow. 4 overflow = Moderate Physical Condition."

**Rook:** "Can I split it? I'll take another Minor Physical and a Minor Mental instead—the pain is breaking my focus."

**GM:** "That works narratively. Mark them."

```
PHYSICAL STRESS (Current: 0/6)
□ □ □ □ □ □

PHYSICAL CONDITIONS
■ Minor (-1d6): "Winded and bruised"
■ Minor (-1d6): "Cracked rib"
□ Moderate (-2d6)
□ Severe (-3d6)

MENTAL CONDITIONS
■ Minor (-1d6): "Pain-distracted"
□ Moderate (-2d6)
□ Severe (-3d6)
```

**Now fighting at -3d6 total** (-2d6 Physical, -1d6 Mental when applicable).

---

**Round 4: Turning the Tide**

**Rook:** "I'm spending 3 Effort and using my 'Street Brawler' Anchor to counter-punch. I want to HURT him."

**GM:** "Roll it."

**Rook:** *Builds pool, rolls... 5 Successes!* "Yes!"

**GM:** "You needed 2, got 5. That's 2 base Stress + 3 excess = 5 Stress damage to him. He staggers back, gasping."

**Enemy thug:** Takes 5 Stress, overflows into Moderate Condition, looking rough.

---

**After Combat: Recovery**

**GM:** "The fight's over. You have ten minutes before reinforcements arrive."

**Rook:** "I catch my breath and bandage up. Does my Stress reset?"

**GM:** "Yes. Short rest clears all Stress boxes. You're back to 0/6."

```
PHYSICAL STRESS (Current: 0/6 - FULL RECOVERY)
□ □ □ □ □ □
```

**GM:** "But the Conditions stay. You're still 'Winded and bruised,' 'Cracked rib,' and 'Pain-distracted' until you get proper medical care."

**Rook:** "Fair. I'll push through."

**Still at -3d6 from Conditions, but Stress buffer is restored for the next fight.**

---

## Final Thought

The Stress & Conditions system creates dynamic combat:
- **Early fight:** Stress absorbs hits, you feel the pressure building
- **Mid fight:** Conditions start landing, penalties mount, decisions matter
- **Late fight:** You're battered, low on Stress, every hit could end you

**Stress** lets you feel like an action hero absorbing punishment.
**Conditions** make you vulnerable and force tactical retreat.

Together, they create tension without HP bloat, and every wound tells a story.

**Fight smart. Know when to retreat. And remember: Stress recovers, but scars don't.**
