---
layout: page
permalink: /
---


<div style="display: flex; gap: 28px; align-items: flex-start; margin-bottom: 24px;">
    <img src="/images/headshot.jpg" alt="Graham Taylor" style="width: 150px; border-radius: 6px; flex-shrink: 0;">
    <div>
        <h2 style="margin: 0 0 2px;">Graham Taylor, PhD</h2>
        <p style="color: #555; margin: 0 0 4px; font-size: 0.95em;">Research Associate, Cornell University</p>
        <p style="color: #888; margin: 0 0 16px; font-size: 0.85em;">Department of Earth and Atmospheric Sciences</p>
        <p style="margin: 0; line-height: 1.65;">
            My name is Graham Taylor, and I am a Research Associate in the Department of Earth and Atmospheric Sciences at Cornell University. My current research focuses on evaluating bias-correction and downscaling methods for climate projections, with emphasis on providing guidance to practitioners. Prior to Cornell, I was a UCAR CPAESS Postdoctoral Researcher working at the NOAA Geophysical Fluid Dynamics Laboratory. I received my PhD from Portland State University, where I investigated the large-scale circulation drivers of weather in the western US, and how that weather may change in a warmer world. Please view the research page for more information about my work.
        </p>
        <div style="display: flex; gap: 12px; margin-top: 14px; flex-wrap: wrap;">
            <a href="https://scholar.google.com/citations?user=JdkbOFUAAAAJ" style="font-size: 0.85em; padding: 4px 12px; background: #f4f4f4; border-radius: 6px; color: #333; text-decoration: none;">Google Scholar</a>
        </div>
    </div>
</div>





<!--
<br><br><br>
# Research Projects

- [West Coast Rain Onset and Wildfire](#west-coast-rain-onset-and-wildfire)
- [Projections of Atmospheric Circulation](#projections-of-atmospheric-circulation)
- [Downscaling Fit-For-Purpose](#downscaling-fit-for-purpose)

## West Coast Rain Onset and Wildfire

The West Coast of the US typically experiences cool, wet winters and warm, dry summers, with a transitional period between seasons that brings an increased risk of both strong winds and significant rain. This transition coincides with dangerously dry vegetation, creating high wildfire risk when strong winds arrive before rain. This work using dynamically downscaled CMIP6 model to analyze changes in the timing of rain onset and the timing of wind onset. Models project that by the end of the century under SSP370, strong winds will occur later in the season, and the first significant rainfall will also be delayed, though not as much as the winds. While there may be fewer instances where wind arrives before rain, the longer dry season will likely lead to drier vegetation, potentially affecting wildfire risk.

#### Historical Rain Onset

<img src="/images/era5_rain_onset_triple_split_3mmWA.jpg" alt="Historical Rain Onset Average" width="300">

#### Projected Changes to Rain Onset

<img src="/images/Figure7.jpeg" alt="Historical Rain Onset Average" width="600">

#### Projected Changes to Wind Onset

<img src="/images/model_wind_onset_change_sig.jpg" alt="Historical Rain Onset Average" width="600">


[Historical and Future Autumn Rain and Wind Onset Over Western North America Using Regional Climate Models](https://doi.org/10.1029/2025JD044267)
<br><br><br><br>

## Projections of Atmospheric Circulation

Climate models predict that by the end of this century, the Pacific Northwest will experience similar winter weather patterns as today, but summer patterns will show weaker atmospheric circulation. Summer weather patterns with strong atmospheric pressure differences will become less frequent. In winter, historically cold patterns will warm the most, while summer will see the greatest warming inland. Most areas will get wetter overall, though some currently rainy summer patterns may become significantly drier.

### Historical JJA Z500 Anomalies (1985-2014)

<img src="/images/JJA_circulation.png" alt="Historical Rain Onset Average" width="600">


### Future JJA Z500 Anomalies (2070-2099)

Shading shows future Z500 anomalies. Solid contours show positive change, dashed contours show negative change. 

<img src="/images/JJA_change.png" alt="Historical Rain Onset Average" width="600">


[CMIP6 model fidelity at simulating large-scale atmospheric circulation patterns and associated temperature and precipitation over the Pacific Northwest](https://doi.org/10.1007/s00382-022-06410-1)

[Projections of Large-Scale Atmospheric Circulation Patterns and Associated Temperature and Precipitation over the Pacific Northwest Using CMIP6 Models](https://doi.org/10.1175/JCLI-D-23-0108.1)
<br><br><br><br>

## Downscaling Fit-For-Purpose

Organizations planning for climate change need to use climate models to assess risks, but face an overwhelming number of choices when selecting downscaled climate data. There’s no universal “best method” because different downscaling approaches have varying strengths, and different climate risks require different considerations. The goal of this work is to create practical guidance to help risk managers make better-informed adaptation decisions by determining which climate tools are truly “fit for purpose” for their specific needs.

### Uncertainty in observations contributes to uncertainty in climate change projections

This study investigates how uncertainties in observation-based gridded datasets (OBGDs) influence downscaled climate projections in the Puget Sound region. We compare four OBGDs with station observations and identify significant disagreement in annual temperature indices. These biases propagate through three widely used bias-corrected and statistically downscaled (BSD) products (STAR-ESDM, LOCA2, NEX-GDDP-CMIP6), resulting in mid- and late-century projections that differ by up to 100% when based on the same sixteen CMIP6 models. Differences among BSD products exceed 1°C in winter minimum temperature warming and 50 Frost Days in areas with complex terrain. These findings emphasize that high spatial resolution does not ensure local accuracy, and reliance on a single dataset can obscure critical uncertainties. We recommend users consider multiple OBGDs and BSD products when using climate data for decision-making, and use climate-quality weather stations as benchmarks, where available, especially in areas of complex terrain.


<img src="/images/Figure1.jpeg" alt="Study Domain" width="600">

The study domain.  Shading shows the elevation gradient of the region with the 5 ISD-lite airport stations indicated by black dots (SEA, TIW, TCM, GRF, OLM). A subset shows the smaller area around the stations. 

<img src="/images/Figure2.jpeg" alt="The workflow of some commonly-used statistical downscaling products" width="600">

The workflow of some commonly-used statistical downscaling products.

<img src="/images/Figure5.jpeg" alt="Historical Frost Days in Station Data and Observation-Based Grids" width="600">

Annual count of Frost Days for 5 stations around the Puget Sound, and OBGD grid cells that contain the station locations, for the historical time period (1985-2014). Note the large disagreements among observation-based datasets, among themselves and with stations.

<img src="/images/Figure8.jpeg" alt="Climate Model Projections of Frost Days Across Downscaling Methods" width="600">

Frost Day (1985-2099) counts for each year at 5 locations, smoothed with a 3-year moving mean, showing the 16 model ensemble mean for LOCA2 (green), BCSDd (purple), and STAR trained on nClimGrid (brown). For STAR, the model mean value for STAR downscaled with station data at OLM and SEA is also shown in blue. For years 2015-2099, results are from the SSP5-8.5 scenario. Note the significant difference between the two STAR datasets, just by switching the training data, the projected future Frost Days count changes by 100% because of a different baseline.

-->
