---
layout: page
title: Research
permalink: /research/
---

Please click on the links or scroll down to view information about some of my research.

- [West Coast Autumn Rain Onset and Wildfire](#west-coast-autumn-rain-onset-and-wildfire)
- [Atmospheric Circulation and Climate Change](#projections-of-atmospheric-circulation)
- [Evaluating High-Resolution Climate Data](#downscaling-fit-for-purpose)

<br><br><br><br>

## West Coast Autumn Rain Onset and Wildfire

The West Coast of the US typically experiences cool, wet winters and warm, dry summers, with a transitional period between seasons that brings an increased risk of both strong winds and significant rain. This transition coincides with dangerously dry vegetation, creating high wildfire risk when strong winds arrive before rain. This work using dynamically downscaled CMIP6 model to analyze changes in the timing of rain onset and the timing of wind onset. Models project that by the end of the century under SSP370, strong winds will occur later in the season, and the first significant rainfall will also be delayed, though not as much as the winds. While there may be fewer instances where wind arrives before rain, the longer dry season will likely lead to drier vegetation, potentially affecting wildfire risk.

#### Historical Rain Onset

<img src="/images/era5_rain_onset_triple_split_3mmWA.jpg" alt="Historical Rain Onset Average" width="300">

Historical (1981:2010) average rain onset date in WRF‐ERA5. Only grid cells where the winter (December, January, and February) mean total precipitation is at least three times the summer (June, July, and August) mean total precipitation are shaded.

#### Projected Changes to Rain Onset

<img src="/images/Figure7.jpeg" alt="Historical Rain Onset Average" width="600">

Projected change in the average rain onset date in days. A positive value indicates that the rain onset is projected to be later in the year, whereas a negative value indicates an earlier onset. Differences are calculated between historical (1981:2010) and future (2070:2099) averages. Hatching indicates significance at the 90th percentile confidence level, using a Mann‐Whitney U test. Ensemble mean hatching indicates where at least six models agree on the significant change of the same sign.

#### Projected Changes to Wind Onset

<img src="/images/model_wind_onset_change_sig.jpg" alt="Historical Rain Onset Average" width="600">

Projected change in the average wind onset date in days. Differences are calculated between future (2070:2099) and historical (1981:2010) averages. Hatching indicates significance at the 90th percentile confidence level, according to a Mann‐Whitney U test. Ensemble mean hatching indicates where at least six models agree on significant change of the same sign. Wind percentiles are based on the 1981–2010 climate for historical and future onset calculations.

This work has been published in the *Journal of Geophysical Research: Atmospheres*: 

[Historical and Future Autumn Rain and Wind Onset Over Western North America Using Regional Climate Models](https://doi.org/10.1029/2025JD044267)
<br><br><br><br>

## Projections of Atmospheric Circulation

Climate models predict that by the end of this century, the Pacific Northwest will experience similar winter weather patterns as today, but summer patterns will show weaker atmospheric circulation. Summer weather patterns with strong atmospheric pressure differences will become less frequent. In winter, historically cold patterns will warm the most, while summer will see the greatest warming inland. Most areas will get wetter overall, though some currently rainy summer patterns may become significantly drier.

### Historical Range in JJA Z500 Anomalies (1985-2014)

<img src="/images/JJA_circulation.png" alt="JJA Circulation" width="600">

Historical range of Z500 anomalies, as calculating using self-organizing maps. These show the range of JJA circulation patterns characteristic of the region.
### Future Change in JJA Z500 Anomalies (2070-2099)

<img src="/images/JJA_change.png" alt="JJA Circulation Change" width="600">

Difference between the 2071–2100 Z500 anomaly patterns and the historical anomaly patterns (contoured every 3 m). Solid contours indicate positive change, while dashed contours indicate negative change. The dotted line is the zero contour. Shading shows end-of-century pseudo-SOMs. Grid cells with green dots are where at least half of the CMIP6 models exhibit a statistically significant change of the same sign at the 95% confidence level according to a t test. Grid cells with gray dots are where at least half of the 26 models agree on the sign of change without the significance constraint.

This work has been published in *Climate Dynamics* and *Journal of Climate*:

[CMIP6 model fidelity at simulating large-scale atmospheric circulation patterns and associated temperature and precipitation over the Pacific Northwest](https://doi.org/10.1007/s00382-022-06410-1)

[Projections of Large-Scale Atmospheric Circulation Patterns and Associated Temperature and Precipitation over the Pacific Northwest Using CMIP6 Models](https://doi.org/10.1175/JCLI-D-23-0108.1)
<br><br><br><br>

## Downscaling Fit-For-Purpose

Organizations planning for climate change need to use climate models to assess risks, but face an overwhelming number of choices when selecting downscaled climate data. There’s no universal “best method” because different downscaling approaches have varying strengths, and different climate risks require different considerations. The goal of this work is to create practical guidance to help risk managers make better-informed adaptation decisions by determining which climate tools are truly “fit for purpose” for their specific needs.

### Uncertainty in observations contributes to uncertainty in climate change projections

This study investigates how uncertainties in observation-based gridded datasets (OBGDs) influence downscaled climate projections in the Puget Sound region. We compare four OBGDs with station observations and identify significant disagreement in annual temperature indices. These biases propagate through three widely used bias-corrected and statistically downscaled (BSD) products (STAR-ESDM, LOCA2, NEX-GDDP-CMIP6), resulting in mid- and late-century projections that differ by up to 100% when based on the same sixteen CMIP6 models. Differences among BSD products exceed 1°C in winter minimum temperature warming and 50 Frost Days in areas with complex terrain. These findings emphasize that high spatial resolution does not ensure local accuracy, and reliance on a single dataset can obscure critical uncertainties. *We recommend users consider multiple OBGDs and BSD products when using climate data for decision-making, and use climate-quality weather stations as benchmarks, where available, especially in areas of complex terrain.*

<br><br>
<img src="/images/Figure1.jpeg" alt="Study Domain" width="600">

The study domain.  Shading shows the elevation gradient of the region with the 5 ISD-lite airport stations indicated by black dots (SEA, TIW, TCM, GRF, OLM). A subset shows the smaller area around the stations. 

<br><br>

<img src="/images/Figure2.jpeg" alt="The workflow of some commonly-used statistical downscaling products" width="600">

The workflow of some commonly-used statistical downscaling products.

<br><br>

<img src="/images/Figure5.jpeg" alt="Historical Frost Days in Station Data and Observation-Based Grids" width="600">

Annual count of Frost Days for 5 stations around the Puget Sound, and OBGD grid cells that contain the station locations, for the historical time period (1985-2014). Note the large disagreements among observation-based datasets, among themselves and with stations.

<br><br>

<img src="/images/Figure8.jpeg" alt="Climate Model Projections of Frost Days Across Downscaling Methods" width="600">

Frost Day (1985-2099) counts for each year at 5 locations, smoothed with a 3-year moving mean, showing the 16 model ensemble mean for LOCA2 (green), BCSDd (purple), and STAR trained on nClimGrid (brown). For STAR, the model mean value for STAR downscaled with station data at OLM and SEA is also shown in blue. For years 2015-2099, results are from the SSP5-8.5 scenario. Note the significant difference between the two STAR datasets, just by switching the training data, the projected future Frost Days count changes by 100% because of a different baseline.

This work is currently in revision at the *Journal of Applied Meteorology and Climatology*
