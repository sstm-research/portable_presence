# Research Lineage

Portable Presence is part of an evolving research lineage within
[SSTM Research](https://github.com/sstm-research).

This document preserves how the research moved from portable trust,
to creator rights, and then to physical presence and location evidence.

---

## 01 — Portable Trust

**Type:** Original research  
**Repository:**  
https://github.com/sstm-research/portable_trust

Portable Trust investigated how creators and physical artworks could
carry verifiable evidence across organizations and platforms.

Its core lifecycle included:

**CREATE → AUTHENTICATE → EXHIBIT → SELL → TRANSFER → RESELL → LICENSE → REPRODUCE**

The central research question was:

> Can a physical artwork carry a verifiable lifecycle of authorship,
> provenance, transfers and rights, with claims issued by independent
> actors, without depending on a single platform as the authority?

---

## 02 — Legallery

**Type:** Independent hackathon implementation

**SSTM Research fork:**  
https://github.com/sstm-research/legallery

**Original repository:**  
https://github.com/Gowdakthegreat/legallery

**Project submission:**  
https://devfolio.co/projects/legallery-2a79

Legallery implemented part of the Portable Trust research direction
during the EAG Global Buildathon in Florianópolis.

The project explored artwork resale and Brazil's Artist's Resale Right
(*direito de sequência*).

### Outcome

**2nd place — EAG track**

Each participating team member received a **USD 500 prize**.

The SSTM Research repository remains a fork in order to preserve the
original implementation, contributors and Git history.

---

## 03 — Portable Rights

**Type:** Research evolution  
**Repository:**  
https://github.com/sstm-research/portable_rights

Portable Rights was created after the Legallery implementation.

It shifted the research from portable evidence alone toward the
economic and rights consequences of artwork lifecycle events.

Research progression:

**AUTHORSHIP**  
↓  
**ARTWORK IDENTITY**  
↓  
**PROVENANCE**  
↓  
**TRANSFER**  
↓  
**RESALE EVENT**  
↓  
**CREATOR RIGHTS**  
↓  
**RIGHTS INFRASTRUCTURE**

---

## 04 — Safe City

**Type:** Independent reference implementation

**SSTM Research fork:**  
https://github.com/sstm-research/safe-city-app

**Original repository:**  
https://github.com/deegalabs/safe-city-app

Safe City is a location-based public infrastructure application.

Its existing implementation provides research references around:

- maps
- geospatial interfaces
- location-based events
- public infrastructure
- privacy-aware interaction
- real-time data

Safe City was not originally developed as an artwork tracking system.

Its relevance to this research emerged later, when the map and
location-event model was considered as a possible foundation for
physical artwork presence.

---

## 05 — Portable Presence

**Type:** Research evolution  
**Repository:**  
https://github.com/sstm-research/portable_presence

Portable Presence begins from a new question:

> Can a physical artwork carry verifiable evidence of where it is,
> where it has been exhibited, and who attested its presence?

It extends Portable Rights by adding physical location and institutional
presence to the artwork lifecycle.

Research progression:

**ARTWORK IDENTITY**  
↓  
**PROVENANCE**  
↓  
**TRANSFER**  
↓  
**RIGHTS**  
↓  
**PHYSICAL PRESENCE**  
↓  
**LOCATION HISTORY**

---

## Presence events

Portable Presence investigates events such as:

- `EXHIBITED_AT`
- `CHECKED_IN_AT`
- `CHECKED_OUT_AT`
- `STORED_AT`
- `LOANED_TO`
- `RETURNED_TO`

A presence event may connect:

**ARTWORK_ID**  
→ **VENUE / LOCATION**  
→ **TIMESTAMP**  
→ **ISSUER / VERIFIER**  
→ **EVIDENCE**

The map displays these events.

The map itself is not the authority.

---

## Research evolution

The current lineage is:

**Portable Trust**  
Portable identity, provenance and verifiable lifecycle evidence.

↓

**Legallery**  
Independent implementation of creator resale-rights logic.

↓

**Portable Rights**  
Rights, transfers, resale events and institutional rights infrastructure.

↓

**Safe City**  
Independent reference for maps, location events and privacy-aware public infrastructure.

↓

**Portable Presence**  
Artwork presence, institutional check-ins and location history.

---

## Research principle

Each repository represents a different moment in the research.

Later repositories should preserve the provenance of earlier work rather
than rewriting that history.

**Lastro → Rastro → Infrastructure**
