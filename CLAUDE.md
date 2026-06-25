# Running knowledge base — maintenance brief

This repository is an Open Knowledge Format (OKF v0.1) wiki bundle on distance running, published as a website at [running.wiki](https://running.wiki). It follows the LLM-wiki pattern: a directory of markdown files, one concept per file, the file path as the concept's identity, with YAML frontmatter and a markdown body. Cross-links between files form the graph.

This file is the operational brief for maintaining the bundle. The editorial rules — the stance, the page types, the evidence grades, the callout mapping and the house style — live in [CONTRIBUTING.md](CONTRIBUTING.md) and are authoritative. Read it before writing or editing any page. The bundle is maintained with the `okf-wiki` skill; all prose is written under the `clear-writing` skill.

## Directory layout

```text
/
├── index.md            # site home and catalogue, navigate from here
├── log.md              # append-only history of ingests and edits
├── CLAUDE.md           # this file — maintenance brief
├── CONTRIBUTING.md     # schema, evidence grades and house style (authoritative)
├── README.md           # GitHub front door
├── sources/            # Source pages (provenance anchors)
├── concepts/           # Concept pages (physiology, theory)
├── techniques/         # Technique pages (training, practice)
├── nutrition/          # Substance pages (food, supplements, ergogenic aids)
├── gear/               # Gear pages
├── recovery/           # Recovery and rest pages (techniques and concepts)
├── injury/             # Injury and musculoskeletal-health pages (techniques and concepts)
└── entities/           # Entity pages (coaches, scientists, bodies)
```

Each subdirectory has its own `index.md`. Recovery and rest material is grouped under `recovery/` for navigability even though individual pages carry the `Technique` or `Concept` type; injury and musculoskeletal-health material is grouped under `injury/` on the same basis.

## Maintenance

Three operations, all via the `okf-wiki` skill: ingest a source, query the compiled wiki, lint for health. The model proposes a plan; the human approves before writes land. A change that adds or moves a page also updates the relevant `index.md` files and appends a dated entry to `log.md`.
