# Log

Append-only history of ingests and edits. One entry per event, newest at the bottom.

## [2026-06-24] init | Bundle instantiated

Created the OKF wiki bundle on running: schema (`CLAUDE.md`), README, master index, and the typed-subdirectory layout (`sources/`, `concepts/`, `techniques/`, `nutrition/`, `gear/`, `metrics/`). Seeded the first round of evidence-graded pages across physiology, training, nutrition, gear, and recovery.

## [2026-06-24] ingest | Marius Bakken on the Norwegian Method (Science of Running, 2026)

Added source page for the Science of Running interview and a new Concept page `concepts/muscle-tone.md` (evidence: weak) covering Bakken's "muscle tone" framework and its relation to durability. Cross-linked from `concepts/durability.md` and `techniques/double-threshold.md`.

## [2026-06-24] seed | First content build

Seeded the bundle from four evidence-research sweeps (physiology and training; super-shoes and foam; nutrition and ergogenic aids; rest and recovery) plus two follow-ups (wearable-metric accuracy and the Canova method; the broader training-philosophy landscape). Wrote 7 concept pages, 12 technique pages, 14 nutrition pages, 6 gear pages, 8 recovery pages, 7 entity pages, and a `the-basics` landing page, all evidence-graded and citing 152 source pages. Added the `entities/` directory and updated the schema to record the real layout (`recovery/`, `entities/`; `Metric` type reserved). Added `the-basics` per a user request to foreground the 95%ers, and people pages including Iglói.

## [2026-06-24] expand | Depth pass and new pages

Began deepening pages beyond thin summaries, starting with `concepts/vo2max.md` as the depth exemplar (added measurement methods, a method-comparison table, test accuracy, and lab versus FirstBeat/wearable estimation). Added two new pages: `gear/heart-rate-monitors.md` (accuracy by sensor type) and `concepts/lactate-testing.md` (lab and finger-prick testing). Expanded `nutrition/hydration-and-electrolytes.md` with dietary-salt adequacy and when supplementation is actually warranted; `nutrition/creatine.md` with the strength-training case; `gear/carbon-plate.md` with the plate's foam-loading role; `gear/gps-watches-and-metrics.md` with a read-the-manual usage section; and `techniques/polarised-training.md` with a caveat on the "Zone 2" naming clash. Added seven source pages.

## [2026-06-24] expand | Physiology cluster deepened

Brought the physiology cluster to the depth standard set by `concepts/vo2max.md`: rewrote `lactate-threshold.md` (what lactate is, the competing threshold definitions, training, the %VO₂max nuance), `running-economy.md` (energy vs oxygen cost, measurement and variability, determinants, what improves it), and `durability.md` (assessment by pre/post testing and decoupling, what trains it). Added source pages for running-economy and durability measurement.

## [2026-06-24] style | Quartz callouts pass

Added a standard evidence callout below the H1 of all 56 claim-bearing pages (concepts, techniques, nutrition, gear, recovery, entities), mapped from the `evidence:` grade: strong → success, moderate → info, limited/cautionary → warning, weak → danger, contested → question; entities without a grade use an info "Coach/Scientist" banner. Uses Obsidian/Quartz callout syntax so the bundle renders cleanly when published via Quartz. The polarised, antioxidant and cold-water-immersion banners use a cautionary type where the page's thrust warrants it.

## [2026-06-24] expand | Potential-vs-performance framing and broader callouts

Added the "a high VO₂max is a ceiling, not a result" distinction to `concepts/vo2max.md` (a high engine still has to be trained into performance) and applied the same necessary-but-not-sufficient framing as callouts to `running-economy.md`, `gear/super-shoes.md` and `techniques/strength-training-for-runners.md`. Broadened callouts beyond evidence banners: added tip, example and warning callouts (practical sessions, worked examples, common mistakes, dosing, decision rules) across the training, nutrition, gear and recovery clusters.

## [2026-06-24] expand | Training, nutrition, gear, recovery clusters deepened

Brought the remaining clusters toward the physiology depth standard with practical-application sections: interval sessions and common mistakes; long-run, base-building, heat-acclimation and double-threshold how-to; periodisation default and a worked taper; volume-vs-intensity application; Canova session example; marathon fuelling, carb-loading and caffeine worked examples; bicarbonate, iron and nitrate practical cautions; a daily protein target; shoe rotation; sleep hygiene; cold-water-immersion decision rule; overtraining warning signs.

