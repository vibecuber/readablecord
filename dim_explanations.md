__**Dims & Expiries — Full Breakdown**__

For an overview of what dims are and how to set them up, see #dims-and-expiries-overview-unfinished

---
## Wave 7 Dim

**Purpose:** Push waves 12-13 without stalling

Stalling wave 12 once almost always means stalling it twice because:
- Multiple bigs split at this point in the waves
- The wave 12 dinhs cannot activate until after the second wave 12 stall

> Any crab that spawns **on or before** wave 7 will expire the tick wave 13 spawns normally *(zero stalls)*

---
## Wave 11 Offset 4 Dim

**Purpose:** Push wave 18

- Not all s12 crabs are equal — this dim identifies which s12 crabs are worth hitting and which aren't
- Helps significantly with zero-stall precap frequency, as wave 17 is the most likely wave to stall due to noodling on bigs

> Any crab that spawns **on or before** wave 11 offset 4 will expire the tick wave 18 spawns normally *(zero stalls)*

---
## Wave 12 Offset 4 Dim

**Purpose:** Push wave 19

- Activates automatically once the wave 11 dim expires
- Shows which crabs will and won't expire before wave 19 spawns

> Unnecessary if you choose not to use the wave 11 dim

---
## Wave 14 Dim

**Purpose:** Push wave 20

- Activates once wave 19 spawns
- Shows which crabs will and won't expire before wave 20 spawns

> Unnecessary to set a later execution tick if you aren't using the wave 11 and wave 12 dims
> If skipping both, you may want to opt for a standalone wave 14 dim only

---
## Waves 20-21 Dims

This is a series of **4 dims** between waves 20 and 21, each lining up tick-perfect to a specific post-cap wave:

```
20 dim             → expires on wave 25 spawn
20 dim offset +8t  → expires on wave 26 spawn
20 dim offset +12t → expires on wave 27 spawn
21 dim offset +4t  → expires on wave 28 spawn
```

- Follow the dim for **north crabs**
- For **south crabs**, clearing the 22 dinhs still takes priority over the dim
- **Main purpose:** Minimize stalls on waves 24-27

---
## Wave 22 Dim

**Purpose:** Identify crabs that expire on insta 29

Wave 22 crabs expire the same tick insta 29 occurs. In duos, insta 29 *(no stalls 26-29)* is the optimal scenario as it maximizes big-popping potential and late wave pushing.

- Dim within the **first 4 ticks** of wave 22 spawning *(1st cycle)* so both roles can quickly identify what to hit and what to ignore
- Splits between waves 22 and 23 can also be ignored — they expire at 3-stall 28

**Why it helps Ranger:**
- Lets you identify hittable nylos faster without losing ticks on the 2-tick cycle
- Continue hitting dimmed crabs until your wave 23 prefire, then ignore dimmed crabs completely

**Why it helps Mager:**
- Makes it easier to identify whether you have a good east 24 dinhs or west 25 dinhs
- s20-s22 melees are easy to get baited by — they have **no dinhs value** as they expire between waves 25-29
- You can still hit dimmed crabs until your wave 24 prefire if s23 splits from the wave 22 prefire haven't spawned yet

---
## Wave 25 Dim

**Purpose:** After wave 29 spawns, the 25, 26, and 27 bigs will all split in sequence. The goal is to spawn wave 31 **before** any of these bigs begin splitting into a chain stall.

Three reasons to dim 25:
1. Helps spawn wave 31 before the 25/26/27 bigs start splitting
2. Results in fewer wave 29 stalls and a faster wave 30 spawn
3. Prevents the ranger from maging or meleeing undimmed crabs too early — maging too early risks ruining barrages, meleeing too early wastes 4 ticks with a bad melee weapon

**Mager — Additional Info:**
- Ignore double barrages containing dimmed crabs in favor of something s26 or higher
- Triple barrages are fine to take for a better 29 push if the situation calls for it
- Optionally set the dim to wave 26 instead — dimming on 25 can make it harder to evaluate the 25 dinhs, but functionally the outcome is the same since there are always plenty of s27+ crabs to hit

**Ranger — Additional Info:**
- Kill all dimmed w23/s24 or higher **range** splits to push wave 29
- **Mage hits should only ever be on s26 or higher**

---
## 27/x and 28/x Dims (Standard cleanup dims)

These are your two normal cleanup dims — choosing the right one for your skill level directly impacts your nylo averages and is the **most important dim decision** you make.

See #dims-and-expiries-overview-unfinished for which to choose.

> The 27 dim counts a 27 stall as equivalent to a 28 stall:
```
27/x = 28/x + 8
Example: 27/20 = 28/12 + 8 = 27/20
(wave 27 is naturally 8 ticks long)
```
*Example: Normal 28/12 expects (28, 28) stalls before wave 29. If you get (27, 28) instead, 28/12 adds 4 unnecessary extra ticks. 27/20 corrects this by treating (27, 28) as equivalent to (28, 28).*

---
## 29 Dim (Supplemental cleanup dim)

- Use **alongside** your 28/x or 27/x dim, not instead of it
- Covers the abnormal case of **insta 29** *(no 27 or 28 stalls before wave 29 spawns)*
- Your 28/x and 27/x dims handle normal situations — 29 dim handles insta 29

---
[Wave 7 dim](https://discord.com/channels/1502348308432162998/1502458070444412969/1502465512620429324)
[Wave 11 dim](https://discord.com/channels/1502348308432162998/1502458070444412969/1502465531486408776)
[Wave 12 dim](https://discord.com/channels/1502348308432162998/1502458070444412969/1502465553363767358)
[Wave 14 dim](https://discord.com/channels/1502348308432162998/1502458070444412969/1502465574213521540)
[Wave 20-21 dim](https://discord.com/channels/1502348308432162998/1502458070444412969/1502465611647946852)
[Wave 22 dim](https://discord.com/channels/1502348308432162998/1502458070444412969/1502465666794651698)
[Wave 25 dim](https://discord.com/channels/1502348308432162998/1502458070444412969/1502465729583386767)
[Wave 27/x dim](https://discord.com/channels/1502348308432162998/1502458070444412969/1502465984689344573)
[Wave 29 dim](https://discord.com/channels/1502348308432162998/1502458070444412969/1502466136678334596)
