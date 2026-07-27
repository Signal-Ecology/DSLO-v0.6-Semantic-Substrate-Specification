DSLO Schema (v0.6)
Canonical machine‑readable structure for DSLO substrate primitives.

The DSLO schema defines the minimal fields required to represent any signal‑bearing system within the DSLO substrate.
These fields correspond to the five operational primitives used in DSLO’s universal signal mapping:

state (x) — localized, moment‑bound position

transition (τ) — lawful movement between states

orientation (o) — contextual routing and alignment

correction (c) — invariant‑preserving fallback structure

meaning_status (κ) — meaning‑bearing condition of the signal

The schema is provided in three synchronized formats:

JSON — canonical machine‑readable structure

JSON‑LD — linked‑data representation

YAML — human‑readable configuration format

This directory establishes the DSLO v0.6 schema layer, ensuring consistent ingestion across semantic engines, AI systems, and substrate‑native tooling.
