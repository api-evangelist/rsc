# RSC (rsc)

The Royal Society of Chemistry (RSC) provides developer APIs through its ChemSpider platform, enabling programmatic access to one of the world's largest chemistry databases with over 88 million unique chemical compounds. The APIs support compound search, structure retrieval, format conversion, and data enrichment for cheminformatics applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Chemistry
- Cheminformatics
- Chemical Data
- Science

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### ChemSpider Compounds API

The ChemSpider Compounds API (v1) provides comprehensive access to the RSC ChemSpider chemical database, supporting compound filtering by name, SMILES, InChI, InChIKey, formula, molecular weight, mass, and elemental composition. Authenticated endpoints allow retrieval of compound records, external references, molecular images, and MOL files. The API also supports batch operations and chemical format conversions between SMILES, InChI, InChIKey, and Mol formats.

- **Human URL:** [https://developer.rsc.org/](https://developer.rsc.org/)
- **Base URL:** `https://api.rsc.org/compounds/v1`

#### Tags

- Chemistry
- Cheminformatics
- Compounds
- Chemical Search

#### Properties

- [Documentation](https://developer.rsc.org/compounds-v1/apis)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/openapi/rsc-chemspider-compounds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rsc-chemspider-compounds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rsc-chemspider-compounds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ChemSpider Tools API

The ChemSpider Tools API provides chemical format conversion utilities, supporting conversions between SMILES, InChI, InChIKey, and Mol file formats. It also includes InChIKey validation. The tools are useful for cheminformatics pipelines that need to normalize chemical identifiers across different format conventions.

- **Human URL:** [https://developer.rsc.org/](https://developer.rsc.org/)
- **Base URL:** `https://api.rsc.org/compounds/v1`

#### Tags

- Chemistry
- Format Conversion
- Cheminformatics
- Tools

#### Properties

- [Documentation](https://developer.rsc.org/compounds-v1/apis)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/openapi/rsc-chemspider-compounds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rsc-chemspider-compounds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rsc-chemspider-compounds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rsc-equipment-rental)
- [Portal](https://developer.rsc.org/)
- [Authentication](https://developer.rsc.org/)
- [Sign Up](https://developer.rsc.org/)
- [Terms of Service](https://www.rsc.org/legal/)
- [Privacy Policy](https://www.rsc.org/help-legal/legal/privacy/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
