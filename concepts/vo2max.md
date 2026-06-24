---
type: Concept
title: VO₂max
description: The ceiling of aerobic energy production, what it predicts, how it is measured by lab, field and wearable methods, and how far to trust each number.
tags: [physiology]
evidence: strong
timestamp: 2026-06-24
---

# VO₂max

> [!success] Evidence: strong
> A real determinant of endurance performance, but routinely over-claimed, and only as trustworthy as the method that measured it.

VO₂max is the maximal rate at which the body can take up and use oxygen during exercise to exhaustion. It sets the ceiling on aerobic ATP production and is one of the three classical physiological determinants of distance-running performance, alongside [lactate threshold](lactate-threshold.md) and [running economy](running-economy.md) ([Joyner & Coyle 2008](../sources/joyner-coyle-2008.md); [Bassett & Howley 2000](../sources/bassett-howley-2000.md)).

It is the most over-claimed of the three. VO₂max correlates strongly with performance across a mixed-ability field, where values range widely, but its power to separate runners collapses within a group of similar ability, because their values cluster ([Farrell et al. 1979](../sources/farrell-1979.md); [Joyner & Coyle 2008](../sources/joyner-coyle-2008.md)). Among trained runners, velocity at lactate threshold and running economy discriminate better. Treating VO₂max as the single master number is a common error.

## Potential, not performance

> [!warning] A high VO₂max is a ceiling, not a result
> A big aerobic engine sets how fast you *could* run once trained. It does not make you fast on its own, and an untrained person with a high VO₂max cannot simply go and run a quick time.

VO₂max describes how much oxygen the body could use, not the ability to turn that into race pace. Realising it depends on the other determinants, which are built by training and barely exist in someone untrained: [running economy](running-economy.md), the fraction of VO₂max sustainable at [lactate threshold](lactate-threshold.md), [durability](durability.md) over the distance, pacing judgement and sport-specific neuromuscular skill. Someone with a naturally high VO₂max who has not trained would run wastefully, be unable to hold a high fraction of their ceiling, and fade badly late on, because those abilities are trained, not given.

This is the same fact seen from two sides. It is why VO₂max barely discriminates between [trained runners](individual-variation.md), whose values cluster while their performances do not, and why the [integrated model](running-economy.md) *multiplies* VO₂max by the other determinants rather than treating it alone. A trained runner with a modest VO₂max routinely beats an untrained one with a high VO₂max. VO₂max raises the lid on what training can achieve; it does not do the training, and a high test result is a reason to train, not a substitute for it.

## How it is measured

The number is only as good as the method that produced it, and the methods differ by an order of magnitude in accuracy.

**Laboratory direct measurement (the gold standard).** A graded exercise test to exhaustion on a treadmill or cycle, with expired air analysed breath by breath by a metabolic cart, or collected in Douglas bags, the historical reference method. A genuine maximum is confirmed by criteria: a plateau in oxygen uptake, conventionally a rise of less than about 100 ml/min despite an increase in workload, supported by secondary criteria such as a respiratory exchange ratio above roughly 1.10, a heart rate near the age-predicted maximum, and a high rating of perceived exertion ([Poole et al. 2020](../sources/frontiers-2020-vo2max-testing.md)). The plateau is the classical primary criterion and the others are corroborating, but a clear plateau is frequently absent and is not reliably reproducible, so a separate verification phase, a second exhaustive bout confirming the value cannot be exceeded, is increasingly treated as the genuine confirmation rather than the plateau itself.

Even this is not error-free. Validation of modern metabolic carts against simulators and Douglas bags puts the measurement error of the equipment itself at a few per cent, around 3.5% for one common laboratory cart ([COSMED reassessment 2025](../sources/cosmed-2025-metabolic-cart.md)). Combined biological and technical variation in repeat testing is around 5 to 6%, and the great majority of that is real day-to-day biological variation, not instrument error. A change smaller than that is within the noise.

