---
layout: default
title: "Horizon Summary: 2026-11-13 (EN)"
date: 2026-11-13
lang: en
---

> From 451 items, 17 important content pieces were selected

---

**GeoAI and Geospatial Data Science**
1. [Open-Vocabulary Event Anticipation in Global Satellite Imagery](#item-geoai-1) ⭐️ 10.0/10
2. [RICapBench: Fine-Grained Vision-Language Model Benchmarking in Remote Sensing](#item-geoai-2) ⭐️ 9.0/10
3. [Investigating Redundancy and Slimmability in Remote Sensing Foundation Models](#item-geoai-3) ⭐️ 9.0/10
4. [MMEarth-Bench: Evaluating and Adapting Multimodal Earth Observation Models Globally](#item-geoai-4) ⭐️ 9.0/10
5. [AgroOmni: Multi-View Agricultural Dataset and Cross-Scale Reasoning Model](#item-geoai-5) ⭐️ 9.0/10
6. [DisasterVLG: Vision-Language Grounding for Crisis Understanding](#item-geoai-6) ⭐️ 9.0/10
7. [UniFlow-RS Unifies Heterogeneous Remote-Sensing Tasks via Generative Flow Matching](#item-geoai-7) ⭐️ 9.0/10
8. [Fast Slice-Wise Deep Learning Motion Correction for Spinal Cord Functional MRI](#item-geoai-8) ⭐️ 8.0/10
9. [SyntheIce Benchmark and Slope-Aware Algorithm for Englacial Radargram Reconstruction](#item-geoai-9) ⭐️ 8.0/10

**Climate, Geoscience, Teaching and Funding**
1. [Evaluating Tropical Cyclone Representation in JRA-3Q Versus ERA5](#item-geo-science-edu-1) ⭐️ 8.0/10
2. [DaYu-TC: Global-Regional Nested AI for Tropical Cyclone Forecasting](#item-geo-science-edu-2) ⭐️ 8.0/10
3. [HybridCT Accelerates 3D Cloud Tomography Using Machine Learning](#item-geo-science-edu-3) ⭐️ 8.0/10
4. [Upscale Energy Transfer from Mesoscale Convective Systems to African Easterly Waves](#item-geo-science-edu-4) ⭐️ 8.0/10
5. [Data-Driven Reconstruction of ENSO Phase Dynamics and Annual Cycle Synchronization](#item-geo-science-edu-5) ⭐️ 8.0/10
6. [Scaling Global Storm-Resolving AI Atmospheric Simulation with STRATA](#item-geo-science-edu-6) ⭐️ 8.0/10
7. [Coupled Multiscale Paleoclimate Reconstruction via 4D-Var Data Assimilation](#item-geo-science-edu-7) ⭐️ 8.0/10
8. [NASA Space Technology Graduate Research Program Announcement](#item-geo-science-edu-8) ⭐️ 7.0/10

---

## GeoAI and Geospatial Data Science

<a id="item-geoai-1"></a>
### [Open-Vocabulary Event Anticipation in Global Satellite Imagery](https://arxiv.org/abs/2611.16000) ⭐️ 10.0/10

Researchers introduce an open-vocabulary event anticipation framework for satellite imagery that uses vector differences in vision-language model embeddings to detect semantic transformations across time. The authors developed an automated data engine and a global dataset covering over 21,000 locations, 64 event types, and approximately two million PlanetScope and Sentinel-2 images. Evaluated on this multi-source data, the model achieved a 93.5% max F1 score for change detection, outperformed baselines 3.6x in predicted event retrieval, and forecasted completion dates with a three-day median error up to nine months in advance.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** This work addresses the limitation of existing remote sensing systems in jointly identifying where changes occur, what they become, and when they finish across an open vocabulary. It builds on vision-language model embeddings—numerical representations that capture semantic meaning—to automate global event discovery without manual annotation.

**「Application」** Geospatial instructors and researchers can utilize the newly released open-source code and large-scale dataset to teach advanced GeoAI workflows, experiment with change detection methods, or adapt the event anticipation model for monitoring dynamic land-use phenomena.

**Tags**: `#GeoAI`, `#Remote Sensing`, `#Vision-Language Models`, `#Change Detection`, `#Datasets`

---

<a id="item-geoai-2"></a>
### [RICapBench: Fine-Grained Vision-Language Model Benchmarking in Remote Sensing](https://arxiv.org/abs/2611.16413) ⭐️ 9.0/10

The authors introduce RICapBench, a new dataset and evaluation framework designed to test fine-grained vision-language model understanding in remote sensing. The dataset contains 245,466 instance-level annotations and 498,005 spatial relation tuples featuring oriented bounding boxes paired with natural language descriptions. Evaluating 15 prominent models using their composite metric RICScore, the authors identify instance localization as a major performance bottleneck, with LocateAnything achieving the highest score of 31.68.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Existing remote sensing datasets insufficiently assess end-to-end instance localization and captioning without relying on target-specific textual cues. To address this, RICapBench unifies instance localization and fine-grained captioning across general satellite, UAV, and dense small-object scenarios, supported by a specialized spatial relation parser and the RelCap-F1 metric.

**「Application」** Geospatial instructors and researchers can use the open-source RICapBench dataset, evaluation code, and parser to benchmark advanced vision-language models or teach modern GeoAI workflows focusing on instance localization and spatial reasoning.

**Tags**: `#vision-language models`, `#remote sensing`, `#benchmarking`, `#instance localization`, `#spatial relations`

---

<a id="item-geoai-3"></a>
### [Investigating Redundancy and Slimmability in Remote Sensing Foundation Models](https://arxiv.org/abs/2601.22841) ⭐️ 9.0/10

The paper investigates representational redundancy and slimmability in ten state-of-the-art remote sensing foundation models across classification, segmentation, and change detection tasks. Using post-hoc uniform width reduction, the authors demonstrate that remote sensing models retain over 85% relative accuracy under aggressive width reduction, whereas natural image models degrade sharply. The analysis shows that task-relevant variance concentrates in few principal components and is redundantly encoded across model dimensions.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Large-scale remote sensing foundation models generally follow computer vision paradigms, but the source notes that transferring computer vision scaling laws without examination overlooks domain-specific differences. Masked autoencoders and DINOv2 trained on natural images degrade more severely under the same computational constraints, indicating that both dataset characteristics and domain-specific pretraining drive this divergence.

**「Application」** Geospatial instructors and researchers can use the provided open-source code and post-hoc slimming strategies to deploy resource-constrained remote sensing applications more efficiently or incorporate model compression techniques into GeoAI coursework.

**Tags**: `#Remote Sensing`, `#Foundation Models`, `#GeoAI`, `#Model Compression`, `#Representational Redundancy`

---

<a id="item-geoai-4"></a>
### [MMEarth-Bench: Evaluating and Adapting Multimodal Earth Observation Models Globally](https://arxiv.org/abs/2602.06285) ⭐️ 9.0/10

The authors introduce MMEarth-Bench, a globally distributed benchmark comprising five environmental tasks and twelve data modalities with random and geographic test splits. Evaluating diverse pretrained models, the source reports that geographic generalization remains poor despite robust pretraining. To address this limitation, the authors propose test-time training with multimodal reconstruction \(TTT-MMR\), a model-agnostic adaptation method that improves performance across all tested models and tasks.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** This work addresses limitations in geospatial machine learning, where most existing benchmark datasets feature restricted data modalities and poor global representation. Self-supervised learning \(training models on unlabeled data without manual tags\) typically aids downstream tasks with limited labels, but models struggle to adapt to unseen geographic regions or utilize new test-time modalities without explicit adaptation strategies.

**「Application」** Geospatial instructors and researchers can utilize the open-source MMEarth-Bench dataset, code, and visualization tools to evaluate GeoAI models, teach multimodal data integration, or adapt the TTT-MMR method in advanced machine learning coursework.

**Tags**: `#GeoAI`, `#Earth observation`, `#machine learning`, `#benchmark`, `#remote sensing`

---

<a id="item-geoai-5"></a>
### [AgroOmni: Multi-View Agricultural Dataset and Cross-Scale Reasoning Model](https://arxiv.org/abs/2603.14342) ⭐️ 9.0/10

The authors introduce AgroOmni, a large-scale multi-view agricultural training corpus containing 268,119 Visual Question Answering pairs across 56 task categories to bridge the cross-scale gap in Earth observation. Building on this dataset, they release AgroNVILA, a multimodal large language model that achieves a state-of-the-art score of 59.86% on the AgroMind benchmark, mitigating scale confusion between satellite, UAV, and ground-level imagery.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Modern precision agriculture relies on diverse platforms spanning multiple spatial scales, but existing multimodal large language models suffer from ground-level bias and semantic collapse due to a lack of multi-view benchmarks. This work addresses that limitation by releasing fully open training scripts and datasets to improve holistic agricultural perception.

**「Application」** Geospatial instructors and researchers can use the open-source AgroOmni dataset and AgroNVILA training scripts as a benchmark for teaching GeoAI concepts or as a foundation for adapting cross-scale remote sensing models to precision agriculture tasks.

**Tags**: `#GeoAI`, `#multimodal large language models`, `#agriculture`, `#remote sensing`, `#dataset`

---

<a id="item-geoai-6"></a>
### [DisasterVLG: Vision-Language Grounding for Crisis Understanding](https://arxiv.org/abs/2611.12144) ⭐️ 9.0/10

The source reports the release of DisasterVLG, a large-scale dataset and benchmark containing 1.24 million disaster images paired with 33 million structured annotations across 142 countries. It features dense captioning with localization, incident assessment, and evidence-grounded visual question answering, evaluated using a human-verified test set of 38,000 images.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** General-purpose vision-language models often struggle with the noise and ambiguity inherent in crisis imagery. DisasterVLG builds upon prior disaster benchmarks by unifying recognition, grounded reasoning, and uncertainty-aware interpretation instead of focusing narrowly on classification.

**「Application」** Geospatial instructors and researchers can use this open dataset and its trained models to teach advanced multimodal AI workflows, crisis mapping, and geospatial computer vision.

**Tags**: `#GeoAI`, `#Vision-Language Models`, `#Disaster Management`, `#Remote Sensing`, `#Dataset`

---

<a id="item-geoai-7"></a>
### [UniFlow-RS Unifies Heterogeneous Remote-Sensing Tasks via Generative Flow Matching](https://arxiv.org/abs/2611.14281) ⭐️ 9.0/10

UniFlow-RS introduces a unified generative prediction framework for heterogeneous remote-sensing tasks using a shared latent flow-matching predictor and task-modality adaptive timestep sampling. By casting diverse task outputs into structured visual targets in a common latent space and optimizing them with a shared flow-matching objective, the framework handles six tasks and thirteen datasets. The authors report that the model surpasses recent task-specific state-of-the-art methods on several benchmarks while demonstrating strong zero-shot transfer across unseen datasets, occlusions, and false-color imagery.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** While remote-sensing foundation models have increasingly unified representations across sensing modalities, their prediction mechanisms have remained fragmented through task-specific decoders and objectives. UniFlow-RS addresses this limitation by establishing a single shared prediction process and introducing Task-Modality Adaptive Timestep Sampling to mitigate optimization mismatches across differing tasks and modalities.

**「Application」** Geospatial researchers and instructors can use the open-source code and unified model checkpoint as a baseline tool to explore multi-task remote-sensing workflows and teach generative prediction methods in GeoAI curricula.

**Tags**: `#GeoAI`, `#remote sensing`, `#foundation models`, `#flow matching`, `#generative prediction`

---

<a id="item-geoai-8"></a>
### [Fast Slice-Wise Deep Learning Motion Correction for Spinal Cord Functional MRI](https://arxiv.org/abs/2611.14677) ⭐️ 8.0/10

The authors propose a lightweight convolutional neural network for fast slice-wise motion correction in spinal cord functional MRI time series. Trained without motion labels using a two-model approach for large and residual motion, the method was evaluated on 3T and 7T datasets containing 120 and 59 scans respectively. The evaluation shows improvements over the Spinal Cord Toolbox on every metric, increasing tSNR by 10 to 25 percent and reducing DVARS by 20 to 38 percent while running in about 10 seconds per scan—roughly 30 times faster than the Spinal Cord Toolbox.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Respiratory and bulk motion displace the spinal cord between functional MRI volumes, yet general-purpose brain tools register whole volumes rather than handling slice-by-slice cord movement. This method integrates into the established Spinal Cord Toolbox \(SCT v7.4\) and provides an open-source codebase to overcome the speed limitations of traditional alignment techniques.

**「Application」** Geospatial instructors and researchers working with high-resolution sequential imaging data can adopt this open-source deep learning method as a faster alternative for image registration and motion correction pipelines.

**Tags**: `#deep learning`, `#image registration`, `#functional MRI`, `#open-source code`, `#methodology`

---

<a id="item-geoai-9"></a>
### [SyntheIce Benchmark and Slope-Aware Algorithm for Englacial Radargram Reconstruction](https://arxiv.org/abs/2611.14728) ⭐️ 8.0/10

The authors introduce SyntheIce, a synthetic benchmark dataset comprising 600 radargrams with exact ground-truth annotations across multiple complexity levels and noise conditions to support automated englacial layer reconstruction. To process these images, they propose a slope-aware greedy fragment-linking algorithm utilizing row-similarity gating and an exponentially weighted moving average slope predictor, alongside a consistency-based validation framework called XCheck. Evaluations against expert-labeled real radargrams show high precision, recall, F1-score, and mean IoU.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Radio-echo-sounding radargrams capture subsurface ice images that reveal the climate and flow history of ice sheets, but large-scale extraction is traditionally limited by manual annotation and fragmented semi-automated detections. This work addresses the challenge of reconstructing complete layers and validating continuity across adjacent tile boundaries, demonstrating that trajectory-based linking outperforms appearance-based matching when spatial features are fragmented.

**「Application」** Geospatial instructors and researchers can use the SyntheIce dataset and the proposed slope-aware algorithm as a benchmark tool for teaching cryospheric remote sensing or developing automated subsurface feature extraction methods.

**Tags**: `#remote sensing`, `#cryosphere`, `#dataset`, `#radargrams`, `#geospatial data science`

---

## Climate, Geoscience, Teaching and Funding

<a id="item-geo-science-edu-1"></a>
### [Evaluating Tropical Cyclone Representation in JRA-3Q Versus ERA5](https://arxiv.org/abs/2611.15222) ⭐️ 8.0/10

The study evaluates tropical cyclone representation in the JRA-3Q reanalysis by comparing it against ERA5 using the SyCLoPS tracker from 1979 to 2024. The authors report that JRA-3Q achieves a higher detection skill, featuring a 90% hit rate and a 6% false alarm rate. Unlike ERA5, which shows degraded detection skill during the pre-satellite era, JRA-3Q maintains stable performance over the entire period due to reduced model biases and a consistent bogus scheme.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** Atmospheric reanalysis products are widely used for long-term tropical cyclone studies, but the fidelity of their representation has remained incompletely established. The research analyzes errors stemming from tracking algorithms, reanalysis data, and best-track uncertainty, though specific regional limitations are noted in the North Indian basin.

**「Relevance」** This research can be used in graduate-level teaching on climate data limitations or applied in remote sensing and water resources research to select more stable atmospheric reanalysis datasets for historical cyclone analysis.

**Tags**: `#tropical cyclones`, `#climate data`, `#remote sensing`, `#atmospheric reanalysis`

---

<a id="item-geo-science-edu-2"></a>
### [DaYu-TC: Global-Regional Nested AI for Tropical Cyclone Forecasting](https://arxiv.org/abs/2611.15266) ⭐️ 8.0/10

Researchers introduce DaYu-TC, a global-regional nested artificial intelligence system designed to mitigate tropical cyclone intensity underestimation. Evaluated on 16 western North Pacific tropical cyclones in 2023, the global model reduces five-day maximum-wind root-mean-square error \(RMSE\) by 6-22% compared to other global AI models, while regional nesting further reduces maximum-wind RMSE by 22.0-33.1% and minimum-pressure RMSE by 28.6-39.8% across 12 to 120 hours. Furthermore, five-day forecasts execute in under one minute on a single GPU.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** While artificial intelligence weather models have advanced rapidly, persistent intensity underestimation for destructive storms has limited their practical utility. DaYu-TC addresses this by coupling architecture and extreme-aware training objectives with high-resolution regional prediction that incorporates evolving local states. The authors note that the regional model can also enhance other global AI systems without retraining, though evaluations currently focus on a specific regional sample.

**「Relevance」** This framework can be integrated into advanced earth science or GIS courses to discuss machine learning applications in meteorology. In research, the methodology provides a transferable multiscale approach for improving high-impact weather forecasting and analyzing tropical cyclone intensity dynamics.

**Tags**: `#tropical cyclones`, `#artificial intelligence`, `#weather forecasting`, `#climate science`, `#remote sensing`

---

<a id="item-geo-science-edu-3"></a>
### [HybridCT Accelerates 3D Cloud Tomography Using Machine Learning](https://arxiv.org/abs/2611.16255) ⭐️ 8.0/10

Researchers introduce HybridCT, a machine learning-accelerated cloud tomography framework that reconstructs 3D cloud extinction from passive multi-angle observations over 500 times faster than existing physics-based methods. Trained on synthetic 3D cloud fields using nine viewing angles between ±70°, the ML emulator and algebraic reconstruction technique achieve a root-mean-square error of 13.3 km⁻¹ in 3.5 seconds, compared to approximately 30 minutes for the state-of-the-art AT3D framework.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** Low-level clouds remain a primary source of uncertainty in climate predictions due to a lack of detailed 3D internal structure measurements. Cloud optical thickness refers to a cloud&\#x27;s opacity to radiation, while extinction measures how much light is scattered or absorbed per unit distance. The source notes that while HybridCT provides a scalable route for large-scale observations, it relies on synthetic training data.

**「Relevance」** This method can be incorporated into remote sensing research and advanced courses to discuss overcoming computational bottlenecks in radiative-budget interpretation and high-resolution cloud simulation evaluations.

**Tags**: `#cloud tomography`, `#machine learning`, `#remote sensing`, `#climate modeling`, `#radiative transfer`

---

<a id="item-geo-science-edu-4"></a>
### [Upscale Energy Transfer from Mesoscale Convective Systems to African Easterly Waves](https://arxiv.org/abs/2611.16941) ⭐️ 8.0/10

This study investigates how mesoscale convective systems \(MCSs\) drive the growth of African easterly waves \(AEWs\) using two 40-day pan-tropical Met Office Unified Model simulations with approximately 5 km grid spacings. Applying turbulence theory techniques via the LoSSETT software package, the authors calculate interscale kinetic energy transfer to demonstrate that explicitly simulated MCSs exhibit a distinctive upper-tropospheric vertical dipole structure below 1000 km scales. The findings show that upscale energy transfer consistently leads AEW troughs at 200 hPa and contributes directly to the eddy kinetic energy growth of strengthening continental waves.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** African easterly waves govern synoptic variability in West African monsoon rainfall through complex interactions with deep convection. While these multiscale feedbacks are recognized, this research calculates explicit interscale kinetic energy transfer patterns across spatial scales and lifecycle phases for the first time. The authors note that these upscale energy transfer signals remain weak in simulations using parameterised convection, which instead rely on enhanced barotropic conversion from a stronger African Easterly Jet.

**「Relevance」** This paper provides valuable insights into tropical meteorology and multiscale atmospheric dynamics, making it directly applicable for advanced graduate coursework in climate science and atmospheric modeling. Researchers studying convective-scale feedbacks and tropical wave dynamics can use these methodologies and km-scale simulation comparisons to advance theoretical frameworks and improve parameterisation evaluations.

**Tags**: `#tropical meteorology`, `#atmospheric dynamics`, `#climate science`, `#mesoscale convective systems`, `#numerical modeling`

---

<a id="item-geo-science-edu-5"></a>
### [Data-Driven Reconstruction of ENSO Phase Dynamics and Annual Cycle Synchronization](https://arxiv.org/abs/2611.14868) ⭐️ 8.0/10

This study treats the El Niño-Southern Oscillation \(ENSO\) as a rhythmic system periodically forced by the annual cycle, using a data-driven Koopman operator approach and Bayesian inference on sea surface temperature data. The source reports that reconstructed two-variable phase equations reveal statistical 3:1 phase locking between the annual and ENSO cycles. Additionally, stochastic simulations indicate that El Niño and La Niña events last longer when initiating in boreal summer and exhibit greater duration variability when starting in boreal spring.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** The research builds on viewing ENSO as a periodically forced oscillator to examine event seasonality and cycle synchronization. The Koopman operator is a mathematical method used to analyze nonlinear dynamical systems through linear operators acting on observable functions.

**「Relevance」** This methodological framework can be integrated into advanced climate research and graduate-level coursework exploring nonlinear dynamics, data-driven Earth system modeling, and teleconnection synchronization.

**Tags**: `#El Niño-Southern Oscillation`, `#Climate research`, `#Data-driven modeling`, `#Sea surface temperature`, `#Phase dynamics`

---

<a id="item-geo-science-edu-6"></a>
### [Scaling Global Storm-Resolving AI Atmospheric Simulation with STRATA](https://arxiv.org/abs/2606.31248) ⭐️ 8.0/10

Researchers introduce STRATA, an autoregressive AI emulator that achieves global storm-resolving atmospheric simulation at 4.9-km resolution. Trained on 17 days of SCREAM physics model output with 10-minute sampling across ~25 million grid cells, STRATA uses a tile-based transformer architecture with 3D patch embedding and Stereographic Rotary Position Embedding. The model yields stable 24-hour global rollouts achieving 48 simulated days per megawatt-hour—over 50 times greater energy efficiency than traditional physics models—and 741 simulated days per wall-clock day on 512 H100 GPUs.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** Traditional global atmospheric models typically operate at coarse 25-100 km resolutions and approximate critical convection processes, whereas global storm-resolving physics models resolve them explicitly at a prohibitive cost of roughly one megawatt-hour per simulated day. STRATA overcomes this data limitation by leveraging local atmospheric dynamics on 10-minute timescales to trade scarce global temporal samples for abundant local spatial samples using overlapping-tile blending. The source notes that large-scale biases develop with lead time during multi-day rollouts.

**「Relevance」** This preprint offers substantial material for graduate-level courses in computational geoscience, climate modeling, and atmospheric dynamics, specifically for discussing machine learning emulators and kilometer-scale convection. Researchers can adapt STRATA&\#x27;s tile-based transformer approach and Stereographic Rotary Position Embedding to study extreme precipitation and cloud feedbacks without relying on exascale supercomputing resources.

**Tags**: `#artificial intelligence`, `#climate modeling`, `#atmospheric dynamics`, `#remote sensing`, `#computational geoscience`

---

<a id="item-geo-science-edu-7"></a>
### [Coupled Multiscale Paleoclimate Reconstruction via 4D-Var Data Assimilation](https://arxiv.org/abs/2608.19469) ⭐️ 8.0/10

The study introduces the Last Millennium Reanalysis 4D-Var framework to integrate heterogeneous paleoclimate archives without treating them as instantaneous equivalents. By assimilating PAGES2k, Temp12k, and borehole temperature profiles, the framework achieves high skill in reconstructing global mean temperature and 300 to 2000-meter ocean heat content.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** Integrating diverse paleoclimate data that capture varying seasons, time averages, and memory lengths remains a longstanding challenge in climatology. The authors note that the framework balances errors across models, observations, and initial conditions, while modern ocean heat trend comparisons indicate that recent 130-year warming trends exceed pre-1870 Common Era distributions.

**「Relevance」** This methodological advancement can be integrated into graduate-level coursework on climate data assimilation or applied in research focusing on Common Era climate variability and ocean heat content reconstructions.

**Tags**: `#paleoclimate`, `#data assimilation`, `#climate reconstruction`, `#ocean heat content`, `#remote sensing`

---

<a id="item-geo-science-edu-8"></a>
### [NASA Space Technology Graduate Research Program Announcement](https://news.google.com/rss/articles/CBMitAFBVV95cUxOdlcxbm5BdlBQRUxZZ2N2d19LY01iMEYwM3BqX2xjYXBST1NWQzVVd3dJSWtGd0hsUEFWal80azhHUkJSS2xkZWdybzV2bjVMYWxzY2pRYjQwbGU3SUtmZDNza3Bia3k0aXFwMkx3Vm04ZW9pSEtpaklwVkF3Um1uYVkxcGM0RUJIVTQwdDgydGdNc0NWVW5uVmtjeTVLUTg4ZUt2OEI0aHA5LTlMdXZFX3ZvbHrSAboBQVVfeXFMUHBqUlh0RHJRUkN1SklEUnc4WTdlVThmOGc3NnBCZmFqcTJKRXdnY2NELTBBSHRIbno2UWtDRnhLVDZ1Q2xna0N0akVfWjhPNkVQMWJIczAwTkhIaUM1Zmo1MDNjYWxlLWxoRVZGcDF6a0phalphNkpfZ2QxcDh4Ul9VaXNTdkhMU1FyUGdYSzRQZE9YSWN0NWkzd2g1ek5BVGVRRU5DenV1d0ViWExYTnNnRG5ZTTZJZGFn?oc=5) ⭐️ 7.0/10

The source reports a funding opportunity for the NASA Space Technology Graduate Research Program in the United States. It announces grant support aimed at graduate students pursuing space technology and related disciplines.

rss · Google News: research funding · Nov 13, 05:22

**「Context」** This program supports graduate research training to help develop the technological workforce for future space missions. The source note does not provide specific eligibility criteria, award amounts, or submission deadlines.

**「Relevance」** Faculty can share this opportunity with graduate students seeking external fellowships for space technology and remote sensing research. However, specific funding amounts and deadlines must be verified directly through NASA&\#x27;s official solicitation pages.

**Tags**: `#research funding`, `#graduate students`, `#space technology`, `#NASA`

---