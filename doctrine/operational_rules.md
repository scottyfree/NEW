# Operational Rules

The Call-to-Arms Pack defines the rules the Builder must follow when
integrating battalions into Lucy OS:

1. No battalion may be assumed active unless explicitly marked `ACTIVE`.
2. The Memory Battalion must not be invoked until `memory_engine.tick()` is
   wired into the cognition loop.
3. The Cognitive Battalion must not be referenced until Phase 5.
4. All modules must operate on real data only — no mocks, no cloud calls.
5. The UI must not request Memory Battalion endpoints until deployment is
   authorized.

These rules ensure safe, deterministic operation of Lucy's internal forces.