## [2026-06-24] add | New pages, injury prevention, manual index

Added `techniques/fartlek.md`, `techniques/workout-types.md` (a map of run types) and `concepts/running-for-beginners.md`. Added an injury-prevention section to `strength-training-for-runners.md` with the Lauersen 2018 meta-analysis (strength training roughly halves overuse-injury risk), a new source page. Deepened the nutrition cluster further: full how-to and verdict sections on `beta-alanine.md`, food-first and exception sections on `antioxidant-supplements.md`. Wired the new pages into the concepts, techniques and master indexes. Regenerated `sources/index.md` by hand (the command classifier being unavailable) to add this session's new source pages.

## [2026-06-24] add | Recovery devices, stretching, adaptations, intermediate guide

Added `recovery/stretching.md` (stretching does not prevent overuse injury; more flexibility is not better), `recovery/foam-rolling.md`, `recovery/massage-guns.md` and `recovery/compression-boots.md` (graded honestly as mostly perceptual). Added `concepts/physiological-adaptations.md` covering tissue-adaptation timelines (cardiovascular fast, muscle weeks-months, tendon and bone months) and why the mismatch causes "too much too soon" injuries, and `concepts/running-for-intermediates.md`. Regraded `recovery/sleep.md` and `techniques/base-building.md` from moderate to strong on user feedback, since the importance of sleep and of a consistent aerobic base is strongly evidenced even where the sub-claims (extension magnitude, optimal volume) are less certain. Added six source pages and wired everything into the indexes by hand.

## [2026-06-24] style | Removed self-reference and figurative tics

Removed self-referential meta-narration from content pages (phrasings such as "run through this wiki", "this page exists to", "kept here", "centre of gravity", "this page records") flagged as breaching the clear-writing house style, rewording each to carry content instead. Fixed figurative tics ("it bites", "rewards patience and punishes haste") and a banned "not X, it is Y" construction. CLAUDE.md and README legitimately describe the bundle and were left.

## [2026-06-24] grade | Volume-vs-intensity regraded

After the sleep and base-building regrades, reviewed all evidence grades and corrected `techniques/training-volume-vs-intensity.md` from moderate to strong, since its headline (volume drives performance) is the same well-evidenced claim as base-building. Other moderates left as genuinely moderate at the headline level.

## [2026-06-24] add | Shoes, barefoot, plyometrics, massage

Added `gear/running-shoes.md` (comfort and rotation over the pronation-and-arch model), `gear/barefoot-running.md` (changes mechanics, no proven injury or performance benefit), `techniques/plyometrics.md` (elastic energy return for economy) and `recovery/massage.md` (manual and sports massage, mostly perceptual). Added three source pages and wired everything into the indexes by hand.

## [2026-06-24] add | Muscle/cardio/respiratory physiology, and evidence corrections

Added three physiology pages on training adaptation: `concepts/energy-systems.md`, `concepts/muscular-adaptations.md` (mitochondria, capillarisation, oxidative enzymes, fat oxidation) and `concepts/cardiovascular-and-respiratory-adaptations.md` (heart and blood drive VO₂max; the lungs rarely limit healthy runners). Corrected `cold-water-immersion.md` and `recovery-modalities.md`: CWI clearly blunts strength/hypertrophy adaptation, but the endurance-adaptation evidence is equivocal, so the common "ice baths wreck running adaptation" claim was overstated; CWI demoted in the modalities ranking. Expanded `lactate-testing.md` on its directional nature and day-to-day confounders (diet, heat, fatigue, caffeine, sampling). Added a trigger-points section to `massage.md` (the "knot" model is poorly validated; localised pressure still gives acute relief). Wove the volume-enabling thesis into `barefoot-running.md` and `running-shoes.md`: improvement comes from training more, so tools that reduce injury and enable volume are net good, and barefoot running fails this test. Added six source pages.

## [2026-06-24] add | Glycogen page; nitrate funding scrutiny

