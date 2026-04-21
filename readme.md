# Lighting Product Property Ontology (LPPO) v2.0

**Permanent URI:** https://w3id.org/ppon/lppo/  
**Documentation:** https://jthsemweblab.github.io/Lighting_Product_Property_Ontology/  
**Version:** 2.0  
**License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)  
**Standard:** SIS-CEN/TS 17623:2021

## Description

LPPO is a data dictionary for the properties describing electric lighting products, luminaires, and sensing devices used in the construction industry. It extends the [Building Product Property Ontology (BPPO)](https://w3id.org/ppon/bppo), which implements the ISO 23386:2020 framework.

**v2.0 change:** All 358 property classes previously identified by opaque GUIDs (e.g., `lppo.owl#0DlY8lmBT8gxJCl04yS42z`) are now identified by human-readable, name-derived URIs (e.g., `lppo:DimmingControlMethod`). Original GUIDs are retained as `bppo:hasGUID` values for traceability to the source standard.

## Repository Structure

```
/
├── index.html              # HTML documentation (GitHub Pages entry point)
├── index-en.html           # WIDOCO-generated documentation (English)
├── ontology.ttl            # Turtle serialization
├── ontology.owl            # RDF/XML serialization
├── ontology.jsonld         # JSON-LD serialization
├── ontology.nt             # N-Triples serialization
├── .htaccess               # Apache content negotiation (for future Apache hosting)
├── provenance/             # WIDOCO provenance page
├── resources/              # CSS and JS assets
└── src/
    ├── lppo_v2.ttl         # Source ontology (Turtle, v2.0)
    └── bppo.ttl            # Building Product Property Ontology (dependency)
```

## Serializations

| Format | URL |
|---|---|
| HTML docs | [index.html](index.html) |
| Turtle | [ontology.ttl](ontology.ttl) |
| RDF/XML | [ontology.owl](ontology.owl) |
| JSON-LD | [ontology.jsonld](ontology.jsonld) |
| N-Triples | [ontology.nt](ontology.nt) |

## Namespace

```
Prefix: lppo
URI:    https://w3id.org/ppon/lppo#
```

## Related Ontologies

- [BPPO](https://w3id.org/ppon/bppo) — Building Product Property Ontology (upper-level)
- [LPPO v1.0](https://w3id.org/ppon/lppo/1.0) — Previous version

## Generated with

[WIDOCO](https://w3id.org/widoco/) v1.4.25 — Wizard for Documenting Ontologies
