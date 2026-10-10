# portable_presence
**From Portable Rights to verifiable physical presence**

Research on portable evidence of artwork presence, location and institutional check-ins, evolving from Portable Rights and informed by the Safe City map infrastructure.

Portable Presence is a research evolution of
[Portable Rights](https://github.com/sstm-research/portable_rights).

It investigates how physical artworks and cultural assets can carry
verifiable evidence of where they are, where they have been exhibited,
and who attested their presence.

## Research lineage

Portable Trust  
↓  
Legallery  
↓  
Portable Rights  
↓  
Safe City  
↓  
Portable Presence

Each stage preserves a different research question.

**Portable Trust**  
Identity, authenticity, provenance and portable evidence.

**Legallery**  
Independent implementation focused on artwork resale and creator rights.

**Portable Rights**  
Research on transfers, resale events and rights infrastructure.

**Safe City**  
Reference implementation for maps, location-based events and
privacy-aware public infrastructure.

**Portable Presence**  
Research on artwork location, institutional check-ins and
verifiable physical presence.

## Research question

> Can a physical artwork carry verifiable evidence of where it is,
> where it has been exhibited, and who attested its presence?

## From rights to presence

Portable Rights asks:

**What happened to the artwork and which rights are affected?**

Portable Presence adds:

**Where is the artwork, where has it been, and who can verify that presence?**

The research progression becomes:

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

## Presence events

Portable Presence investigates structured events such as:

- `EXHIBITED_AT`
- `CHECKED_IN_AT`
- `CHECKED_OUT_AT`
- `STORED_AT`
- `LOANED_TO`
- `RETURNED_TO`

A minimal presence event may contain:

**ARTWORK_ID**  
↓  
**LOCATION / VENUE**  
↓  
**TIMESTAMP**  
↓  
**ISSUER / VERIFIER**  
↓  
**EVIDENCE**

## The map is not the authority

The map is a presentation layer.

Trust should come from attributable and verifiable presence events.

A museum, gallery, collector, artist or authorized institution may
attest that an artwork entered, left, was exhibited at or was stored
at a location.

Portable Presence investigates how these claims can remain useful even
when the map interface or platform changes.

## Potential use cases

- museums
- galleries
- exhibitions
- cultural institutions
- artwork loans
- distributed collections
- temporary exhibitions
- restaurants, hotels and establishments displaying artworks
- storage facilities
- private collections

A future owner or institution could view a history such as:

**Created in São Paulo**  
→ **Exhibited at Gallery A**  
→ **Transferred to Collector B**  
→ **Loaned to Museum C**  
→ **Returned to Collector B**

## Safe City reference

Portable Presence is informed by the Safe City implementation.

SSTM Research fork:

https://github.com/sstm-research/safe-city-app

Original repository:

https://github.com/deegalabs/safe-city-app

Safe City is a location-based public infrastructure project.

Its existing implementation includes map and geospatial primitives,
privacy-oriented design and public location-based events.

Portable Presence explores how those technical patterns can be
reapplied to physical artworks and cultural assets.

The Safe City project itself should not be interpreted as an artwork
tracking system.

## Privacy

Location evidence can create sensitive information.

Portable Presence should distinguish between:

- public exhibition location
- institutional storage location
- private collection location
- precise coordinates
- approximate location
- public evidence
- restricted evidence

A public map should never automatically expose sensitive private
locations simply because location evidence exists.

## Research principles

### Lastro

Who is authorized to attest that an artwork is present at a location?

### Rastro

Where has the artwork been, when, and which evidence supports each event?

### Infrastructure

How can presence evidence remain portable across museums, galleries,
collectors and applications?

## Relationship to previous research

Portable Presence does not replace:

- Portable Trust
- Legallery
- Portable Rights
- Safe City

It documents a new research layer created from their intersection.

## Research

**Felipe Gustavo Santana dos Santos**  
Felipe Gusta · w3bgus.eth

SSTM Research  
https://github.com/sstm-research

Accelerated by **MeGust4 Networks**

Incubated by **T0FU TURE Frameworks**

## Attribution

Safe City remains attributed to its original repository and contributors.

The SSTM Research copy is maintained as a fork to preserve provenance.

Portable Presence represents a later research interpretation and does
not claim authorship of the original Safe City implementation.

## License

Software authored directly in this repository is released under
Apache License 2.0 unless otherwise stated.

Third-party code, implementations, datasets and research materials
retain their original authorship, licenses and rights.

---

**Lastro → Rastro → Infrastructure**
