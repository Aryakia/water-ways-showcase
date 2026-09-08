# Water Ways — Public Showcase

**Mapping System Dynamics water research to the river basins, aquifers, and water systems researchers actually study.**

| | |
|---|---|
| **Project type** | Research infrastructure · GIS · System Dynamics · water systems |
| **Role** | Creator and developer |
| **Status** | Active research prototype |
| **Canonical source** | Private research repository |
| **Public disclosure** | Curated project architecture, methods, aggregate metrics, and source attribution only |

---

## Executive summary

Water Ways is an interactive research-infrastructure project for discovering **who studies which water systems** using System Dynamics, systems thinking, and related modeling approaches.

Most researcher maps place people at their universities. That is useful for networking, but it can misrepresent water research: the actual object of study may be a river basin, aquifer, catchment, lake, or groundwater system located far from the researcher's institution. Water Ways therefore separates **researcher identity**, **research geography**, and **affiliation geography**.

## Current public-safe project snapshot

The working research catalogue currently contains:

- **27** publication-linked river basins, aquifers, catchments, lakes, and groundwater systems
- **34** mapped study records plus **2** relevant non-spatial method records
- **92** distinct researchers across the evidence catalogue
- **5** mapped peer-reviewed *System Dynamics Review* articles
- a systematic search of accessible System Dynamics Society proceedings from **1984–2026**
- **102** preserved researcher profiles from the original Water Ways pilot
- **303** preserved source-derived collaboration links
- **68** profiles with one or more source-named studied water systems
- **40** profiles currently matched to at least one IGRAC–UNESCO 2025 transboundary-aquifer polygon
- **292** global HydroBASINS level-3 basin areas
- **426** IGRAC–UNESCO transboundary aquifers from the 2025 edition

These figures describe the current working snapshot and may grow as literature and researcher records are reviewed.

## What I built

### Researcher + publication layer

Researcher profiles preserve affiliation and profile context while keeping publication evidence separate. Publication-level records connect researchers to named study areas only when the underlying source supports that relationship.

### Basin and aquifer geography

The platform combines two major geographic reference layers:

- **HydroBASINS v1c, Pfafstetter level 3** for global river-basin context
- **IGRAC–UNESCO Transboundary Aquifers of the World, 2025 edition** for international groundwater context

The aquifer layer is explicitly treated as a transboundary inventory, not a complete map of every local aquifer on Earth.

### Evidence-aware matching

A source-named water system and a current GIS polygon match are not treated as the same evidence state. Unmatched or uncertain names remain visible for validation instead of being forced into an unsupported polygon.

### Interactive research discovery

The working application supports:

- researcher, study, water-system, methodology, and source panels
- basin selection → associated studies and researchers
- search and scope filters
- independent map-layer controls
- deep zoom, mouse/touch navigation, pan controls, keyboard movement, and reset
- external researcher/publication links
- filtered research-geography export

## Evidence rules

1. Peer-reviewed articles, conference records, and discovery profiles remain visibly distinct.
2. A basin-study link requires a defensible named study area in the underlying research record.
3. One researcher may study multiple water systems.
4. One water system may connect multiple researchers.
5. Affiliation coordinates are context—not evidence of where research occurred.
6. Global or methodological work remains non-spatial until a defensible study area is identified.
7. Geographic datasets carry edition, source, license, and limitation metadata.

## Research discovery approach

The evidence release combines targeted researcher discovery with a systematic search of accessible annual System Dynamics Society proceedings from 1984 through 2026 and *System Dynamics Review* metadata. This is intended as a transparent discovery process, not a claim that every relevant researcher worldwide has already been found.

Known limitations include uneven indexing of older proceedings, incomplete conference metadata, terminology differences across research communities, and changing geographic delineations.

## Data provenance

Key public sources used by the project include:

- HydroSHEDS / HydroBASINS — https://www.hydrosheds.org/products/hydrobasins
- IGRAC & UNESCO-IHP Transboundary Aquifers of the World 2025 — https://doi.org/10.58154/yb8g-cp97
- researcher-discovery inputs derived from the SuAVE Transboundary Groundwater Research landscape and curated System Dynamics water-community records

## Why this matters

Water problems are organized around physical systems that cross institutional and national boundaries. A research directory that can move from **basin → study → researcher** is more useful for collaboration, literature discovery, and community building than a map of university addresses alone.

## Public/private boundary

This repository intentionally does **not** publish the canonical source application, raw working datasets, internal data-processing scripts, private notes, credentials, environment configuration, or unpublished research materials. It is a curated public case study of the project's purpose, architecture, methods, and aggregate results.

## Author

**Arya Kia**  
System Dynamics · Water systems · Research infrastructure
