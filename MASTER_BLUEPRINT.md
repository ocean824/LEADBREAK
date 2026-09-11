# LEADBREAK Master Blueprint

## Fighter contract
Stocks/health rules configurable; percentage/knockback model if selected; movement/jump/air control; attacks/specials; hitstop; hitstun; DI/tech/ledge rules as canon defines; shields/dodge/parry if selected; items optional; stage hazards; camera; match rules; training; replay.

## Network
Design simulation for deterministic/rollback-friendly behavior from inception even if online ships later. Inputs/state snapshots, prediction/resimulation and desync diagnostics are first-class.

## Stage Forge
Grid/freeform arena authoring, platforms/spawns/hazards/backgrounds/rules, validation, preview, save/share policy. Creator content remains sandboxed/data-driven.

## Unreal
FightingGameTemplate accelerates prototype; canonical move/physics/netcode rules own final behavior. Narrative/Ultra support menus/meta/story, not duplicate combat state. Couch co-op accelerates local input patterns.

## AXIOM
Native deterministic fighter simulation, renderer and PYRAMID social/tournament integration.

## XYRA
Frame data, hitbox/hurtbox, knockback, controller latency, rollback simulation, desync, stage validation, local multiplayer device churn, performance, accessibility and competitive integrity.

## Delivery
Fighter simulation → local match → 4-fighter slice → visual pipeline → online rollback → roster/stages → Stage Forge → ranked/tournaments → AXIOM.