---
layout: default
title: "Horizon Summary: 2026-11-24 (EN)"
date: 2026-11-24
lang: en
---

> From 826 items, 12 important content pieces were selected

---

**GeoAI and Geospatial Data Science**
1. [Training-Free Few-Shot Pineapple Detection in Aerial Imagery](#item-geoai-1) ⭐️ 9.0/10
2. [Why Short Chain-of-Thought Breaks Spatial VQA](#item-geoai-2) ⭐️ 9.0/10
3. [Benchmarking Geospatial Foundation Models Under Calibrated Label Errors](#item-geoai-3) ⭐️ 9.0/10
4. [Delineate Anything Flow for Country-Level Agricultural Field Boundary Detection](#item-geoai-4) ⭐️ 9.0/10
5. [Training-Free Entity-Level Few-Shot Segmentation for Remote Sensing](#item-geoai-5) ⭐️ 9.0/10

**Climate, Geoscience, Teaching and Funding**
1. [Differentiable PyTorch Rewrite of Coupled Weather and Fire Model](#item-geo-science-edu-1) ⭐️ 9.0/10
2. [Stochastic Climate Emulation With ACE2.5-ERA5](#item-geo-science-edu-2) ⭐️ 8.0/10
3. [Five Stable Climates Possible Under Modern Earth Boundary Conditions](#item-geo-science-edu-3) ⭐️ 8.0/10
4. [Extending Climate Projections Past 2100](#item-geo-science-edu-4) ⭐️ 8.0/10
5. [BGC-Argo Floats Provide Critical Early Warning for Marine Ecosystems](#item-geo-science-edu-5) ⭐️ 8.0/10
6. [UTA Project Uses AI and Satellites to Map Waterbodies for Drought Resilience](#item-geo-science-edu-6) ⭐️ 7.0/10
7. [Western Slope Water Users Mitigate Record Drought](#item-geo-science-edu-7) ⭐️ 7.0/10

---

## GeoAI and Geospatial Data Science

<a id="item-geoai-1"></a>
### [Training-Free Few-Shot Pineapple Detection in Aerial Imagery](https://arxiv.org/abs/2611.28442) ⭐️ 9.0/10

The authors introduce a training-free few-shot object detection method for agricultural imagery that converts dense features from frozen visual foundation models directly into detections using a whitened foreground-background direction. Evaluated on aerial pineapple imagery, the approach outperforms PET-DINO and GeCo2 across all tested support sizes, while RGB-depth fusion successfully lowers counting error. The team also releases the Pineapple Plantation dataset containing 4,908 aerial frames, with 1,995 annotated frames comprising 17,609 boxes, predicted depth, and leakage-aware splits.

rss · arXiv cs.CV · Nov 24, 05:00

**「Context」** This work addresses the challenges of few-shot object detection in agricultural remote sensing, which is typically hindered by dense vegetation, repetitive patterns, and limited annotations. The method builds on frozen visual foundation models by eliminating the need for fine-tuning, learned detection heads, or external region proposals.

**「Application」** Geospatial instructors and researchers can utilize the newly released Pineapple Plantation dataset and adapt the training-free detection method for evaluating few-shot agricultural monitoring workflows using visual foundation models.

**Tags**: `#few-shot learning`, `#object detection`, `#agricultural remote sensing`, `#visual foundation models`, `#aerial imagery`

---

<a id="item-geoai-2"></a>
### [Why Short Chain-of-Thought Breaks Spatial VQA](https://arxiv.org/abs/2611.28665) ⭐️ 9.0/10

This paper investigates why short chain-of-thought \(CoT\) reasoning degrades spatial Visual Question Answering \(VQA\) across 15 open and 6 frontier vision-language models. The author finds that writing intermediate spatial relations turns a perception task into a transcription problem, where the model follows its text instead of the image. False relations and conclusion mis-mapping account for four in five CoT losses, a bottleneck that model scale alone does not fix. The study introduces open-sourced datasets and code alongside a fine-tuning pilot that restores performance on natural photographs.

rss · arXiv cs.CV · Nov 24, 05:00

**「Context」** This research builds on efforts to understand multimodal reasoning failures in vision-language models by examining how intermediate text generation affects visual grounding. It demonstrates that frontier models avoid this degradation either by maintaining high spatial relation accuracy or by re-checking the image after writing text.

**「Application」** Geospatial instructors and researchers can use the open-sourced datasets and code as a benchmark to evaluate spatial grounding in multimodal GeoAI models or adapt the fine-tuning methodology to improve spatial reasoning in remote sensing applications.

**Tags**: `#GeoAI`, `#Vision-Language Models`, `#Spatial Reasoning`, `#Remote Sensing`, `#Benchmarking`

---

<a id="item-geoai-3"></a>
### [Benchmarking Geospatial Foundation Models Under Calibrated Label Errors](https://arxiv.org/abs/2611.30215) ⭐️ 9.0/10

The source reports a new benchmark protocol designed to evaluate fine-tuning performance under calibrated, spatially structured label errors. The protocol tests nine encoders, six decoder heads, and ten datasets using four calibrated error types equalized to the same label mIoU. The authors find that satellite-pretrained and web-pretrained DINOv3 encoders perform equivalently within a three-point margin on eight of nine datasets, and that real-world labels often incur a higher performance cost than their matched simulated counterparts.

rss · arXiv cs.CV · Nov 24, 05:00

**「Context」** Earth-observation labels frequently suffer from misalignments, coarse outlines, or incompleteness, yet geospatial foundation models \(GFMs\) are typically benchmarked assuming perfect ground truth. This work addresses the resulting gap by systematically testing model robustness against imperfect training data rather than assuming pristine labels. Mean Intersection over Union \(mIoU\) is a standard evaluation metric measuring the overlap between predicted and true segmentation regions.

**「Application」** Geospatial instructors and researchers can use this benchmark protocol and its findings to guide encoder selection when working with noisy, real-world remote sensing datasets. Practitioners can adopt these evaluation methods to test how different decoder heads and pretraining strategies handle label noise in applied GeoAI workflows.

**Tags**: `#geospatial foundation models`, `#earth observation`, `#benchmark`, `#label noise`, `#remote sensing`

---

<a id="item-geoai-4"></a>
### [Delineate Anything Flow for Country-Level Agricultural Field Boundary Detection](https://arxiv.org/abs/2511.13417) ⭐️ 9.0/10

The authors introduce Delineate Anything Flow \(DelAnyFlow\), an open GeoAI framework that integrates a YOLOv11-based model called DelAny with structured post-processing for scalable field boundary detection. Trained on the FBIS-22M dataset comprising 22.9 million field instances across 672,909 patches, DelAny achieves an mAP@0.5 of 0.720 with faster inference than SAM2. Operating at a national scale, the framework successfully mapped Ukraine&\#x27;s entire 603,000 km² territory in 5.4 hours, yielding an intersection over union of 0.971 and a small-object recall of 0.878.

rss · arXiv cs.CV · Nov 24, 05:00

**「Context」** Generating accurate agricultural field boundaries from satellite imagery typically suffers from topological errors and high computational costs when scaling tile-level predictions into continuous vector products. DelAnyFlow addresses this by combining cross-tile instance unification—which reduces seam-induced fragmentation by a factor of 4 to 6—with anchor-guided simplification to resolve neighboring field overlaps.

**「Application」** Geospatial instructors and researchers can utilize DelAnyFlow&\#x27;s open-source code, models, and national vector datasets for land management studies or as a scalable workflow method for large-area remote sensing analysis.

**Tags**: `#GeoAI`, `#Remote Sensing`, `#Field Boundary Delineation`, `#Object Detection`, `#Agriculture`

---

<a id="item-geoai-5"></a>
### [Training-Free Entity-Level Few-Shot Segmentation for Remote Sensing](https://arxiv.org/abs/2607.29278) ⭐️ 9.0/10

The authors introduce ELFSS-AR, a training-free framework for entity-level few-shot segmentation in remote sensing imagery. The method leverages SAM3 geometric priors to shift from pixel-level prediction to entity-level reasoning, constructing a multi-modal semantic potential field combined with an advection equation-based refinement mechanism. Experiments across multiple remote sensing datasets show that the approach mitigates domain shift and local texture noise, improving semantic continuity without requiring additional training.

rss · arXiv cs.CV · Nov 24, 05:00

**「Context」** Traditional cross-domain few-shot segmentation techniques face high training costs from source-domain episodic training and dense pixel-wise predictions, frequently resulting in fragmented remote sensing outputs. This method builds on foundational models like SAM3, adapting their capabilities for remote sensing tasks by replacing standard pixel-wise inference with entity-level reasoning and advection refinement.

**「Application」** Geospatial instructors and researchers can utilize the open-source code repository as a practical GeoAI tool for few-shot image segmentation experiments and teaching advanced spatial machine learning workflows.

**Tags**: `#GeoAI`, `#few-shot segmentation`, `#remote sensing`, `#image segmentation`, `#open-source code`

---

## Climate, Geoscience, Teaching and Funding

<a id="item-geo-science-edu-1"></a>
### [Differentiable PyTorch Rewrite of Coupled Weather and Fire Model](https://arxiv.org/abs/2611.30866) ⭐️ 9.0/10

Researchers successfully rewrote selected configurations of the Weather Research and Forecasting \(WRF\) model and its coupled fire physics in PyTorch using AI coding agents. During a twelve-hour simulation of the Marshall Fire across 365 checkpoints, the reconstructed PyTorch code achieved bit-for-bit agreement with the original Fortran code in the atmosphere, fire, and firebrand particles. Furthermore, the PyTorch model executed approximately five times faster on a single GPU than the double-precision Fortran code on a 128-core CPU node while enabling gradient-based sensitivity analysis.

rss · arXiv physics.ao-ph · Nov 24, 05:00

**「Context」** This work demonstrates an alternative to replacing physical weather and climate models entirely with learned AI models by rebuilding the physical numerical models directly inside machine-learning frameworks. The source notes that neural networks replaced radiation and fire-spread calculations in 24-hour coupled forecasts, though quantitative error metrics for these specific neural network substitutions are not detailed.

**「Relevance」** This development can be directly utilized in research and advanced computational teaching to perform gradient-based sensitivity analyses, such as mapping fire sensitivity to wind at every grid point. It offers a pathway for integrating machine learning components into established physical models while preserving their tested calculations.

**Tags**: `#weather forecasting`, `#wildfire modeling`, `#machine learning`, `#differentiable programming`, `#numerical modeling`

---

<a id="item-geo-science-edu-2"></a>
### [Stochastic Climate Emulation With ACE2.5-ERA5](https://arxiv.org/abs/2611.28315) ⭐️ 8.0/10

Researchers introduce ACE2.5-ERA5, a stochastic AI-based weather and climate emulator that generates calibrated ensembles from days to centuries at reduced computational cost. The model retains 86% of its ERA5 target precipitation spectral power at wavenumbers 100-179, compared to 36% for its predecessor, while delivering 3.2 times the inference throughput. The authors release 1-degree daily, 4-degree daily, and 1-degree 6-hourly model checkpoints.

rss · arXiv physics.ao-ph · Nov 24, 05:00

**「Context」** Building on the deterministic ACE2-ERA5 model, the new version uses noise-conditioned layer normalization and combined scoring losses to achieve stochastic behavior and a smaller memory footprint. However, the authors note that interannual variability of global mean surface temperature remains uncalibrated in both versions.

**「Relevance」** The open-release checkpoints and reduced training costs offer valuable resources for computational geoscience research workflows and case studies in advanced climate modeling courses.

**Tags**: `#climate modeling`, `#artificial intelligence`, `#weather forecasting`, `#remote sensing`, `#stochastic emulation`

---

<a id="item-geo-science-edu-3"></a>
### [Five Stable Climates Possible Under Modern Earth Boundary Conditions](https://arxiv.org/abs/2611.28357) ⭐️ 8.0/10

Researchers use the coupled atmosphere-ocean-ice-vegetation model BIG-MITgcm to demonstrate that modern Earth could support five distinct stable climates under identical pre-industrial boundary conditions. The identified states range from a pole-to-pole Snowball and a tropical Waterbelt to a Last Glacial Maximum-like Cold world, our current Warm climate, and a Hot world with a collapsed Atlantic overturning circulation. Each state is maintained by specific competing feedbacks, with ocean heat transport anchoring the ice edge where transport is weak.

rss · arXiv physics.ao-ph · Nov 24, 05:00

**「Context」** This study explores multiple equilibria in Earth&\#x27;s climate system, suggesting the Holocene is only one of several potential states. These findings have implications for understanding glacial-interglacial transitions and the risk of crossing irreversible global tipping points. The authors note that ocean heat transport plays a critical role in anchoring each respective climate state.

**「Relevance」** This paper provides excellent case studies for teaching climate dynamics, tipping points, and feedback mechanisms in advanced earth science courses. Researchers can also use these modeling insights to frame new hypotheses regarding multiple equilibria and stability landscapes in paleoclimate and future climate research.

**Tags**: `#climate dynamics`, `#climate modeling`, `#paleoclimate`, `#tipping points`, `#ocean circulation`

---

<a id="item-geo-science-edu-4"></a>
### [Extending Climate Projections Past 2100](https://eos.org/editors-vox/2100-is-not-the-far-future-anymore) ⭐️ 8.0/10

A recent review article in Earth&\#x27;s Future examines the motivations, challenges, and importance of extending climate model projections past the year 2100 into the 22nd century. Lead author David Huard notes that while most simulations historically stopped at 2100 due to high computational costs and simplistic emission scenarios, long-term projections are crucial for managing multi-century risks like coastal development and infrastructure design. Out of more than 400 analyzed papers on post-2100 climate change, Huard points out that only five explicitly discuss hazard probabilities.

rss · Eos \(AGU\) · Nov 24, 16:15

**「Context」** Limiting climate model projections to 2100 risks framing climate change strictly as a 21st-century issue rather than a multi-generational crisis. Earth System Model simulations remain expensive to run, and post-2100 pathways often rely on stylized assumptions where emissions stay constant or return linearly to zero. Huard highlights that researchers face lower confidence in both emission scenarios and long-term models, alongside a scarcity of data and probabilistic risk assessments.

**「Relevance」** Faculty can use this study in courses on climate modeling, earth systems, and policy to discuss why long-term projections are vital for infrastructure design, coastal planning, and climate services. It provides a strong framework for teaching students about the limitations of 21st-century horizons and the need for probabilistic risk assessments in climate adaptation.

**Tags**: `#climate modeling`, `#climate projections`, `#earth systems`, `#climate change policy`

---

<a id="item-geo-science-edu-5"></a>
### [BGC-Argo Floats Provide Critical Early Warning for Marine Ecosystems](https://eos.org/opinions/these-ocean-floats-offer-unique-early-warning-capabilities-we-shouldnt-let-them-go) ⭐️ 8.0/10

Biogeochemical Argo \(BGC-Argo\) floats offer unique subsurface chemical and ecological data during El Niño events, capturing nutrient changes that surface-level satellites miss. The source reports that the global network comprised 985 floats as of October 2026—including 579 equipped with nitrate sensors—and tracked early declines in surface nitrate across the equatorial Pacific during the developing 2026 super El Niño. However, the author warns that the expiration of U.S. funding for the GO-BGC program in 2026 threatens sustained monitoring and leaves future gaps in the observing array.

rss · Eos \(AGU\) · Nov 24, 14:22

**「Context」** The article builds on the understanding that El Niño disrupts trade winds and upwelling, altering ocean temperatures and primary productivity that sustain fisheries, seabirds, and marine mammals. BGC-Argo floats address limitations in traditional sea surface temperature monitoring by profiling the upper 2,000 meters of the water column every 10 days. The author notes that single nitrate measurements represent local conditions rather than regional forecasts or entire ecosystem outcomes.

**「Relevance」** Faculty can incorporate these findings into physical oceanography and climate courses by using real-world comparisons between the 2023–2024 and 2026 El Niño events to illustrate subsurface biogeochemical responses. The piece also provides a strong case study for research and policy discussions regarding the vulnerability of long-term environmental monitoring networks and technical workforce retention.

**Tags**: `#oceanography`, `#El Niño`, `#climate change`, `#marine ecosystems`, `#remote sensing`

---

<a id="item-geo-science-edu-6"></a>
### [UTA Project Uses AI and Satellites to Map Waterbodies for Drought Resilience](https://news.google.com/rss/articles/CBMi5wFBVV95cUxPT255TlZ6ZHNCRV94TG1FSkcyMlN6M0Y0cnlmR0YyUGg5QW1YWUZGV0R6MlpxQnJxb0g4SEdGWkRpdExxcDZldGRtUTRRTlRkTVpvUGRjanJZNzdybzZsdFUwZXY2TlItckpldUY1VTFCOThfTGlkZGQxdUVXcmRhMFFtYzQwSHA4ZFVjUHN6ZTRKQ0VOdWVZbHpxd08wWkNna3pWX1FHOWRxTjFmUm5RZXFYWUZ3LXIwNEJnZUcxQ3FLZ2QyZlFyUUd5dHJuNnRsQngyVU9NOWItZWxqU0dJcFhWSHhJenM?oc=5) ⭐️ 7.0/10

A research project at the University of Texas at Arlington \(UTA\) applies artificial intelligence and satellite data to map small waterbodies and improve drought resilience. The initiative focuses on tracking smaller aquatic features that are often missed by traditional monitoring networks to support better regional water resource management.

rss · Google News: climate and water · Nov 24, 17:04

**「Context」** This research addresses ongoing challenges in hydrological monitoring, where small waterbodies are critical for local ecosystems and agriculture yet difficult to inventory at scale. Utilizing remote sensing and machine learning helps overcome spatial resolution limits inherent in standard satellite observation.

**「Relevance」** This project offers a strong real-world case study for undergraduate or graduate courses in GIS, remote sensing, and environmental management, illustrating how machine learning workflows can be integrated with satellite data for applied hydrological research.

**Tags**: `#remote sensing`, `#GIS`, `#water resources`, `#drought resilience`, `#artificial intelligence`

---

<a id="item-geo-science-edu-7"></a>
### [Western Slope Water Users Mitigate Record Drought](https://news.google.com/rss/articles/CBMi0wJBVV95cUxPQnFhRVotbTV0MGVsY1hUc0dqRy14ZElVZml3M2tLbE80a0N5NGNQTHFZWkV3dVpZRGE5aFFYcXVxWUZBYlp0Q2YxWnRURHZGNFY2VnRrbGd0MkxpSlZ3a3hYOXNMOWN2REV2ZUNNSmMzRlo3M1gyQkNPc2lCYVdNdXR1dldqc2dPYmdyX2ZBaGpRQl85R0dWZmdlZHZod2xsNmVwd0o4Njhvd2dTUU14cmtoUW9BZHV1dl9ZWDZrTi04TVlNQUxDZTVlMDBnNW0xVGlwRVdwNHl6OFVwUFNDeEJqUFdValpic0Y0b0FBal95Sm9QeGFsR1Jfb1lSWnZWbU55ZURwSEZaSlhBbzBaLVVhZFNFLTd5TmpDTWVVWlpSNlV5a01RV3ZkZW9GQmw3ejFnTVJsOGdzcG95SkhES0xrWEpDRzRCMVdDcTZabVM1dEE?oc=5) ⭐️ 7.0/10

According to Aspen Journalism reporting featured on Coyote Gulch, water users on the Western Slope navigated a record-breaking drought by sharing supplies to head off deeper cuts. During this event, one-third of regional stream gauges dropped to all-time lows.

rss · Google News: climate and water · Nov 24, 12:04

**「Context」** This case highlights localized collaborative responses to severe hydrologic stress within the Colorado River basin. The source reports on how cooperative supply sharing helped mitigate the impacts of historic low streamflows, though it does not detail specific long-term limitations or regulatory mechanisms.

**「Relevance」** Faculty can use this regional case study in undergraduate or graduate courses covering water resource management, hydrology, and collaborative governance to illustrate how agricultural and municipal users adapt to extreme drought conditions.

**Tags**: `#drought`, `#water resources`, `#Colorado River`, `#streamflow`, `#regional geography`

---