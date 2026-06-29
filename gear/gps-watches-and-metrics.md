---
type: Gear
title: GPS watches and metrics
description: What running watches measure well, what they only estimate, and why their numbers are directional trends for one person, not precise absolute truths.
tags: [gear]
evidence: strong
timestamp: 2026-06-24
---

# GPS watches and metrics

> [!success] Evidence: strong
> Read every watch number as a trend within yourself over time, not as a precise absolute or a way to compare with others. Calories and sleep staging are the least trustworthy; the branded "readiness" scores carry false precision.

> [!note] Keep it in proportion
> This is one of the last few per cent, at most. It pays off only once the [basics](../concepts/the-basics.md) are already in place: consistent volume, sleep and adequate fuelling. Most runners gain far more from those than from anything on this page.

A running watch is both a genuine training tool and a generator of vanity metrics, and the value lies in telling the two apart. The governing idea, endorsed by a cardiology consensus review, is that consumer wearable signals should be read as *trends within one individual over time*, not as precise absolute values or as a basis for comparing one person to another ([JACC State-of-the-Art Review 2023](../sources/jacc-2023-wearables.md)). Because a device's error is often a fairly stable offset, an absolutely-wrong number can still track real change in one person against their own baseline.

## What watches measure well

- **Average pace and distance over a normal run.** GPS distance error for modern watches is typically around 3 to 6%, and can be under 3% at steady efforts on open ground ([Gilgen-Ammann et al. 2020](../sources/gilgen-2020-gps.md)).
- **Heart rate, with caveats.** Optical wrist heart rate is within about 5% at rest and steady state ([Shcherbina et al. 2017](../sources/shcherbina-2017-wearables.md)).

## What they only estimate

- **GPS distance under tree cover, in cities, and on tight bends**, where it is systematically underestimated and noisier ([Gilgen-Ammann et al. 2020](../sources/gilgen-2020-gps.md)). Instantaneous pace is far noisier than lap or average pace, because differentiating a metre-noisy position over a short window amplifies the noise; use lap pace, not the jumping real-time figure.
- **Wrist heart rate during intervals and hard efforts**, where optical sensors lag and underestimate, with error worst during cycling and resistance work, and larger for darker skin tones at high intensity ([Zhang et al. 2020](../sources/zhang-2020-hr.md); [Hung et al. 2025](../sources/hung-2025-hr-skin.md)). A chest strap is far better for interval work.
- **Estimated VO₂max.** Garmin's figure uses the FirstBeat algorithm from the heart-rate-to-pace relationship ([FirstBeat VO₂max white paper](../sources/firstbeat-vo2max.md)). The manufacturer states roughly 5% mean error; independent validation found around 7 to 8% overall, valid in moderately trained runners but poor in the highly trained, where it underestimates ([Engel et al. 2025](../sources/engel-2025-vo2max.md); [Železnik Mežan 2025](../sources/zeleznik-2025-vo2max.md)). A chest strap markedly improves it.
- **Calories.** The weakest common metric: no device tested achieved under 20% error, with a median around 27%, even while heart-rate error stayed small ([Shcherbina et al. 2017](../sources/shcherbina-2017-wearables.md)). Treat calorie figures as fiction.
- **Sleep staging.** Wearables detect sleep well but wake poorly, show meaningful errors in total sleep time, and get light, deep and REM staging substantially wrong ([Schyvens et al. 2025](../sources/schyvens-2025-sleep.md); [Lee et al. 2025](../sources/lee-2025-sleep-tracker-meta.md)). A pooled analysis of 24 studies found devices underestimated total sleep time by around 17 minutes on average and overestimated wake after sleep onset by 13 minutes. Total sleep trend, yes; the stage breakdown, no. See [sleep](../recovery/sleep.md).
- **Lactate threshold and running power.** Watch threshold estimates get heart rate roughly right but pace badly wrong, overestimating threshold pace by over 20% ([Lu et al. 2025](../sources/lu-2025-lt-watch.md)). Running "power" has no agreed criterion standard, so different brands report different watts for the same run and cannot be compared ([Imbach et al. 2020](../sources/imbach-2020-power.md)).

## Read the manual

The accuracy figures above are best-case, and sloppy setup makes them worse. Most of that error is avoidable by matching the watch's settings to how you actually run.

- **Use the lap button, not the live pace field.** Instantaneous pace is the noisiest number the watch shows. Press lap at known points, or set auto-lap, and judge effort from lap or average pace. For [intervals](../recovery/training-monitoring.md), the lap button marks each rep cleanly; staring at jumping real-time pace mid-rep is chasing noise.
- **Select the right activity profile.** Track, trail, treadmill and road profiles apply different distance logic; a track mode that snaps to a 400 m lane, or treadmill mode that uses the accelerometer rather than absent GPS, is far more accurate than a generic outdoor run.
- **Set the satellite mode deliberately.** Multi-band or multi-GNSS positioning is markedly more accurate under tree cover and among buildings than the default single-band mode, at some battery cost. Pick it for technical routes; the [GPS error](../sources/gilgen-2020-gps.md) you read about is largely the default setting underperforming.
- **Pair a chest strap for hard sessions.** Wrist optical heart rate lags and underreads during intervals; a paired [chest strap](heart-rate-monitors.md) fixes both the heart-rate trace and every metric built on it, including estimated VO₂max.
- **Calibrate and update.** Calibrate a foot pod or treadmill factor, keep the firmware current, and enter an accurate maximum and resting heart rate, because the zone and load models are only as good as those inputs.
- **Know what each metric actually is.** The branded scores below are models, not measurements; reading the manufacturer's description of how one is derived is the difference between using it well and being misled by it.

## The vanity-metric trap

"Training Load", "Training Status", "Body Battery", "Recovery Time", "Sleep Score" and "Training Readiness" are built mostly on heart-rate-variability models from FirstBeat ([FirstBeat stress and recovery white paper](../sources/firstbeat-stress.md)), with sleep staging and training-load inputs also feeding some scores. A "Sleep Score" inherits the staging errors above, so it is a rough nightly trend at best. The mechanisms are credible, but the branded *absolute* outputs have little independent validation, and a headline like "Recovery Time: 37 hours" carries false precision. Their value is comparative and longitudinal within one person, not the exact number and not across people.

This connects directly to [training monitoring](../recovery/training-monitoring.md) and the idea of a smallest worthwhile change: a metric is only useful for a decision when its measurement error is smaller than the change you are trying to detect ([Hopkins 2000](../sources/hopkins-2000-reliability.md)). For most watch-estimated metrics that means watching multi-week trends and ignoring daily wobble, the same discipline that applies to [HRV](../recovery/training-monitoring.md) and to judging a [shoe](super-shoes.md) or [supplement](../nutrition/dietary-nitrate.md) on yourself.

## Related

- [Training monitoring](../recovery/training-monitoring.md)
- [Individual variation](../concepts/individual-variation.md)
- [VO₂max](../concepts/vo2max.md)
- [Sleep](../recovery/sleep.md)
- [Lactate threshold](../concepts/lactate-threshold.md)
