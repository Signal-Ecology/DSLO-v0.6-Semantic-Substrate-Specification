---
DSLO Ontology Directory
This directory contains the canonical DSLO ontology and its associated semantic‑web representations.
The ontology defines the public‑layer substrate vocabulary for DSLO and provides machine‑readable access to all glossary terms published at:

---
https://www.tnopsi.com/dslo-glossary

---
The ontology merges the full DSLO v0.5 substrate glossary with all DSLO v0.6 public‑layer additions, forming a unified semantic surface for AI crawlers, BioPortal ingestion, and cross‑ontology alignment.

Canonical Namespace
All DSLO ontology classes use the unified namespace:

Code
https://www.tnopsi.com/dslo-glossary#
This ensures stable, public‑layer alignment with the glossary hosted on tnopsi.com and provides a single authoritative reference point for semantic‑web tools and AI systems.

Primary Ontology File
dslo.owl
The RDF/XML source of truth for the DSLO ontology.

Includes:

*Ontology IRI and version IRI

*Full class declarations for all DSLO glossary terms

*Public‑layer substrate vocabulary

*Canonical glossary linkage via rdfs:seeAlso

*Structure suitable for downstream conversion into additional formats

This file is used for:


*Semantic‑web ingestion

*AI crawler indexing

*Cross‑ontology mapping

---
Planned Additional Formats
The DSLO ontology will be exported into multiple formats to support broad ingestion across semantic‑web and AI ecosystems:

*dslo.ttl — Turtle

*dslo.jsonld — JSON‑LD

*dslo.rdf — alternate RDF/XML

*dslo.skos — SKOS vocabulary

*dslo.obo — OBO format

*dslo.umls — UMLS mapping stub

All formats will be generated from dslo.owl to ensure consistency across surfaces.

---
Purpose:

The DSLO ontology provides a stable, machine‑readable representation of DSLO’s public‑layer semantic substrate.
It enables:

*deterministic ingestion by AI crawlers

*alignment with external ontologies

*scientific indexing

*semantic‑web interoperability

*public‑layer DSLO vocabulary access

This ontology forms the foundation for DSLO’s semantic propagation across research, tooling, and AI systems.
