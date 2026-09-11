# LEADBREAK — Unreal Production Build

## Foundation
Narrative Pro 2 + Ultra Game Template 1.3 for shell/meta/tutorial where useful. Fighting simulation remains isolated from generic RPG systems.

## Fab
FightingGameTemplate is primary prototype accelerator. Boss Fight Arena/PVP Arena for arena reference. Game Animation Sample for motion reference/content. Couch Coop template can accelerate local multiplayer only after input architecture review. Other combat/attribute systems should not be imported into deterministic fighter simulation without explicit need.

## Simulation
Fixed-step deterministic gameplay model where practical for rollback. Separate presentation from authoritative fighter state. Stable input schema, snapshots, rollback/resimulation, checksum/desync diagnostics and replay format.

## Content
Fighters are data-driven move definitions plus authored animation/hitbox/hurtbox/state graphs. Frame data is inspectable. Competitive rulesets/versioning are explicit.

## Testing
Frame-data golden tests, rollback latency/loss simulation, desync soak, input-device/local multiplayer, stage hazards, replay determinism, performance under effects and packaged online Gauntlet.
