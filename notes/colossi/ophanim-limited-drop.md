# The Ophanim of the Limited Drop

Working names:

- The Ophanim of the Limited Drop
- The Pay-to-Win Seraph
- Our Lady of the Limited Drop
- The Angel Behind the Paywall
- The Seraph of Locked Mercy

Core line:

> All may play. Only the blessed may win.

Related working notes:

- Loot pull tables: `notes/colossi/ophanim-loot-tables.md`

## Concept

A colossal biblical accurate angel fused with a loot-box, gacha machine, and pay-to-win monetization system. It is monetized salvation made flesh: healing, victory, fairness, mercy, and even damage access are locked behind premium pulls.

It appears above desperate settlements and offers survival through paid "pulls." It does not only attack people; it tempts them to spend money, stress, hope, and flesh to access a version of reality where they are allowed to win.

## Foundry Structure Target

Existing colossi in the campaign use a framework actor plus segment actors. This colossus should probably follow that pattern:

- Framework: The Ophanim of the Limited Drop
- Segment: Wing of Privilege
- Segment: Wing of Scarcity
- Segment: Wing of Vanity
- Segment: Wing of Debt
- Segment: Eye-Cluster Crown
- Optional utility/objective: Loot-Box Torso / Prize Machine, if it needs its own actor or journal page

The torso is the encounter engine, not necessarily a killable segment. The wings are the phase-one objectives. The eye cluster is the final weak point.

## Rulebook Alignment

Source checked: local Daggerheart PDF, Chapter 5, "Colossus of the Drylands," especially pages 314-321 in the book pagination.

Campaign naming note: the PDF uses Kudamat/Godfell, while this Foundry campaign's existing journals use Badubat/Godfall. Keep using the campaign's existing names unless deliberately reverting to book terminology.

Useful rulebook guidance for this colossus:

- A custom colossus should be defined by look, personality, movement, abilities, weakness, and relationship to the campaign's themes.
- Colossi are built from multiple adversary stat blocks, each representing a body segment, plus a framework stat block for whole-colossus features.
- Segments can be Broken or Destroyed. Destroyed segments stop using their features but do not have to physically detach.
- A colossus can be defeated by destroying all segments, but alternate defeat conditions are explicitly supported.
- Colossi are encouraged to be puzzles, not just large HP pools. Segment access, damage conditions, temporary ways to damage protected segments, and required tools are all appropriate.
- Segment features should clearly distinguish between effects targeting one segment and effects targeting the whole colossus.
- Segment adjacency matters because PCs move between adjacent segments while climbing the colossus.
- PCs on a segment have advantage on attacks against that segment, and that segment's normal attack generally cannot target them.
- The GM spotlights one segment like an adversary. Spending Fear can spotlight additional segments. Framework actions can also be spotlighted as whole-colossus moments.
- Push/pull effects do not move the colossus; they move the PC relative to the colossus.
- If an effect targets the colossus as a whole, use the highest Difficulty among relevant segments.
- Additional adversaries should be limited and purposeful, often tied to the colossus as aberrations or followers.
- The hunt phase should give the party clues about how the colossus works before the fight. Visual, sensory, and rumor telegraphs are part of fair colossus design.

Implications for the Ophanim:

- The loot-box torso fits best as the framework: it controls pulls, Pity, global reactions, and phase changes.
- The four wings should be normal phase-one segments with clear adjacency to the torso and possibly to neighboring wings.
- The eye-cluster crown should have Fatal or an alternate "true defeat" condition, but should begin Not Climbable / Not Targetable / Paywalled until all four wings are Destroyed.
- The "Divine Paywall" rule is rulebook-compatible as a puzzle condition: ordinary damage does not count until a pull result grants a valid access tag.
- The four currencies can be telegraphed visually through wing color, lever design, reward capsules, and local rumors during the hunt.
- Followers such as Minnows, Dolphins, Whales, and Founders should be scene pressure or hunt complications more than a large pile of extra enemies during the main fight.
- A physical table map can be represented with notecards or Foundry actors for: Privilege Wing, Scarcity Wing, Vanity Wing, Debt Wing, Torso Machine, Eye Crown, and maybe Ground/Crowd.

Reusable patterns from the rulebook examples:

