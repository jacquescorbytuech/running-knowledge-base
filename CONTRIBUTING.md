# Contributing

This is an evidence-based knowledge base on distance running, published at [running.wiki](https://running.wiki). Contributions are welcome, provided they keep it that way. The rules below exist to protect the one thing that makes it worth reading: every claim is traceable to a source, and the editorial line answers to the evidence rather than to anyone's commercial interest.

This file is the full guide to how the knowledge base is written: the editorial stance, the page types, the evidence grades and the house style. (`CLAUDE.md` is a short operational brief for the AI assistant used to maintain the bundle, and points back here for the rules.)

## Editorial stance

Heavy on the things that move the needle for most runners; light on the marginal and the marketing. A poorly-evidenced topic earns a page only so a reader can find an honest account of *why* it is poorly evidenced, with a prominent caveat, rather than being left to the marketing. Where professionals and elites adopt something ahead of the literature (sodium bicarbonate is the standing example), that adoption is noted as a signal worth weighing, not as proof.

## The non-negotiables

**Keep it non-commercial.** This is a reference, not a shopfront. Contribute because you want the knowledge to be accurate, not because you stand to gain from what a reader does next. Anything written to drive a sale, a sign-up, a click or a referral does not belong here, however well dressed.

**No affiliate links.** No tracking parameters, no referral codes and no monetised redirects, anywhere in the bundle: not in citations, not in body prose, not in source pages. Link to the primary source directly. If you find an affiliate link already in the bundle, removing it is a welcome contribution.

**No promotion of individual brands.** Name a product only where the named product *is* the evidence: a specific super-shoe in the study that measured it, a specific supplement in the trial that tested it. State what the research found and cite it. Do not rank brands, recommend a purchase, or carry a brand's marketing claim as though it were a finding. A `Gear` or `Substance` page describes a category and what the literature says about it; it is not a buyer's guide.

**Keep the sourcing.** Every empirical claim cites a source at the point it is made, as an inline link to a page under [sources/](sources/index.md), which in turn links to the primary material. No claim enters the wiki without that chain of provenance running both ways. If you cannot source a claim, either leave it out or flag it explicitly as folklore, with the absence of evidence stated plainly.

**The more outlandish the claim, the more careful the sourcing.** Extraordinary claims need extraordinary evidence. A surprising, counter-intuitive, or strongly-stated assertion needs better support than a mundane one: ideally multiple studies, a meta-analysis, or a consensus statement rather than a single small trial, a press release, or a podcast. Match the [evidence grade](#evidence-grading) in the frontmatter to the real strength of the support. Where professionals adopt something ahead of the literature, label it as a signal worth weighing, not as proof.

## Page types

Every page declares a `type` in its frontmatter. Use only these values:

- `Source` — an ingested document: a paper, review, consensus statement, book, article or talk. Source pages live in [sources/](sources/index.md) and anchor every claim.
- `Concept` — a physiological or theoretical idea (VO₂max, lactate threshold, running economy, durability).
- `Technique` — a concrete training or practice method (polarised training, the long run, carb-loading, tapering).
- `Substance` — anything ingested for performance or health (caffeine, nitrate, sodium bicarbonate, iron, ketones).
- `Gear` — equipment (super-shoes, foams, carbon plates).
- `Metric` — a defined, measurable quantity (a VO₂max value, HRV, running economy in ml/kg/km). Reserved for now; measured quantities currently live inside the relevant Concept and Gear pages.
- `Entity` — a named person, body or brand, only where it earns its own page.

Do not invent types. If something needs a type the bundle lacks, propose adding it here first.

## Evidence grading

Every claim-bearing page (Concept, Technique, Substance, Gear, Metric) carries an `evidence:` field in its frontmatter, so the editorial stance is structural rather than buried in prose. The value reflects the page's headline claim; the body may grade individual claims differently. The occasional editorial or meta page, one about the practice of the field rather than an empirical claim (such as [the marketing playbook](nutrition/the-marketing-playbook.md)), may omit the grade and carry a plain callout in place of the evidence banner.

| Grade | Meaning |
| --- | --- |
| `strong` | consistent findings from multiple RCTs, meta-analyses or consensus statements; safe to act on |
| `moderate` | supported by several studies but with caveats: smaller effects, heterogeneity or population limits |
| `limited` | some supporting evidence, but thin, preliminary or mixed |
| `weak` | little credible support; widely believed or marketed beyond what the data justifies |
| `contested` | genuine disagreement in the literature, or a claim being actively superseded |

The evidence callout at the top of each claim-bearing page renders the grade with a fixed icon, so the colour signals the grade and nothing else: `strong → [!success]`, `moderate → [!info]`, `limited → [!info]`, `weak → [!danger]`, `contested → [!question]`. Do not reach for `[!warning]` on the evidence callout to flag a risky or over-marketed topic; that caution belongs in a separate body callout (a `[!warning]`, or the standard `> [!warning] Not medical advice` notice), never in the headline grade.

## House style and conventions

- **One concept per file.** The file path is the concept's identity. Add a new page for a genuinely novel concept; otherwise extend the existing one. Slugs are kebab-case, descriptive and stable, so renaming is a deliberate act that also updates every link.
- **Write under the house style.** Prose is plain, direct, British English, with every load-bearing claim cited at the point of use. The `clear-writing` skill enforces this; match the surrounding pages.
- **Cite at the point of use.** Citations are inline links at the point of the claim, pointing to a page under [sources/](sources/index.md), which in turn links to the primary material. Provenance runs both ways. Cross-links between pages use ordinary relative markdown links, e.g. `[running economy](../concepts/running-economy.md)`.
- **Supersede, never delete.** When newer evidence overturns a claim, keep the old claim with a dated marker and add the new one. The bundle preserves what was believed and when. Timestamps are ISO 8601 (`YYYY-MM-DD`).
- **Carry the warnings.** Every page that touches health, injury or anything ingested (all [injury/](injury/index.md) pages, all [nutrition/](nutrition/index.md) pages, and medical concept pages such as heat illness and cardiac health) carries a standard `> [!warning] Not medical advice` callout directly below the evidence callout, pointing the reader to a doctor, physiotherapist or registered dietitian. This is a general knowledge base, not clinical advice. Keep it.
- **Tag by domain.** Tags group by domain (`physiology`, `training`, `nutrition`, `recovery`, `gear`, `injury`) and may add an evidence tag where useful.
- **Update the plumbing.** A change that adds or moves a page also updates the relevant `index.md` files and appends a dated entry to [log.md](log.md).

## Raising a change

Open an issue or a pull request describing what you are changing and why. For a new or contested claim, lead with the source. Changes that strengthen sourcing, correct an error or remove commercial creep are the easiest to accept; changes that assert without evidence are the easiest to decline.
