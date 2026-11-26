---
layout: default
title: "Horizon Summary: 2026-11-26 (EN)"
date: 2026-11-26
lang: en
---

> From 473 items, 12 important content pieces were selected

---

**GeoAI and Geospatial Data Science**
1. [Geo-Eval-Harness: Benchmarking Geospatial Foundation Models](#item-geoai-1) ⭐️ 10.0/10
2. [MOVR-SAR: A Multi-resolution SAR Registration Dataset](#item-geoai-2) ⭐️ 9.0/10
3. [Mapping Amazon Forest Height with Planet NICFI, LiDAR, and U-Net](#item-geoai-3) ⭐️ 9.0/10
4. [Mapping Large Trees and Health Status in the Sierra Nevada](#item-geoai-4) ⭐️ 9.0/10
5. [High-Resolution Canopy Height and Carbon Maps for the Atlantic Forest](#item-geoai-5) ⭐️ 9.0/10

**Climate, Geoscience, Teaching and Funding**
1. [Skysail: Wind Shear Altitude Control for Weather Balloons](#item-geo-science-edu-1) ⭐️ 8.0/10
2. [LatENSO v1.0: A Learned Latent State for ENSO Forecasting](#item-geo-science-edu-2) ⭐️ 8.0/10
3. [CLM-JAX v3.2.46: Differentiable, GPU-Accelerated Land Surface Modeling](#item-geo-science-edu-3) ⭐️ 8.0/10
4. [Bolivia Drought El Niño 2026 DREF Operation](#item-geo-science-edu-4) ⭐️ 7.0/10
5. [El Niño Drought Strands Amazon Villages as Roraima Rivers Drop](#item-geo-science-edu-5) ⭐️ 7.0/10
6. [Heatwave and Drought Worsened South African Air Pollution](#item-geo-science-edu-6) ⭐️ 7.0/10
7. [Severe Drought and Low Lake Levels Grip Okanagan Valley](#item-geo-science-edu-7) ⭐️ 7.0/10

---

## GeoAI and Geospatial Data Science

<a id="item-geoai-1"></a>
### [Geo-Eval-Harness: Benchmarking Geospatial Foundation Models](https://arxiv.org/abs/2611.33990) ⭐️ 10.0/10

The authors introduce geo-eval-harness, an open-source framework designed for controlled benchmarking of 100 geospatial and general vision foundation models. Using frozen or low-rank-adapted encoders across 6 classification and 14 segmentation datasets, the evaluation reveals that general vision backbones perform well on RGB tasks, while geospatial models excel in multispectral settings. The results demonstrate that model scale correlates weakly with segmentation performance, and small accuracy differences can lead to significant variations in deployment compute costs.

rss · arXiv cs.CV · Nov 26, 05:00

**「Context」** Geospatial foundation model research has often suffered from inconsistent evaluation settings, such as varying pre-processing and probes, which obscure true performance differences. This framework addresses these inconsistencies by enforcing explicit, fixed settings, highlighting the necessity of reporting uncertainty and deployment compute alongside accuracy metrics.

**「Application」** Geospatial instructors and researchers can utilize this open-source framework and its associated code, configurations, and datasets as a reproducible tool to benchmark GeoAI models and teach rigorous evaluation practices.

**Tags**: `#Geospatial Foundation Models`, `#Model Evaluation`, `#GeoAI`, `#Remote Sensing`, `#Open Source`

---

<a id="item-geoai-2"></a>
### [MOVR-SAR: A Multi-resolution SAR Registration Dataset](https://arxiv.org/abs/2611.33673) ⭐️ 9.0/10

The authors introduce MOVR-SAR, a large-scale, multi-resolution benchmark dataset comprising 450,845 quality-screened tile pairs from Capella, Umbra, Sentinel-1, and NISAR. Covering X, C, and L bands with ground sampling distances of 0.25 to 20 meters, the dataset addresses synthetic aperture radar image registration across orbit-crossing and view-variant geometries. Systematic evaluations show that fine-tuning models on MOVR-SAR dramatically increases registration accuracy, raising the FlexGlue AUC@5 score from 3.06% to 89.79% on Capella imagery.

rss · arXiv cs.CV · Nov 26, 05:00

**「Context」** Synthetic aperture radar image registration under varying acquisition geometries is difficult because differences in orbit direction, look side, and incidence angle alter backscatter, terrain-induced distortion, and feature visibility. Large-scale geometry-aware benchmarks for this task have previously been scarce, limiting cross-geometry matching performance.

**「Application」** Geospatial instructors and researchers can use the open dataset, evaluation framework, and model weights to train and benchmark robust cross-geometry synthetic aperture radar registration algorithms across diverse sensor platforms and land-cover types.

**Tags**: `#synthetic aperture radar`, `#image registration`, `#datasets`, `#deep learning`, `#earth observation`

---

<a id="item-geoai-3"></a>
### [Mapping Amazon Forest Height with Planet NICFI, LiDAR, and U-Net](https://arxiv.org/abs/2501.10600) ⭐️ 9.0/10

Researchers generated a high-resolution canopy height map of the Amazon forest at approximately 4.78-meter resolution using Planet NICFI imagery and a U-Net regression model trained on tropical airborne LiDAR data. The validation sample yielded a mean absolute error of 3.68 meters, outperforming existing global products by estimating canopy heights up to 40-50 meters with minimal saturation, while reporting slight overestimation for heights of 5-15 meters and underestimation above 50 meters.

rss · arXiv cs.CV · Nov 26, 05:00

**「Context」** Measuring tree canopy height accurately at regional scales remains challenging despite its importance for assessing forest biomass and structure. This work builds on deep learning and satellite remote sensing to overcome saturation limits common in previous global model-based canopy height products.

**「Application」** Geospatial instructors and researchers can use this study&\#x27;s methodology as a reference for training U-Net regression models with high-resolution satellite imagery and LiDAR data to monitor regional forest structure and regeneration.

**Tags**: `#GeoAI`, `#remote sensing`, `#deep learning`, `#forest canopy height`, `#Earth observation`

---

<a id="item-geoai-4"></a>
### [Mapping Large Trees and Health Status in the Sierra Nevada](https://arxiv.org/abs/2609.17925) ⭐️ 9.0/10

Researchers mapped over 6.5 million large trees with crown areas of at least 100 square meters across the Sierra Nevada from 2020 to 2025. The study utilized deep learning on USDA-NAIP canopy height models, validated with over 20,000 giant sequoia crowns to achieve a median Intersection over Union of 0.60. Sentinel-2 time series captured visible and near-infrared color changes to evaluate tree health, revealing that 61.4 percent of large trees within 2020–2024 wildfire perimeters were disturbed or dead.

rss · arXiv cs.CV · Nov 26, 05:00

**「Context」** This work addresses the regional-scale gap in tracking large forest trees, which store disproportionate forest biomass. It builds on deep learning approaches for canopy height models and satellite time series to monitor individual tree crowns over large geographic extents.

**「Application」** Geospatial instructors and researchers can use this study as a methodological reference for combining high-resolution aerial canopy models with Sentinel-2 time series for individual tree crown delineation and disturbance monitoring.

**Tags**: `#remote sensing`, `#deep learning`, `#vegetation monitoring`, `#tree crown delineation`, `#sentinel-2`

---

<a id="item-geoai-5"></a>
### [High-Resolution Canopy Height and Carbon Maps for the Atlantic Forest](https://arxiv.org/abs/2611.23048) ⭐️ 9.0/10

Researchers released high-resolution wall-to-wall maps of canopy height \(10m\) and aboveground carbon density \(30m\) for the Brazilian Atlantic Forest in 2024. The method uses a deep learning network fusing Sentinel-2, Sentinel-1, ALOS PALSAR, and elevation data, trained on 58,800 square kilometers of airborne LiDAR from São Paulo state. Evaluated on held-out test patches, canopy height achieved a mean absolute error of 2.26 meters at 10 meters and 1.90 meters at 30 meters, outperforming global products in regional accuracy.

rss · arXiv cs.CV · Nov 26, 05:00

**「Context」** While global canopy height maps are increasingly utilized to estimate forest carbon, their regional accuracy is seldom rigorously tested against local conditions. The authors demonstrate that regional models can substantially improve precision over existing global datasets, highlighting that global products require careful local validation prior to carbon accounting.

**「Application」** Geospatial instructors and researchers can use these open datasets and methods to teach advanced deep learning workflows in remote sensing, or to examine regional carbon storage and biomass estimation in tropical forests.

**Tags**: `#GeoAI`, `#Remote Sensing`, `#Deep Learning`, `#Biomass Estimation`, `#Earth Observation`

---

## Climate, Geoscience, Teaching and Funding

<a id="item-geo-science-edu-1"></a>
### [Skysail: Wind Shear Altitude Control for Weather Balloons](https://arxiv.org/abs/2611.33882) ⭐️ 8.0/10

The source reports the development of an altitude-control system that uses wind shear to drive vertical motion and atmospheric profiling for weather balloons without consuming ballast or lifting gas. A small suspended wing extracts mechanical work from the wind velocity difference between 450 meters below a zero-pressure balloon and the balloon itself. Flight experiments over two years demonstrated significant performance, including a 43-hour flight with 53 kilometers of vertical travel and an eight-day flight achieving 159 kilometers of vertical travel across 24 profiles.

rss · arXiv physics.ao-ph · Nov 26, 05:00

**「Context」** Traditional long-duration weather balloons are limited by finite consumables like lifting gas and ballast used to collect repeated atmospheric profiles. The authors developed sizing models, a lightweight aerodynamic governor, and a control architecture to harness wind shear, though conventional actuators are retained for trim and fallback. Control authority inherently depends on available wind shear conditions.

**「Relevance」** This research can be used in atmospheric science and remote sensing courses to discuss modern instrumentation and sustainable data collection methods. In research, it provides a methodological framework for improving the endurance and profiling capabilities of autonomous atmospheric platforms.

**Tags**: `#atmospheric science`, `#remote sensing`, `#weather balloons`, `#wind shear`, `#instrumentation`

---

<a id="item-geo-science-edu-2"></a>
### [LatENSO v1.0: A Learned Latent State for ENSO Forecasting](https://arxiv.org/abs/2611.34296) ⭐️ 8.0/10

Milad Panahi and Annalisa Bracco introduce LatENSO v1.0, a machine-learning forecasting framework that uses a Swin-transformer autoencoder to compress thirteen monthly-averaged tropical Pacific fields into a 32-dimensional latent state. Evaluated across 1981-2024 verification windows, the system&\#x27;s extended nonlinear recharge oscillator \(XRO-lat\) achieves an anomaly correlation coefficient of 0.673 over 1-18 month lead times, matching multi-basin reference models, and becomes the most skillful system at lead times of 15 to 24 months.

rss · arXiv physics.geo-ph · Nov 26, 05:00

**「Context」** This work builds on traditional recharge oscillator dynamics by coupling them with a compact, inspectable machine-learning representation of the tropical Pacific. The authors note limitations such as a temporary performance deficit for the Floquet modal operator at 3-9 month lead times, which is partly attributed to its base forecast.

**「Relevance」** The open-access code, model weights, and data make LatENSO v1.0 a valuable resource for teaching advanced climate modeling or incorporating hybrid machine-learning methods into oceanography and remote sensing research.

**Tags**: `#climate modeling`, `#ENSO`, `#machine learning`, `#remote sensing`, `#oceanography`

---

<a id="item-geo-science-edu-3"></a>
### [CLM-JAX v3.2.46: Differentiable, GPU-Accelerated Land Surface Modeling](https://arxiv.org/abs/2611.34574) ⭐️ 8.0/10

The authors introduce CLM-JAX v3.2.46, a Python-based implementation of the Community Land Model 5.0 \(CLM5.0\) that supports GPU acceleration and automatic differentiation while preserving numerical consistency with the original Fortran version. Evaluated over a five-year global simulation from 2019 to 2023 across 32 variables, CLM-JAX maintained errors below an internal ensemble baseline. Running on a single NVIDIA A800 GPU, the model achieved an integration speed of 0.7692 seconds per model hour, providing speedups over 64-core CPU implementations.

rss · arXiv physics.ao-ph · Nov 26, 05:00

**「Context」** Traditional land surface models like CLM5.0 primarily target CPUs and lack native support for gradient calculations, limiting their use in optimization and data assimilation tasks. CLM-JAX overcomes this by enabling backpropagation through multi-step time integration, allowing researchers to compute gradients with high accuracy relative to central finite difference references.

**「Relevance」** This framework can be integrated into graduate-level hydrology and climate modeling courses to demonstrate high-performance computing, or used in research funding proposals focused on machine learning-accelerated earth system modeling, parameter optimization, and four-dimensional variational data assimilation.

**Tags**: `#land surface modeling`, `#climate modeling`, `#GPU acceleration`, `#data assimilation`, `#remote sensing`

---

<a id="item-geo-science-edu-4"></a>
### [Bolivia Drought El Niño 2026 DREF Operation](https://news.google.com/rss/articles/CBMirgFBVV95cUxOcjk4Wl8yMUtIeXkzcGM5amJuUko0M2RFaXg3M0YxbHV0c2MtZUMybWNvbU5mN3NWYVNwYnB6SkdrS19jT0Q4QWVBeHVsTnY0Q0I2bEpjcGRDWDhTNm9FTWswdnNZLTRKZmY2dXZCd3Mya2J4RlE2aWxwa2g5cWhNeWlrTjRfbGNmUllGaXJPSDlNYktma3ZaQWJqaHBaZmpjc0Uyd1lROExRRmJNRlE?oc=5) ⭐️ 7.0/10

A ReliefWeb Disaster Relief Emergency Fund operation report outlines drought conditions and ongoing response efforts driven by El Niño in Bolivia. The report details the scale of the climate impacts and humanitarian interventions coordinated during the 2026 event.

rss · Google News: climate and water · Nov 26, 04:04

**「Context」** The operation builds on international monitoring of El Niño-induced weather extremes affecting South American agricultural and water systems. Specific limitations and local vulnerability metrics depend on ongoing field assessments detailed in the full operational update.

**「Relevance」** This operational report can be utilized in undergraduate geography or climatology courses as a real-world case study examining humanitarian responses to climate anomalies and water resource crises.

**Tags**: `#drought`, `#El Niño`, `#Bolivia`, `#water resources`, `#climate`

---

<a id="item-geo-science-edu-5"></a>
### [El Niño Drought Strands Amazon Villages as Roraima Rivers Drop](https://news.google.com/rss/articles/CBMi4wFBVV95cUxORjg3TGY5LVJwSWdhNzhyc2ZkX09BS3IwMVYzTHhnZ2JfT0JMcDhkODdha2U0V1hmNmFBNW9ieTBWMDNPSmRsalJEYllidzRfeFdRb29JV0VoV2poMlVHTjFDcHZGMGVxUllOSGMtQWJDLXlzRDgtMjRKQ0x5TDJYNU1naGRtaF9qZUQ4aFkydThNaFZrTUh4cWM5X3VSbHRMRldIX3FVRmtIZm1Pd01pMXVDVWtYd09qLXBPSmc1bERHSHYtMmw1VVMxSy1ZQTk1ODRqWVpUZHQ5NExCaWFYNEdzdw?oc=5) ⭐️ 7.0/10

An El Niño-induced drought in Brazil&\#x27;s Roraima state has caused critical low river levels, stranding remote Amazon villages that depend on waterways for transport. The severe dry conditions have severely restricted navigation and access to essential supplies across the affected river basins.

rss · Google News: climate and water · Nov 26, 14:37

**「Context」** This event highlights the acute vulnerability of Amazonian hydrological systems to climate oscillations like El Niño, which frequently trigger severe droughts in northern South America. The source notes the immediate logistical impacts on local communities but provides limited quantitative hydrological metrics.

**「Relevance」** This case study can be used in physical geography and earth science courses to illustrate teleconnections between Pacific climate phenomena and South American hydrological disruptions. Researchers studying tropical climate impacts on vulnerable populations may also find it a useful reference for community-level vulnerability.

**Tags**: `#climate change`, `#drought`, `#water resources`, `#Amazon`, `#El Niño`

---

<a id="item-geo-science-edu-6"></a>
### [Heatwave and Drought Worsened South African Air Pollution](https://news.google.com/rss/articles/CBMipwFBVV95cUxQekxZUmN4RW9nMDRmNElfMlBoOGdLSzdKams1WHd1aUxWQ1NBeGQ3UE95c0JtbmFkeVBnamF2bE1KcXdFeVlLa25oZTAyOS04ZXFNZzJVYzNhX000SWxLNVhWN1JtSkR0Ulhkdk5WSDk2emdDZVdLb1BrcW42NXlLY2RGcWFtcUk4T3B2eFVmU0dzM0RPaVltUV9fV0lpWVZ5Z280cXdHZw?oc=5) ⭐️ 7.0/10

Research reports that an October 2022 heatwave and drought significantly worsened severe air pollution across South Africa. The study links these extreme meteorological conditions directly to compounded atmospheric pollution levels during that period.

rss · Google News: climate and water · Nov 26, 01:19

**「Context」** This work builds on ongoing investigations into how extreme weather events interact with regional industrial and domestic emissions to impact air quality. The source highlights the compound nature of climate extremes and pollution without detailing specific numerical thresholds or modeling limitations.

**「Relevance」** This finding can be incorporated into undergraduate or graduate courses addressing atmospheric sciences, climatology, and environmental justice in southern Africa. Researchers studying climate-air quality feedbacks can also use this event study in comparative regional assessments.

**Tags**: `#air pollution`, `#climate`, `#drought`, `#heatwave`, `#South Africa`

---

<a id="item-geo-science-edu-7"></a>
### [Severe Drought and Low Lake Levels Grip Okanagan Valley](https://news.google.com/rss/articles/CBMiywFBVV95cUxNb04waDJvdUNpbDBOOXpqN2tfU0J5Q29ta1E4aVRrLUVMRVdhTlFTTHZiN3hJbG1HVV9mdVQxdmNUNU4zbGZYdGNjbGhYNlAxNWdnX1lUZzFMLVlTN3JFZ0ZJTjFQcGxhZFdYNmhqNnFIZUJHYW5qdFh1U1B4QU01RU0zek5xQUV4cmlScDFoUVZnZ0tFWE5xaVdUblBEVGpMc3pOcW5QRF9fLUNqcVFvU05YMjBRS2hKN3hPSC1GT2tBLUNhSldtdE55TQ?oc=5) ⭐️ 7.0/10

The Weather Network reports that a severe drought is currently impacting the Okanagan Valley, causing lake levels to drop to historical lows. This event highlights acute regional water stress within the specified Canadian watershed.

rss · Google News: climate and water · Nov 26, 12:28

**「Context」** This reporting builds on ongoing regional climate monitoring of western Canada&\#x27;s water supplies. The source notes the severe conditions and record lows without detailing specific meteorological drivers or long-term hydrological limitations.

**「Relevance」** Instructors can use this event in regional geography and earth science courses as a real-world case study on watershed management, climate change impacts, and localized drought vulnerabilities.

**Tags**: `#drought`, `#water resources`, `#climate change`, `#regional geography`

---