Added `concepts/glycogen.md` (stores, depletion and "the wall", loading, in-race fuelling, sparing through training, train-low). Reworked `nutrition/dietary-nitrate.md` to drop the overstated "well researched" framing and add a "Research quality and who funds it" section: nitrate is heavily studied but in small, young, recreational, male samples with modest, conditional effects, and the performance literature is concentrated in the University of Exeter group, which has an openly acknowledged commercial relationship with Beet It (James White Drinks), maker of the standard research shot. Two source pages added (umbrella review; the Exeter–Beet It link). Wired glycogen into the indexes and the carbohydrate pages.

## [2026-06-24] add | Nomio, supplement-scrutiny framework, tightness-and-strength link

Added `nutrition/nomio-broccoli-shots.md` (broccoli-sprout isothiocyanate shots: plausible NRF2 mechanism, heavy elite hype, no published performance evidence; same Karolinska/GIH-to-commercial pattern as nitrate) and `nutrition/evaluating-supplements.md`, a framework page applying consistent scrutiny to every supplement claim (who funded it, study quality, biomarker-versus-performance, elite adoption as a weak signal, contamination), linked from the supplement hubs. Added a "tightness as information" section to `massage.md` connecting chronic tightness to a possible weak link and the case for strength work over repeated massage. Two source pages added.

## [2026-06-24] lint | Full health check

Ran the full OKF lint checklist over 266 files (181 sources, 75 content pages). Zero broken internal links; frontmatter conformant throughout (every page has a valid `type`, every claim page an `evidence` grade, all timestamps ISO); zero orphans; every source page cited by at least one content page; all directory indexes complete and master-index links resolving. Fixed the only finding, four pages reachable only via an index, by adding prose cross-links: `stephen-seiler` from polarised-training, `renato-canova` from canova-method, `plyometrics` from strength-training, and `running-for-intermediates` from running-for-beginners. Contradictions, stale claims and duplicate facts reviewed by hand: none outstanding.

Ran the OKF lint checklist. Fixed one missing source page (`maunder-2021-durability`, cited by durability and muscle-tone) and wired two orphan sources (`san-millan-2018`, `hottenrott-2012-volume`) into the training-philosophies page. Result: zero broken internal links, every page carries `type`, every claim page carries `evidence`, no orphan pages, every source page cited by at least one content page, and all directory indexes complete. One link in `CLAUDE.md` is an intentional syntax example, not a navigational link.

## [2026-06-24] red-team | Claim audit and corrections

Ran an adversarial accuracy pass over every claim-bearing page, checking each load-bearing claim against the primary literature and against its own cited source, with fresh web research where a corrected claim needed new provenance. No fabricated facts and no unsafe dosing advice were found; the defects were overclaims of precision, single small studies presented as general laws, and a few evidence grades that outran the page body. Corrections made:

