---
layout: default
title: "Horizon Summary: 2026-11-13 (EN)"
date: 2026-11-13
lang: en
---

> From 437 items, 13 important content pieces were selected

---

**GeoAI and Geospatial Data Science**
1. [DisasterVLG: Vision-Language Grounding and Evidence-Based Reasoning for Disaster Scene Understanding](#item-geoai-1) ⭐️ 10.0/10
2. [Open-Vocabulary Event Anticipation in Satellite Imagery](#item-geoai-2) ⭐️ 9.0/10
3. [GOOSELoc: Multimodal Off-Road Ground-to-Aerial Localization Benchmark](#item-geoai-3) ⭐️ 9.0/10
4. [RICapBench: Evaluating Vision-Language Models in Remote Sensing](#item-geoai-4) ⭐️ 9.0/10
5. [MMEarth-Bench: Evaluating Multimodal Test-Time Training for Global GeoAI](#item-geoai-5) ⭐️ 9.0/10
6. [AgroOmni: A Multi-View Dataset for Cross-Scale Agricultural Reasoning](#item-geoai-6) ⭐️ 9.0/10
7. [Fast Deep Learning Motion Correction for Spinal Cord fMRI](#item-geoai-7) ⭐️ 8.0/10

**Climate, Geoscience, Teaching and Funding**
1. [Evaluating Tropical Cyclone Representation in JRA-3Q Versus ERA5](#item-geo-science-edu-1) ⭐️ 8.0/10
2. [DaYu-TC: A Global-Regional Nested AI System for Tropical Cyclone Forecasting](#item-geo-science-edu-2) ⭐️ 8.0/10
3. [HybridCT: Machine Learning-Accelerated Tomography for 3D Cloud Observations](#item-geo-science-edu-3) ⭐️ 8.0/10
4. [Upscale Energy Transfer from Convective Systems to African Easterly Waves](#item-geo-science-edu-4) ⭐️ 8.0/10
5. [Scaling Global Storm-Resolving Atmospheric AI Emulation with STRATA](#item-geo-science-edu-5) ⭐️ 8.0/10
6. [Coupled Multiscale Paleoclimate Reconstruction via 4D-Var Data Assimilation](#item-geo-science-edu-6) ⭐️ 8.0/10

---

## GeoAI and Geospatial Data Science

<a id="item-geoai-1"></a>
### [DisasterVLG: Vision-Language Grounding and Evidence-Based Reasoning for Disaster Scene Understanding](https://arxiv.org/abs/2611.12144) ⭐️ 10.0/10

The source reports the release of DisasterVLG, a large-scale, multi-task dataset and benchmark containing 1.24 million disaster images from 142 countries and 33 million structured annotations. The dataset unifies dense captioning, incident assessment, and crisis-grounded visual question answering with evidence-grounded annotations and spatial grounding layers. Experiments demonstrate that domain-adapted vision-language models achieve strong performance, while exposing limitations in general-purpose models.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** General-purpose vision-language models typically struggle with noisy and ambiguous crisis imagery, and prior disaster benchmarks have focused narrowly on basic classification. DisasterVLG addresses this gap by providing a reproducible benchmark for models that must perform grounded reasoning and uncertainty-aware interpretation under real-world disaster conditions.

**「Application」** Geospatial instructors and researchers can use the publicly released DisasterVLG dataset, open code, and trained models as a benchmark for teaching crisis informatics, evaluating vision-language models, or developing GeoAI applications for humanitarian response.

**Tags**: `#GeoAI`, `#Vision-Language Models`, `#Disaster Management`, `#Remote Sensing`, `#Datasets and Benchmarks`

---

<a id="item-geoai-2"></a>
### [Open-Vocabulary Event Anticipation in Satellite Imagery](https://arxiv.org/abs/2611.16000) ⭐️ 9.0/10

Researchers introduce an open-vocabulary satellite event anticipation model paired with an automated data discovery engine that uses vision-language model latent space arithmetic. Trained on a new global dataset of over 21,000 locations and roughly two million PlanetScope and Sentinel-2 images across six continents, the system achieves a 93.5% max F1 score for change detection and forecasts event completion dates with a 3-day median error up to nine months in advance.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** This work addresses the limitation of existing remote sensing systems in jointly identifying where changes occur, what they become, and when they finish across an open vocabulary. It overcomes the bottleneck of manual annotation in petabyte-scale archives by leveraging vision-language model embeddings to search for semantic transformations directly in latent space.

**「Application」** Geospatial instructors and researchers can utilize the publicly available code and dataset to teach advanced GeoAI workflows, explore vision-language model latent space arithmetic, or adopt the event anticipation model for change detection and forecasting tasks.

**Tags**: `#GeoAI`, `#Remote Sensing`, `#Vision-Language Models`, `#Change Detection`, `#Dataset`

---

<a id="item-geoai-3"></a>
### [GOOSELoc: Multimodal Off-Road Ground-to-Aerial Localization Benchmark](https://arxiv.org/abs/2611.16162) ⭐️ 9.0/10

The authors introduce GOOSELoc, an open multimodal benchmark and baseline for cross-view ground-to-aerial localization in unstructured off-road environments. Consisting of 9,356 scenes recorded across four seasons near Munich, Germany, the dataset pairs geo-referenced aerial orthophotos with surround-view RGB imagery and 3D LiDAR point clouds. The authors evaluate four adapted state-of-the-art baselines and propose a multimodal baseline combining RGB and LiDAR geometry to address performance drops caused by unstructured terrain and seasonal appearance variations.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Cross-view pose estimation matches onboard sensor data with geo-referenced overhead imagery when Global Navigation Satellite Systems \(GNSS\) are unreliable. While existing metric cross-view benchmarks like VIGOR and cross-view KITTI focus primarily on structured urban and road scenes, GOOSELoc addresses the lack of off-road datasets covering forests, fields, and rural tracks.

**「Application」** Geospatial instructors and researchers can utilize the open-access GOOSELoc dataset, code, and multimodal baselines to teach advanced GeoAI concepts or test cross-view localization algorithms under challenging seasonal and unstructured off-road conditions.

**Tags**: `#GeoAI`, `#Cross-View Localization`, `#LiDAR`, `#Remote Sensing`, `#Datasets and Benchmarks`

---

<a id="item-geoai-4"></a>
### [RICapBench: Evaluating Vision-Language Models in Remote Sensing](https://arxiv.org/abs/2611.16413) ⭐️ 9.0/10

The authors introduce RICapBench, an open-source dataset, benchmark, and evaluation framework designed to assess fine-grained visual understanding, instance localization, and spatial relation captioning in remote sensing imagery. The dataset features 245,466 instance-level oriented bounding box annotations and 498,005 spatial relation tuples spanning general, UAV, and dense small-object scenarios. Evaluating 15 advanced vision-language models using their proposed composite RICScore metric, the authors identify instance localization as a primary performance bottleneck, with the highest-scoring model, LocateAnything, achieving a RICScore of 31.68.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** While vision-language models have advanced remote sensing analysis, existing benchmarks inadequately test end-to-end instance localization and captioning without target-specific textual cues due to object scale variations and complex spatial relations. Vision-language models \(VLMs\) are artificial intelligence models that process both image and text inputs to perform tasks like image captioning and visual question answering.

**「Application」** Geospatial instructors and researchers can use the open-source RICapBench dataset and code repository to evaluate existing vision-language models or adapt their own GeoAI methods for fine-grained remote sensing tasks.

**Tags**: `#GeoAI`, `#Vision-Language Models`, `#Benchmark Dataset`, `#Remote Sensing`, `#Object Detection`

---

<a id="item-geoai-5"></a>
### [MMEarth-Bench: Evaluating Multimodal Test-Time Training for Global GeoAI](https://arxiv.org/abs/2602.06285) ⭐️ 9.0/10

The authors introduce MMEarth-Bench, a multimodal global benchmark featuring five environmental tasks, 12 data modalities, and both random and geographic evaluation splits. The source reports that while pretrained multimodal models struggle with geographic generalization, the authors&\#x27; proposed model-agnostic test-time training with multimodal reconstruction \(TTT-MMR\) method improves performance across models and tasks using all available test-time modalities.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** This work addresses the limitation that most geospatial benchmarks lack global representation and multi-modality, restricting how pretrained self-supervised models are evaluated. It builds on self-supervised learning approaches for Earth observation data, demonstrating that test-time adaptation can help models leverage abundant auxiliary modalities.

**「Application」** Geospatial instructors and researchers can use the open-source MMEarth-Bench dataset, code, and visualization tools to evaluate model robustness or teach methods for multimodal test-time adaptation in remote sensing workflows.

**Tags**: `#GeoAI`, `#Remote Sensing`, `#Machine Learning`, `#Benchmarking`, `#Multimodal Data`

---

<a id="item-geoai-6"></a>
### [AgroOmni: A Multi-View Dataset for Cross-Scale Agricultural Reasoning](https://arxiv.org/abs/2603.14342) ⭐️ 9.0/10

The authors release AgroOmni, a large-scale multi-view agricultural training corpus containing 268,119 Visual Question Answering pairs across 56 task categories and 14 task types, bridging ground-level photography, UAV observations, and satellite imagery. Using this corpus, they developed AgroNVILA, which achieves a state-of-the-art score of 59.86% on the AgroMind benchmark, overcoming the scale confusion and semantic collapse typical of existing multimodal large language models.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Existing multimodal large language models \(MLLMs\) suffer from severe ground-level bias when handling multi-scale agricultural data, failing to properly integrate macro-priors with micro-diagnostics. This release provides the benchmark data and model training scripts needed to advance cross-scale spatial understanding in precision agriculture.

**「Application」** Geospatial researchers and instructors can utilize the publicly available AgroOmni dataset and AgroNVILA training scripts as a resource for teaching advanced GeoAI multimodal reasoning or for developing localized precision agriculture workflows.

**Tags**: `#GeoAI`, `#Multimodal Models`, `#Precision Agriculture`, `#Remote Sensing`, `#Open Dataset`

---

<a id="item-geoai-7"></a>
### [Fast Deep Learning Motion Correction for Spinal Cord fMRI](https://arxiv.org/abs/2611.14677) ⭐️ 8.0/10

The source reports a lightweight convolutional neural network that performs slice-wise motion correction for spinal cord functional MRI by regressing in-plane translations to align each axial slice. Evaluated on 3T and 7T datasets, the method runs in about 10 seconds per scan—roughly 30 times faster than the Spinal Cord Toolbox \(SCT\)—while improving temporal signal-to-noise ratio by 10 to 25 percent and reducing DVARS by 20 to 38 percent. The authors have released the code on GitHub and integrated the method into SCT v7.4.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Spinal cord functional MRI suffers from artifacts caused by respiratory and bulk motion that displace the cord slice-by-slice rather than as a rigid whole volume. This deep learning approach addresses the slow processing speeds of traditional tools like SCT and the limitations of whole-volume brain registration methods.

**「Application」** Instructors and researchers can use the open-source code and its integration in SCT v7.4 to accelerate preprocessing workflows for spinal cord imaging datasets.

**Tags**: `#Geospatial AI`, `#Medical Imaging`, `#Deep Learning`, `#Open Source`, `#Methodology`

---

## Climate, Geoscience, Teaching and Funding

<a id="item-geo-science-edu-1"></a>
### [Evaluating Tropical Cyclone Representation in JRA-3Q Versus ERA5](https://arxiv.org/abs/2611.15222) ⭐️ 8.0/10

The study evaluates tropical cyclone \(TC\) representation in the JRA-3Q reanalysis against ERA5 for the 1979–2024 period using the SyCLoPS tracker. JRA-3Q achieves a 90% hit rate and a 6% false alarm rate, maintaining temporally stable performance across the pre-satellite and satellite eras. The authors report that JRA-3Q&\#x27;s improvements stem from reduced model biases and a more consistently applied TC bogus scheme, supported by error decompositions across tracking, reanalysis, and best-track data.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** Reanalysis products are heavily relied upon for long-term climate and meteorological studies, but their fidelity in capturing extreme events like tropical cyclones requires ongoing benchmarking. While ERA5 exhibits degraded detection skill prior to the satellite era, JRA-3Q demonstrates greater temporal stability. However, the analysis highlights remaining uncertainties tied to best-track observational datasets and tracking algorithm configurations.

**「Relevance」** This paper provides valuable insights for researchers selecting atmospheric datasets for climatology and extreme weather research. It can also be incorporated into advanced meteorology and geographic information science courses to discuss the limitations and comparative strengths of modern global reanalysis products.

**Tags**: `#tropical cyclones`, `#reanalysis data`, `#climate research`, `#remote sensing`, `#meteorology`

---

<a id="item-geo-science-edu-2"></a>
### [DaYu-TC: A Global-Regional Nested AI System for Tropical Cyclone Forecasting](https://arxiv.org/abs/2611.15266) ⭐️ 8.0/10

The authors report the development of DaYu-TC, a global-regional nested artificial intelligence system designed to improve tropical cyclone intensity forecasts. In an independent evaluation of 16 western North Pacific tropical cyclones in 2023, the system reduced five-day maximum-wind root-mean-square error by 22-33% and minimum-pressure root-mean-square error by 29-40% compared to its global model. Five-day forecasts run in under one minute on a single graphics processing unit.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** This work addresses persistent intensity underestimation in artificial intelligence weather models, which limits their effectiveness for predicting destructive tropical cyclones. The approach links large-scale environmental data with high-resolution regional evolution using extreme-aware training objectives. The study notes that the regional model can also enhance other global artificial intelligence models without requiring retraining.

**「Relevance」** This research provides a case study for graduate-level courses in atmospheric sciences or machine learning applications for geosciences, highlighting multiscale model nesting and extreme weather prediction. Researchers can explore the transferable regional architecture to improve high-impact weather forecasting in their own modeling frameworks.

**Tags**: `#Artificial Intelligence`, `#Tropical Cyclones`, `#Weather Forecasting`, `#Remote Sensing`, `#Climate Science`

---

<a id="item-geo-science-edu-3"></a>
### [HybridCT: Machine Learning-Accelerated Tomography for 3D Cloud Observations](https://arxiv.org/abs/2611.16255) ⭐️ 8.0/10

The source reports on HybridCT, a machine learning-accelerated cloud tomographic reconstruction scheme that recovers three-dimensional cloud extinction from passive multi-angle observations. The framework uses a machine learning emulator to map radiances from nine viewing angles between plus or minus 70 degrees to cloud optical thickness, followed by an algebraic reconstruction technique to retrieve 3D extinction. HybridCT achieves a root mean square error of 13.3 inverse kilometers in 3.5 seconds, delivering a speedup exceeding 500-fold compared to the state-of-the-art physics-based framework AT3D.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** Low-level clouds represent a major source of uncertainty in climate predictions due to a lack of detailed three-dimensional measurements of their internal structure. HybridCT addresses this limitation by offering a scalable approach for large-scale observations relevant to radiative-budget interpretation and the evaluation of high-resolution cloud simulations.

**「Relevance」** This methodology can be incorporated into advanced remote sensing and atmospheric science courses to discuss modern machine learning applications in climate research. Researchers can also utilize this framework to process large volumes of multi-angle satellite or airborne observations for high-resolution cloud modeling.

**Tags**: `#Climate Science`, `#Remote Sensing`, `#Machine Learning`, `#Atmospheric Science`

---

<a id="item-geo-science-edu-4"></a>
### [Upscale Energy Transfer from Convective Systems to African Easterly Waves](https://arxiv.org/abs/2611.16941) ⭐️ 8.0/10

This study investigates how upscale kinetic energy feedbacks from mesoscale convective systems \(MCSs\) drive the growth and evolution of African easterly waves \(AEWs\). Using two 40-day Met Office Unified Model simulations with approximately 5 km grid spacings and turbulence theory techniques via the LoSSETT package, the authors calculate interscale kinetic energy transfer across spatial scales around MCSs. The findings reveal a distinctive vertical dipole structure of energy transfer below 1000 km, with strong upper-tropospheric upscale transfer in storm anvils that consistently leads AEW troughs.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** The research addresses multiscale interactions in tropical meteorology, where AEWs govern West African monsoon rainfall variability through complex two-way interactions with convection. While explicit convection simulations highlight crucial upscale energy transfers during AEW growth, simulations utilizing parameterized convection instead rely primarily on barotropic conversion from a stronger African Easterly Jet.

**「Relevance」** This preprint provides valuable methodological and physical insights that can be incorporated into advanced undergraduate or graduate courses in atmospheric science and tropical dynamics. Researchers studying multiscale atmospheric interactions and kilometer-scale climate modeling can also use these turbulence-theory diagnostics to evaluate convective parameterizations.

**Tags**: `#Tropical Meteorology`, `#Mesoscale Convective Systems`, `#African Easterly Waves`, `#Atmospheric Dynamics`, `#Climate Modeling`

---

<a id="item-geo-science-edu-5"></a>
### [Scaling Global Storm-Resolving Atmospheric AI Emulation with STRATA](https://arxiv.org/abs/2606.31248) ⭐️ 8.0/10

Researchers introduce STRATA, an autoregressive AI emulator designed for global storm-resolving atmospheric simulation at a 4.9-km resolution utilizing 25 million grid cells. Trained on 17 days of SCREAM physics model output sampled every 10 minutes, STRATA achieves stable 24-hour global rollouts. The model demonstrates high computational efficiency, delivering 48 simulated days per megawatt-hour and 741 simulated days per wall-clock day on 512 H100 GPUs.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** This work addresses the extreme computational costs of traditional global storm-resolving physics models, which consume roughly one megawatt-hour per simulated day on exascale supercomputers. STRATA overcomes scarce global temporal samples by training on small spatial tiles based on the premise that 10-minute atmospheric dynamics are predominantly local. While efficient, the source notes that large-scale biases develop in the model with increased lead time.

**「Relevance」** Faculty can incorporate this study into remote sensing and climate modeling courses to discuss high-resolution convection, tile-based machine learning approaches, and the energy efficiency of AI emulators versus traditional physics solvers. In research, the architecture provides a benchmark for developing kilometer-scale weather models and exploring localized spatial training strategies.

**Tags**: `#Climate Modeling`, `#Artificial Intelligence`, `#Remote Sensing`, `#Atmospheric Science`, `#High-Performance Computing`

---

<a id="item-geo-science-edu-6"></a>
### [Coupled Multiscale Paleoclimate Reconstruction via 4D-Var Data Assimilation](https://arxiv.org/abs/2608.19469) ⭐️ 8.0/10

Researchers introduce the Last Millennium Reanalysis 4D-Var \(LMR4D-Var\) framework to integrate heterogeneous paleoclimate archives and improve climate trajectory reconstructions. The study assimilates proxy data from PAGES2k, Temp12k, and borehole temperature profiles, avoiding treating them as instantaneous equivalents. Instrumental validation shows that LMR4D-Var achieves the highest global mean temperature reconstruction skill among existing methods, while borehole assimilation yields a cooler Little Ice Age ocean and shows modern 130-year ocean heat content trends exceeding pre-1870 Common Era distributions.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** This work addresses the longstanding challenge of unifying diverse paleoclimate archives that register different seasons, variables, and time averages into a single methodology that balances model, observation, and initial condition errors. The authors note that Temp12k assimilation demonstrates the potential for Holocene and deeper-time applications when paired with suitable emulators.

**「Relevance」** This framework provides advanced methodological concepts and validation examples suitable for graduate-level earth science or paleoclimatology courses focusing on data assimilation. Researchers studying long-term climate dynamics and ocean heat content can utilize these techniques to better integrate multi-proxy archives.

**Tags**: `#paleoclimate`, `#data assimilation`, `#climate reconstruction`, `#ocean heat content`, `#remote sensing and modeling`

---