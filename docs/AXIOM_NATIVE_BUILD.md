# LEADBREAK — AXIOM Native Build

AXIOM migration is gated on deterministic/rollback networking and fighter simulation quality.

Required services: fixed-step simulation, input capture/prediction, snapshots/rollback/resimulation, low-latency networking, animation/presentation decoupling, hit/hurt collision, replay/desync diagnostics, UI and matchmaking/platform adapters.

Fighter/move/stage/rules schemas should be engine-neutral. Golden rollback/replay fixtures compare Unreal and AXIOM outcomes. AXIOM may improve tooling/rendering, but competitive simulation semantics require explicit versioning.
