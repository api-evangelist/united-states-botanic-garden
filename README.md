# United States Botanic Garden

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The United States Botanic Garden (USBG) is a living museum in Washington, D.C. that showcases a diverse collection of plants from around the world. Established by the U.S. Congress in 1820, the Botanic Garden serves as a resource for education and inspiration, promoting an understanding and appreciation of plants and their importance to the environment and human well-being. The USBG maintains more than 9,500 accessions representing approximately 44,000 individual plants, managed through its Living Collections database. The garden is administered by the Architect of the Capitol and is located adjacent to the U.S. Capitol on the National Mall.

**Website:** [https://www.usbg.gov/](https://www.usbg.gov/)

## Resources

| Resource | Link |
|---|---|
| Website | [usbg.gov](https://www.usbg.gov/) |
| Plant Collections | [Plant Collections](https://www.usbg.gov/gardens-plants/plant-collections) |
| Collection Search | [Search the Collection](https://www.usbg.gov/gardens-plants/search-collection) |
| Plant Database | [Plant Database Search (beta)](https://www.usbg.gov/plant-database-search-beta) |
| Garden Explorer | [usbg.gardenexplorer.org](https://usbg.gardenexplorer.org/) |
| Science & Conservation | [Science & Conservation](https://www.usbg.gov/science-conservation) |
| Education | [Education Programs](https://www.usbg.gov/learn/education) |

## Artifacts

### JSON Schema

- [usbg-plant-schema.json](json-schema/usbg-plant-schema.json) — JSON Schema for USBG Living Collections plant specimen records.

### JSON Structure

- [usbg-plant-structure.json](json-structure/usbg-plant-structure.json) — Structure documentation for USBG plant collection fields.

### JSON-LD Context

- [united-states-botanic-garden-context.jsonld](json-ld/united-states-botanic-garden-context.jsonld) — Linked data context aligning USBG plant collection vocabulary with Darwin Core (DwC), schema.org, and conservation ontologies.

### Vocabulary

- [united-states-botanic-garden-vocabulary.yml](vocabulary/united-states-botanic-garden-vocabulary.yml) — Domain vocabulary covering plant taxonomy, living collections management, conservation biology, and botanic garden concepts.

## Notes

The United States Botanic Garden does not operate a public REST API. Plant collection data is accessible through the Garden Explorer web interface and the Plant Database Search tool. Data consumers interested in botanical data APIs may find relevant resources through GBIF (Global Biodiversity Information Facility), BGCI (Botanic Gardens Conservation International), and the USDA PLANTS Database.

**Maintained by:** [API Evangelist](https://apievangelist.com)
