# Everything I Know — Running

An evidence-based knowledge base on distance running, built as an [Open Knowledge Format](https://cloud.google.com/blog/products/data-analytics/how-the-open-knowledge-format-can-improve-data-sharing) (OKF) wiki: a directory of markdown files, one concept per file, cross-linked into a graph, following the [LLM-wiki pattern](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

The bias is deliberate: heavy on the methods that move the needle for most runners, light on the marginal and the marketing. Every empirical claim is graded for evidence quality and cited at the point it is made.

## How to read it

Start at [index.md](index.md), the master catalogue, or jump straight to [the basics](concepts/the-basics.md) for the short version of what actually matters. Navigate by the per-directory index files.

The knowledge is organised by type:

- [concepts/](concepts/index.md) — physiology and theory (VO₂max, lactate threshold, running economy, durability)
- [techniques/](techniques/index.md) — training and practice (volume, intervals, tapering, the major training philosophies)
- [nutrition/](nutrition/index.md) — food, supplements and ergogenic aids, graded honestly
- [gear/](gear/index.md) — super-shoes, foams, plates, and how to read GPS-watch metrics
- [recovery/](recovery/index.md) — sleep, overtraining, recovery modalities, monitoring
- [entities/](entities/index.md) — the coaches and scientists behind the methods
- [sources/](sources/index.md) — provenance anchors for every claim

## Evidence grading

Each claim-bearing page carries an `evidence:` field in its frontmatter:

| Grade | Meaning |
| --- | --- |
| `strong` | consistent RCTs, meta-analyses or consensus statements; safe to act on |
| `moderate` | several supporting studies, with caveats |
| `limited` | thin, preliminary or mixed support |
| `weak` | little credible support; marketed beyond the evidence |
| `contested` | genuine disagreement in the literature |

Poorly evidenced topics get a page so a reader can find an honest account of *why* they are poorly evidenced, with a prominent caveat, rather than being left to the marketing. Where elites adopt something ahead of the literature (sodium bicarbonate is the standing example), that adoption is noted as a signal worth weighing, not as proof.

## Conventions and maintenance

The schema, type vocabulary and house rules live in [CLAUDE.md](CLAUDE.md). The bundle is maintained with the `okf-wiki` skill; all prose is written under the `clear-writing` skill. [log.md](log.md) records the history of changes.

To add or correct something, see [CONTRIBUTING.md](CONTRIBUTING.md). In short: keep it non-commercial, no affiliate links, no brand promotion, source every claim, and the more outlandish the claim the more careful the sourcing.

This is a personal knowledge base, not medical or coaching advice. People respond differently to training and to products; treat even well-evidenced claims as a starting point to test on yourself.
