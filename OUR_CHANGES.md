# Our Changes

This fork aims to preserve the casual-player philosophy of Matcha Flavoured while making adjustments where newer design changes have introduced unnecessary grinding, reduced player choice, or created technical problems.

## Already Solved / Community Solutions

Before implementing custom replacements, prefer existing Matcha or community solutions where they are maintained and compatible with the current version.

- **Accessibility / darkness**
  - Matcha provides instructions for adjusting or removing the darker lighting.
  - An accessible Matcha resource pack is available.
  - Test and adopt the existing solution rather than creating our own.

- **Vanilla textures**
  - A community Matcha-Vanilla resource pack already exists.
  - Test compatibility with the current Matcha version before considering custom texture changes.

## Gameplay Changes

### Obol acquisition

**Status:** Planned

Matcha no longer provides Obols through enough repeatable mob-related sources. This makes villager trading disproportionately dependent on leaving the base and repeatedly hunting for Obols.

**Goal:** Restore a reliable, repeatable source of Obols while preserving exploration and other acquisition methods.

**Likely change:** Restore Obol drops from appropriate mobs.

---

### Crystal Hearts / Divine Fragments

**Status:** Under investigation

Divine Fragments are important for late-game progression but have comparatively restricted acquisition methods. Crystal Hearts have more varied acquisition methods, but the current conversion from excess hearts into Divine Fragments is very low.

**Goal:** Give excess Crystal Hearts a meaningful alternative use while providing another reliable route to Divine Fragments.

**Current proposal:** Change the existing heart-to-fragment conversion to approximately:

`1 Crystal Heart → 4 Divine Fragments`

Before implementation, verify the practical acquisition rates of Crystal Hearts and Divine Fragments to ensure the new conversion does not make Divine Fragments trivial to obtain.

---

### Wither spawning

**Status:** Under investigation

Matcha restricts where the Wither can be spawned. This removes a potentially repeatable source of Divine Favour/Divine Fragments and prevents technical players from creating optimized Wither farms.

**Goal:** Preserve player choice by allowing technical players to use Wither farms while still retaining the normal Wither encounter.

**Likely direction:** Review the current restriction and consider returning Wither spawning closer to vanilla behaviour.

---

### Sulfur

**Status:** No change planned

Initial investigation suggests Sulfur is sufficiently obtainable through normal gameplay. No custom solution is currently justified.

---

### Villager trading

**Status:** No general changes planned

The general Matcha villager trading system is not currently a priority. The Obol and Crystal Heart/Divine Fragment economy will be addressed separately first.

---

## Performance

### Mob spawning

**Status:** Planned investigation

Previous profiling identified Matcha's spawning/datapack logic as a major contributor to server lag during rapid exploration and Elytra travel.

The current Matcha version should be profiled again before making changes.

**Goal:** Improve spawning performance without unnecessarily removing Matcha's gameplay changes.

---

## Design Principle

> Keep the creativity and convenience that make Matcha special, while preserving the casual-player philosophy that made us love it in the first place.

Changes should generally increase player choice rather than simply make the game easier. Casual players should have reasonable ways to progress without being forced into repetitive grinding, while technical players should remain free to optimize systems where appropriate.
