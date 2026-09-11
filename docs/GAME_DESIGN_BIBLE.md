# LEADBREAK — Game Design Bible

## Identity
Fast 2D/2.5D anime/manga crossover-style platform fighter with grayscale/comic presentation, irreverent humor and dynamic platform arenas. Original characters/IP and mechanics; inspirations guide genre, not copied expression.

## Core loop
Select fighter/loadout → arena match → movement/spacing/combos/knockback/objective → results/rank/rewards → training/customization/rematch.

## Combat
Platform-fighter fundamentals: directional attacks, specials, air options, shield/guard/dodge policy, grabs, knockback/percent or game-specific damage model, recoveries, ledges/platforms and items/hazards as mode configuration. FightingGameTemplate accelerates prototype; canonical combat must be deterministic and rollback-compatible.

## Movement
Ground/air acceleration, jumps, fast-fall, dodge, wall/platform interactions and character-specific movement. Titanfall Movement concepts are reference only unless a mode/character explicitly needs them.

## Arenas
Multi-platform dynamic maps with competitive-safe variants. Boss Fight Arena/PVP Arena may accelerate prototyping. Future Forge-like map editor is a later capability with safe scripting/content validation.

## Netcode
Rollback-first architecture, deterministic simulation boundaries, input delay configuration, replays and desync diagnostics. Competitive integrity is a release gate.

## Presentation
Manga panel transitions, grayscale/limited-color art direction, impact frames, stylized captions and comedic interstitials. Presentation must remain readable during competitive play.

## V1→V3
V1 proves 4 fighters, 3 arenas, local + online rollback matches, training and replay. V2 expands roster/modes/ranking/editor prototype. V3 mature competitive ecosystem, content/editor tooling and AXIOM-native implementation.
