# Water Ways — Public Showcase

**Mapping System Dynamics water research to the river basins, aquifers, and water systems researchers actually study.**

**Repository type:** Public project showcase  
**Project area:** Water systems · System Dynamics · GIS · research infrastructure  
**Canonical source:** Private research repository  
**Role:** Creator and developer

---

## Project overview

Water Ways is an interactive research infrastructure project designed to connect researchers to the **water systems they study**, rather than simply mapping them to the locations of their universities or organizations.

The project keeps three concepts separate:

1. **Researcher identity and methods** — who the researcher is and which systems approaches are associated with the work.
2. **Research geography** — the river basins, aquifers, and water systems studied.
3. **Affiliation geography** — institutional location, retained as profile context rather than treated as evidence of research geography.

## What I built

- Researcher directory with preserved profile and affiliation context
- River-basin and aquifer research geography
- HydroBASINS-based global basin layer
- IGRAC–UNESCO transboundary aquifer layer
- Search and filtering across researchers and water systems
- Independent map-layer controls
- Researcher-to-water-system relationships
- Evidence-state handling for uncertain or unmatched geography
- Exportable research-geography records

## Why it matters

Water research is organized around physical systems that cross institutional and national boundaries. A university address does not tell us which basin or aquifer a researcher studies. Water Ways makes those research geographies visible and searchable.

## Design principle

A researcher can study multiple water systems, and a water system can be studied by multiple researchers. Source-named systems and current GIS polygon matches are treated as distinct evidence states rather than collapsed into one field.

## Repository note

This repository is a curated public showcase. The working application, research-processing workflow, and internal development materials remain in a separate private repository.

## Author

**Arya Kia**  
System Dynamics · Water systems · Research infrastructure