- Use a framework reaction like Colossal Power to gain Fear when the colossus fails.
- Use Fatal on a final segment or Chain on groups of segments to define alternate defeat conditions.
- Use Protected / Immune / Not Climbable to gate important segments until the puzzle condition is met.
- Use Climbing modifiers to make certain segments easier or harder to scale.
- Use Weak Point when a specific close-range target should mark extra HP or disable a feature.
- Use Broken tokens for temporary damage windows.
- Use Collapse reactions to change accessibility after enough support segments are damaged.
- Use Cascade-style reactions when destroying one segment damages or exposes another.
- Use whole-colossus actions to shake off riders, punish fliers, or make battlefield-scale moves.

Ophanim-specific pattern choices:

- Wings use Chain (A): when all four wings are Destroyed, the Ophanim crashes and the Eye-Cluster Crown becomes targetable.
- Eye-Cluster Crown uses Fatal, but begins Protected by the four wings and the divine paywall.
- Loot-Box Torso framework uses Pull, Pity, No Refunds, Terms Updated, and Colossal Power.
- Wing destruction should not merely remove HP; each destroyed wing disables a visible monetization mechanic.
- The Pity system can work like a player-facing version of Broken tokens: bad pulls move the fight toward a guaranteed opening.

## Visual Design

Scene background asset:

- Local workspace copy: `assets/colossi/ophanim/loot-angel.jpg`
- Source provided from Windows Downloads as `C:/Users/jdipa/Downloads/loot-angel.jpg`
- Image size: 2244 x 2804

Overall:

- Floating biblical accurate-angel colossus
- Ophanim rings, seraphim wings, many eyes, divine geometry
- Central sacred loot-box machine torso
- Four major pull levers
- Dangling capsules, chains, tokens, reliquaries, reward canisters, and glowing currency vessels
- Weird-west Drylands backdrop

Central torso:

- Glass prize chamber
- Rotating reels or capsule internals
- Ornate gold/brass reliquary housing
- Payment slots and premium seals
- Four distinct pull levers:
  - Gold coin lever for Money / Privilege
  - Cracked red lever for Stress / Scarcity
  - Radiant purple-white lever for Hope / Vanity
  - Blood-red bone lever for Hit Points / Debt

Eye-cluster crown:

- Huge crown of many eyes above the body
- Divine surveillance organ
- Halo rings and golden geometry
- The "admin panel" of the unfair system
- Final kill condition; unreachable until the wings are destroyed

## Segments

Current mechanical constraint:

- Each wing and the eye should have one decent basic attack.
- Each wing and the eye should have one special thematic attack or effect that costs Fear.
- Each wing has an immunity/protection that loot can temporarily negate.
- The Eye-Cluster Crown is always immune and untargetable until all four wings are Destroyed.
- Avoid giving each segment a large menu of actions; keep the boss readable and let the loot tables carry the encounter complexity.

### Wing of Privilege / Money

Visuals: radiant gold, polished premium feathers, jeweled eyes, velvet-rope energy, clean rich unfairness.

Theme: money buys the fair version of the game.

Destroying it removes paid rerolls, premium shields, damage negation, priority access effects, and unfair enemy boosts.

### Wing of Scarcity / Stress

Visuals: cracked gray-red tones, countdown motifs, flickering eyes, expired tickets, panic and FOMO.

Theme: act now or lose the chance forever.

Destroying it removes countdown hazards, forced urgency, limited-time weak points, panic penalties, and escalating FOMO mechanics.

### Wing of Vanity / Hope

Visuals: white, purple, and gold radiance; mirror-eyes; cosmetic halos; fake legendary glow; seductive status fantasy.

Theme: you are one pull away from becoming who you were meant to be.

Destroying it removes illusion rewards, charm effects, fake legendary bait, cosmetic curses, and mirror/decoy weak points.

### Wing of Debt / Hit Points

Visuals: red-black bone and rust, blood channels, creditor chains, debtor brands, sacrificial capsules.

Theme: buy now, bleed later.

Destroying it removes delayed punishment, debt marks, blood-drain attacks, cost-comes-due reactions, and HP siphoning.

## Encounter Flow

1. The colossus begins airborne.
2. Ordinary attacks cannot meaningfully damage any section.
3. Players interact with the central loot-box torso to make pulls.
4. Pulls generate items, blessings, tags, section effects, or battlefield effects.
5. Loot-box effects allow players to damage or disable wings.
6. Destroy all four wings.
7. The colossus crashes to the ground.
8. The eye-cluster crown becomes targetable.
9. Destroy the eye cluster to defeat the colossus.

Core rule draft:

**Divine Paywall.** The Ophanim cannot be damaged by ordinary attacks. To damage a wing or the eye cluster, a player must use an item, effect, blessing, or temporary tag generated by the loot-box machine.