- **Fabricated citation removed.** `gear/heart-rate-monitors.md` cited a non-existent "Hettiarachchi et al. 2019" (the link pointed at the unrelated Zhang 2020 optical-HR meta) for the chest-strap accuracy claim. Replaced with a verified anchor, new source `schaffarczyk-2022-polar-h10.md` (Polar H10 vs criterion ECG).
- **Heat acclimation rewritten.** The cool-condition VO₂max/time-trial benefit from `lorenzo-2010-heat` is contradicted by better-controlled work; reframed the page so the robust claims (plasma-volume expansion, thermoregulation, benefit in the heat) carry the case and the cool-condition transfer is flagged contested. Corrected the Lorenzo source (journal, sample) and added `keiser-2015-heat`, `mikkelsen-2019-heat`, `tyler-2016-heat-meta`.
- **Super-shoes.** Reframed the Alda-Blanco 2025 muscle-damage null (it compared two super-shoe models, so it cannot rebut the super-vs-conventional recovery claim) and gave the previously uncited "~1% per 100 g" shoe-mass figure a proper anchor, new source `hoogkamer-2016-shoe-mass.md`.
- **Strength training.** Resolved the internal contradiction (`strong` + "best-evidenced applied topic" vs the body's "small, short trials"): separated the well-evidenced economy gain from the weaker performance carry-over, and flagged that the Lauersen injury data are mostly non-runner cohorts.
- **Grades and precision.** Regraded `recovery/sleep.md` strong→moderate and `recovery/compression-boots.md` moderate→limited (sibling consistency). Softened single-study precision on volume (Casado r=0.75), detraining (Coyle 7%/12-day), tapering magnitude, and the HERITAGE heritability (upper-bound estimate) across vo2max, individual-variation, base-building and the-basics.
- **Other claim fixes.** Durability now labels the fatigue figure as LT1 (not generic threshold); the Seiler 2006 sample is correctly given as 11 junior skiers on the Seiler and polarised pages; the polarised "80/20 is time not sessions" claim softened to acknowledge both measures; the Iglói "49 world records" hedged as a reported, era- and category-mixed tally; caffeine's false-precise "6% RPE" and "9 mg/kg ceiling" corrected; the muscle fibre-type claim narrowed to IIX→IIA. Verified Jack Daniels' 1933–2025 dates (correct; left as is).

Added five source pages and registered them in `sources/index.md`.

## [2026-06-24] add | Altitude training

Added `techniques/altitude-training.md` (evidence: contested), filling a notable gap: the bundle previously had no altitude page despite the topic's prominence. The page is honest about the split in the literature: the EPO-to-haemoglobin-mass mechanism and the ~1.1%/100 h dose-response are well established, but the sea-level performance benefit in trained runners is contested, with a placebo-controlled trial (Siebenmann 2012) finding nothing against the positive meta-analysis (Bonetti & Hopkins 2009) and the sceptics' review (Lundby & Robach 2016). Covers the three models (LHTL best-supported, LHTH and live-low-train-high weaker), the ~2,000-2,500 m living window, responders/non-responders being an unreliable label, and the iron prerequisite. Per the bundle's editorial stance, gave the near-universal elite adoption its own "smoke where there may be fire" treatment, weighed as a signal but not as proof, with an explicit parallel to sodium bicarbonate. Flagged the "train low" naming clash with the carbohydrate sense. Added eight source pages, wired the page into the techniques and master indexes, cross-linked it from heat-acclimation, and softened the heat-acclimation index entry to match its contested cool-condition claim.

## [2026-06-24] expand | Coverage-gap build: injury, female athlete, and 20 more pages

Filled the two largest holes a gap audit surfaced (injury and health; the female athlete) plus a long tail of missing training, physiology and lifestyle topics. Added 25 content pages and roughly 80 new source pages, built by five research-and-draft passes and reviewed for house style and citation integrity. New material: a new `injury/` directory (`running-injuries`, `bone-stress-injuries`, `tendinopathy`, `common-overuse-injuries`) with its own index; the female-athlete and energy cluster (`nutrition/red-s`, `concepts/the-female-runner`, `concepts/menstrual-cycle-and-training`, `nutrition/body-composition-and-weight`, `nutrition/disordered-eating`, `nutrition/vitamin-d-and-calcium`); training methods (`techniques/race-pacing`, `hill-training`, `warm-up-and-cool-down`, `distance-specific-training`, `nutrition/gut-training`); physiology and populations (`concepts/biomechanics-and-gait`, `fatigue-mechanisms`, `anaerobic-capacity-and-speed-reserve`, `masters-runners`); and health and lifestyle (`concepts/running-and-health`, `concepts/heat-illness`, `recovery/sauna`, `stress-and-life-load`, `travel-and-jet-lag`, `active-recovery`). Grades reflect the evidence honestly: strong for RED-S and tendon loading rehab, contested for the menstrual-cycle and running-and-health pages, limited for sauna and jet lag.

Per a user instruction, added a standard `Not medical advice` warning callout to all injury pages, all nutrition pages, and the medical concept pages (heat illness, running and health), directing readers to a doctor, physiotherapist or registered dietitian; documented the convention in `CLAUDE.md` and registered the new `injury/` directory in the schema. Fixed three source slugs whose filenames did not match their actual authors (renamed to `mancine-2020-disordered-eating-prevalence`, `mountjoy-2018-ioc-reds`, `pluim-athletes-heart`). Regenerated `sources/index.md` by domain (now 281 entries with a new Injury section) and wired every new page into its sub-index and the master index. Final link check across 394 files: zero broken internal links (bar the intentional CLAUDE.md syntax example) and zero uncited source pages.

## [2026-06-24] red-team | Full content red-team, corrections and 30-page coverage build

Ran a six-front content red-team across every category (physiology, training, nutrition, gear, recovery, injury, entities) plus a cross-cutting integrity audit. The bundle's structure held up: zero broken links, zero orphans, no index drift, universal evidence-field and medical-callout coverage. The findings were concentrated in a few accuracy slips, some evidence grades that outran their own prose, one real provenance defect, and genuine content-breadth gaps.

Provenance and accuracy corrections:

- **Misattributed citation fixed.** The LEA/RED-S–bone source was a fabricated "Jeukendrup et al. 2024"; the real paper is Gallant et al. 2024 (*Sports Medicine*, PMID 39485653). Renamed the source to `gallant-2024-lea-reds.md`, corrected five in-text citations (bone-stress, red-s, disordered-eating, body-composition) and the source index, and deleted the bad file. Verified Jack Daniels' 1933–2025 dates (correct; died 12 Sept 2025).
- **Mislabelled orthoses source.** `bonanno-2018-orthoses.md` (PMID 28935689) is actually Whittaker et al. 2018 on plantar heel pain, and it carried a prevention overclaim belonging to Bonanno 2017. Renamed to `whittaker-2018-plantar-orthoses.md`, scoped to plantar heel pain, and split the prevention claims onto `bonanno-2017-orthoses-prevention.md` across the plantar, common-overuse and insoles pages.
- **Claim fixes.** 800 m corrected from "even split" to ~60–65% aerobic (energy-systems); the VO₂max plateau reworded to reflect that it is often absent and the verification phase is the genuine confirmation; the tendon ≤5/10 pain rule re-cited from a bone-stress paper to its real source (new `silbernagel-2007-pain-monitoring.md`); the ITB foam-rolling claim re-grounded on what Fairclough actually showed; the high-risk fifth-metatarsal site corrected to the Jones-zone diaphysis; the ACWR/single-session claim softened to match a contested literature; strength-training economy range corrected to a typical 2–4%; the race-pacing cost-of-variability and 800 m positive-split claims softened; the carb-loading internal number and a mislinked cross-reference fixed.
- **Evidence grades recalibrated** to match each page's headline claim: the-long-run moderate→limited, running-and-health contested→strong (longevity), sleep moderate→strong (deprivation), barefoot-running contested→limited; durability kept at moderate by reasoning. Added the missing "Not medical advice" callout to menstrual-cycle-and-training.

Reinforcing the basics (per user steer): rewrote `concepts/the-basics.md` with an explicit "order of returns" (consistency, volume, sleep, fuelling, a little hard work, then the last few per cent), and threaded a consistent "keep it in proportion" callout pointing back to it into 14 marginal pages (recovery gadgets, hyped or weak supplements, vanity-metric gear).

Coverage build: added 30 new content pages with verified sources (every new citation confirmed by author/DOI against PubMed or the publisher before use). Training: threshold-and-tempo-training, cross-training, return-to-running, strides-and-drills, training-load-management, ultra-and-trail-training. Nutrition: daily-carbohydrate-and-energy, pre-race-fuelling, recovery-nutrition (which also answers whether intra-workout carbohydrate aids recovery), low-carbohydrate-and-keto, carbohydrate-periodisation, collagen-and-vitamin-c, alcohol, omega-3. Injury: patellofemoral-pain, plantar-fasciopathy, achilles-tendinopathy, muscle-strains, injury-prevention, practical-niggles (splitting the most prevalent injuries out of the single bundled page). Physiology: critical-speed-and-power, fat-oxidation-and-metabolic-flexibility, thermoregulation, vo2-kinetics, pregnancy-and-postpartum-running, youth-running. Gear: trail-running-shoes, insoles-and-orthotics. Recovery: naps, blood-flow-restriction. Added a concrete evidence-led lifts section to strength-training-for-runners.

Ran a clear-writing QA pass over all 30 new pages (removed em dashes, meta-narration and self-reference leaks, figurative tics, rule-of-three and American spellings), wired every page into its sub-index and the master index, and ran a full link check: zero broken internal links bar the intentional CLAUDE.md syntax example.
