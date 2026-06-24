# Schema: Everything I Know — Running

This repository is an Open Knowledge Format (OKF v0.1) wiki bundle on distance running, with a deliberate bias toward methods that are real, science-based, and evidence-backed. It follows the LLM-wiki pattern: a directory of markdown files, one concept per file, the file path as the concept's identity, with YAML frontmatter and a markdown body. Cross-links between files form the graph.

The bundle is maintained with the `okf-wiki` skill. All prose is written under the `clear-writing` skill (plain, direct, British English, every load-bearing claim cited at the point of use).

## Editorial stance

Heavy on the things that move the needle for most runners; light on the marginal and the marketing. A page exists for a poorly-evidenced topic only so a reader can find an honest account of *why* it is poorly evidenced, with a prominent caveat. Where professionals and elites adopt something ahead of the literature (sodium bicarbonate is the standing example), that adoption is noted as a signal worth weighing, not as proof.

Every empirical claim cites a source at the point it is made. No claim enters the wiki without provenance back to a source page.

## Type vocabulary

The `type` frontmatter field is required. Use only these values:

- `Source` — an ingested document: a paper, review, consensus statement, book, article, or talk.
- `Concept` — a physiological or theoretical idea (VO₂max, lactate threshold, running economy, durability).
- `Technique` — a concrete training or practice method (polarised training, the long run, carb-loading, tapering).
- `Substance` — anything ingested for performance or health (caffeine, nitrate, sodium bicarbonate, iron, ketones).
- `Gear` — equipment (super-shoes, foams, carbon plates).
- `Metric` — a defined, measurable quantity (VO₂max value, HRV, running economy in ml/kg/km).
- `Entity` — a named person, body, or brand, only where it earns its own page.

Do not invent types. If a source needs a type the bundle lacks, propose adding it here first.

## Evidence grading (bundle-specific field)

Every claim-bearing page (Concept, Technique, Substance, Gear, Metric) carries an `evidence:` frontmatter field. This makes the editorial stance structural rather than buried in prose. Values:

- `strong` — consistent findings from multiple RCTs, meta-analyses, or consensus statements. Safe to act on.
- `moderate` — supported by several studies but with caveats: smaller effects, heterogeneity, or population limits.
- `limited` — some supporting evidence, but thin, preliminary, or mixed.
- `weak` — little credible support; widely believed or marketed beyond what the data justifies.
- `contested` — genuine disagreement in the literature, or a claim that is being actively superseded.

A page may grade individual claims differently in the body; the frontmatter value reflects the page's headline claim.

## Directory layout

```
/
├── index.md            # master catalogue, navigate from here
├── log.md              # append-only history of ingests and edits
├── CLAUDE.md           # this file
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

Each subdirectory has its own `index.md`. The `Metric` type is reserved for future use; measured quantities currently live inside the relevant Concept and Gear pages. Recovery and rest material is grouped under `recovery/` for navigability even though individual pages carry the `Technique` or `Concept` type. Injury and musculoskeletal-health material is grouped under `injury/` on the same basis.

## Conventions

- **Cross-links** use ordinary relative markdown links, e.g. `[running economy](../concepts/running-economy.md)`.
- **Citations** are inline links at the point of the claim, pointing to the source page under `sources/`, which in turn links to the raw source. Provenance runs both ways.
- **Slugs** are kebab-case, descriptive, stable. The file path is the concept's identity, so renaming is a deliberate act with link updates.
- **Supersede, never delete.** When a newer source overturns a claim, keep the old claim with a dated marker and add the new one.
- **Timestamps** are ISO 8601 (`YYYY-MM-DD`).
- **Tags** group by domain (`physiology`, `training`, `nutrition`, `recovery`, `gear`, `injury`) and may add an evidence tag where useful.
- **Not-medical-advice notice.** Every page that touches health, injury, or anything ingested (all `injury/` pages, all `nutrition/` pages, and medical concept pages such as heat illness and cardiac health) carries a standard `> [!warning] Not medical advice` callout directly below the evidence callout, telling the reader to consult a doctor, physiotherapist or registered dietitian. This is a general knowledge base, not clinical advice.

## Maintenance

Three operations, all via the `okf-wiki` skill: ingest a source, query the compiled wiki, lint for health. The model proposes a plan; the human approves before writes land.
