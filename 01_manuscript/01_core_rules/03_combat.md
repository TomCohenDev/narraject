# Combat

> **Status:** PLACEHOLDER — Major design decisions pending

---

## Design Goals

1. **Fast:** 15-30 minutes for meaningful combat
2. **Dangerous:** Stakes matter; avoiding fights is valid
3. **Narrative:** Combat generates story, not just damage
4. **Readable:** You should know the stakes at any moment

---

## Open Questions

### Initiative
- Popcorn (current actor picks next)?
- Side-based (all PCs, then all NPCs)?
- Stat-based (highest Agility first)?

### Damage Track
**Critical:** Damage is separate from stat pools.

Options under consideration:
- Condition ladder (Fine → Hurt → Wounded → Critical → Down)
- Wound slots (3-5 slots, each adds penalty)
- Stress track (Blades-style)

### Weapons
- Add dice to attack pool?
- Modify damage directly?
- Both?

---

## Placeholder Structure

```
1. DECLARE — State intents
2. ACT — Resolve via core loop
3. ASSESS — Update conditions, describe results
```

---

## NPCs

Following Cypher's lead: NPCs need minimal stats.

```
GANG ENFORCER
Level: 3
Motivation: Protect the boss
Special: Pack tactics (+1d6 with allies)
```

Level determines Hits needed to affect them AND threat they pose.

---

## Coming Soon

- Attack resolution details
- Defense calculation
- Damage application
- Range and positioning
- Special combat actions