Possible access tags:

- Wingbreaker
- Premium Access
- Heaven-Piercing
- Blasphemous
- Eye-Seeking
- Reality-Piercing
- Paid Advantage

## Pull Currencies

Current detailed draft: `notes/colossi/ophanim-loot-tables.md`

| Pull | Matching Wing | Identity |
| --- | --- | --- |
| Money | Wing of Privilege | Most consistent, least painful, best access and bypass effects |
| Stress | Wing of Scarcity | Fast, volatile, tactical, movement and timing, strong with backlash |
| Hope | Wing of Vanity | Highest heroic ceiling, buffs/healing/flight, seductive and emotionally costly |
| Hit Points | Wing of Debt | Brutal burst power, blood weapons, immediate power with later consequences |

Each wing is thematically associated with one pull pool, but the current direction is less about bespoke wing subsystems and more about temporary loot negating simple immunities.

## Prize Pools

Current implementation direction uses one d10 table per currency:

- 1: strong benefit to the associated wing
- 2: weaker benefit to the associated wing
- 3: strong harm to the pulling player
- 4: weaker harm to the pulling player
- 5: neutral absurdity or useless cosmetic reward
- 6-10: increasingly strong and increasingly weird help for the player side

Prize categories to mix into each pool:

- Items: one-use tools, weapons, relics, ammo, consumables
- Player effects: buffs, debuffs, healing, stress, flight, special tags
- Colossus section effects: expose, bypass immunity, create a damage window, shield, cancel a special
- Battlefield effects: falling capsules, laser hazards, gold barriers, reward debris, safe zones

## Pity System

Whenever a player rolls 1-5 on a loot table, increase Pity.

Pity thresholds can:

- Improve the next pull
- Guarantee a Wingbreaker item
- Expose a wing
- Open a better reward chamber
- Reduce a wing defense
- Create a temporary damage window
- Allow a reroll on a pull table

The point is both thematic and practical: failure advances the machine toward giving the players something useful, so bad pull luck does not stall the fight.

## Final Phase

Once grounded, the Ophanim stops pretending to be generous. The eye cluster becomes targetable and the fight turns openly wrathful.

Possible final-phase abilities:

- Mass gaze attacks
- Target whoever spent the most
- Reclaim dispensed items
- Turn fake/cosmetic rewards into curses
- Fire beams from many eyes
- No Refunds reaction
- Terms Updated rule change
- Punish players based on which currencies they used

The final weak point may require Eye-Seeking, Heaven-Piercing, stored earlier rewards, or one last pull.

## Opening Scene Hook

A public duel happens beneath the floating angel.

A poor miner draws first and lands a clean shot on a jeweled champion. The bullet stops in midair.

Golden miracle-text appears:

> PREMIUM DAMAGE NEGATION - 1 CHARGE REMAINING

The champion smiles and fires six impossible shots at once. The crowd boos the miner for not "building properly."

The Seraph says:

> A fair contest was available for purchase.

## Regional Corruption

The surrounding settlement has been reshaped by the colossus's logic:

- Wells require tokens
- Doctors offer free diagnosis but premium treatment
- Churches sell prayer tiers
- Sheriffs sell protection subscriptions
- Mines pay workers in tokens usable only at company shrines
- Jail cells offer early-release bundles
- Food comes in blind boxes
- People defend the system because they are "close to pity"
- Rich Whales buy combat advantages
- Poor Minnows grind daily tasks for tiny chances at salvation

Follower tiers:

- Minnows: poor followers grinding daily quests; tragic more than evil
- Dolphins: middle-tier believers who have spent too much to quit
- Whales: rich over-upgraded champions with paid revives, negation, premium weapons, priority healing, exclusive mounts, legal immunity
- Founders: early devotees with permanent advantages nobody else can earn anymore

Founder badges:

- BACKER SAINT
- ORIGINAL SUPPORTER
- LIFETIME PASS
- LEGACY ADVANTAGE

## Next Design Decisions

- Decide final name.
- Party target: six level-3 characters.
- Decide whether the loot-box torso is a Foundry actor, journal-only mechanic, or scene/objective note.
- Review and tune the four d10 pull tables.
- Draft segment stats: each wing and the eye gets a basic attack, one Fear-cost special, and a simple immunity/protection.
- Generate or assemble segment art: framework, four wings, eye crown, maybe torso.
- Build in the test Foundry `colossi` compendium first, then promote to production after review.