**Submaximal laboratory estimates.** Tests such as the Åstrand cycle protocol predict VO₂max from the heart-rate response to a fixed submaximal load, using the near-linear heart-rate-to-oxygen-uptake relationship. They avoid an exhausting maximal effort, which suits older or clinical populations, but the price is accuracy: correlation with the true value is around 0.85 to 0.90 with a standard error of estimate of roughly 5 to 6 ml/kg/min ([Åstrand nomogram validity](../sources/macsween-2001-astrand-nomogram.md)). They also assume a standard maximal heart rate, which itself varies by around ±10 beats per minute between people.

**Field tests.** The Cooper 12-minute run and the Rockport 1-mile walk estimate VO₂max from distance covered or from walk time and heart rate. They are cheap and need no equipment, but estimates differ significantly from measured values and depend on pacing skill and the population the equation was built on ([Cooper test validity](../sources/cooper-test-validity-2015.md)). Useful for tracking your own change over time, weak for an absolute number.

**Wearable estimates.** Garmin and others derive VO₂max from the relationship between heart rate and running speed using the FirstBeat algorithm: faster running at a lower heart rate implies higher fitness ([FirstBeat VO₂max white paper](../sources/firstbeat-vo2max.md)). The manufacturer states a mean error around 5%. Independent validation is less flattering: overall error around 7 to 8%, valid in moderately trained runners but poor and systematically *underestimating* in the highly trained, where the heart-rate-to-pace relationship flattens ([Engel et al. 2025](../sources/engel-2025-vo2max.md); [Železnik Mežan 2025](../sources/zeleznik-2025-vo2max.md)). Devices tend to overestimate at low fitness and underestimate at high. A chest strap markedly improves the estimate over wrist optical heart rate, because the input is only as good as the heart-rate signal; see [heart-rate monitors](../gear/heart-rate-monitors.md).

| Method | Typical error | Best for |
| --- | --- | --- |
| Lab metabolic cart, max test | ~3.5% device, ~5-6% test-retest | the reference number |
| Submaximal lab estimate | SEE ~5-6 ml/kg/min | clinical and untrained groups |
| Field test (Cooper, Rockport) | large, population-dependent | cheap self-tracking |
| Wearable (FirstBeat) | ~5% claimed, ~7-8% independent, worse in elites | tracking your own trend |

The practical lesson runs alongside the [wearable-metrics](../gear/gps-watches-and-metrics.md) argument: read any estimate as a trend within yourself over time, not as a precise absolute or a way to compare against other people. A wearable VO₂max that ticks up over months is informative; the exact figure is not.

## Trainability and its limits

In sedentary adults, 20 weeks of standardised endurance training raised VO₂max by about 17% on average in the HERITAGE Family Study ([Bouchard et al., HERITAGE](../sources/heritage-family-study.md)). Gains shrink towards zero in already-trained athletes, who are close to their ceiling.

The response to identical training varies enormously between people. HERITAGE recorded individual changes from roughly −5% to +48% on the same programme; genuine low and high responders exist ([Bouchard et al., HERITAGE](../sources/heritage-family-study.md)). As much as half of the variation in trainability is heritable, though that ~47% figure is a maximal estimate that sets an upper bound rather than a precise share. This is the clearest single argument for [individual variation](individual-variation.md) in how runners should train. The training that raises VO₂max most is high-intensity work near the ceiling, which is the rationale for [interval training](../techniques/interval-training.md), though volume builds the supporting peripheral adaptations.

## Typical values

Elite male distance runners sit around 70 to 85 ml/kg/min and run marathons at roughly 75 to 85% of VO₂max ([Joyner & Coyle 2008](../sources/joyner-coyle-2008.md)). The highest recorded values belong to cross-country skiers and cyclists rather than runners, reflecting the larger active muscle mass in those sports. Specific record figures above about 90 ml/kg/min are largely anecdotal and should be treated as such.

## Related

- [Lactate threshold](lactate-threshold.md)
- [Running economy](running-economy.md)
- [Lactate testing](lactate-testing.md)
- [Individual variation and trainability](individual-variation.md)
- [Interval training](../techniques/interval-training.md)
- [GPS watches and metrics](../gear/gps-watches-and-metrics.md)
- [Heart-rate monitors](../gear/heart-rate-monitors.md)
