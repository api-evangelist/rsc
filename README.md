# RSC - Royal Society of Chemistry

The Royal Society of Chemistry (RSC) provides developer APIs through its ChemSpider platform, enabling programmatic access to one of the world's largest chemistry databases with over 88 million unique chemical compounds. The APIs support compound search, structure retrieval, format conversion, and data enrichment for cheminformatics applications.

**Human URL:** https://developer.rsc.org/

## APIs

| API | Description |
|-----|-------------|
| [ChemSpider Compounds API](openapi/rsc-chemspider-compounds-openapi.yml) | Search, filter, and retrieve chemical compound records |

## OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [rsc-chemspider-compounds-openapi.yml](openapi/rsc-chemspider-compounds-openapi.yml) | ChemSpider Compounds API covering filter, records, lookups, and tools |

## Rules

| Ruleset | Description |
|---------|-------------|
| [rsc-spectral-rules.yml](rules/rsc-spectral-rules.yml) | Spectral ruleset enforcing RSC API design conventions |

## Capabilities

### Workflow Capabilities

| Capability | Description |
|------------|-------------|
| [chemical-research.yaml](capabilities/chemical-research.yaml) | Compound discovery, structure lookup, and format conversion for researchers |

### Shared Definitions

| Shared | Description |
|--------|-------------|
| [chemspider-compounds.yaml](capabilities/shared/chemspider-compounds.yaml) | Per-API consumed definition for the ChemSpider Compounds API |

## Schemas

| Schema | Description |
|--------|-------------|
| [rsc-compound-schema.json](json-schema/rsc-compound-schema.json) | JSON Schema for ChemSpider compound records |

## Structures

| Structure | Description |
|-----------|-------------|
| [rsc-compound-structure.json](json-structure/rsc-compound-structure.json) | JSON structure documentation for ChemSpider data entities |

## JSON-LD

| Context | Description |
|---------|-------------|
| [rsc-context.jsonld](json-ld/rsc-context.jsonld) | JSON-LD context mapping ChemSpider vocabulary to standard ontologies |

## Examples

| Example | Description |
|---------|-------------|
| [rsc-filter-by-name-example.json](examples/rsc-filter-by-name-example.json) | Filter compounds by name (aspirin) |
| [rsc-get-record-details-example.json](examples/rsc-get-record-details-example.json) | Get compound record details |
| [rsc-convert-chemical-format-example.json](examples/rsc-convert-chemical-format-example.json) | Convert SMILES to InChI format |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [rsc-vocabulary.yml](vocabulary/rsc-vocabulary.yml) | Domain vocabulary for chemistry, cheminformatics, and API operations |

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
