# LEADBREAK — Production Systems

Domains: deterministic fighter simulation, input, moves, fighters, stages, rulesets, rollback networking, matchmaking/ranking, replay/spectator, training, UI/audio, content/editor.

Fixed-step state is serializable/snapshot-able. Presentation does not mutate authoritative simulation. Move/frame/hit/hurt data is inspectable. Rulesets and balance are versioned. Replays include build/rules/content version.

Requirements: LEAD-REQ-001 rollback determinism; 002 low-latency controls; 003 frame-data integrity; 004 desync diagnostics; 005 competitive stage/rules variants; 006 training/replay; 007 Unreal/AXIOM simulation parity.
