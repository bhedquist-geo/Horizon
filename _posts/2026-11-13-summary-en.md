---
layout: default
title: "Horizon Summary: 2026-11-13 (EN)"
date: 2026-11-13
lang: en
---

> From 451 items, 16 important content pieces were selected

---

**GeoAI and Geospatial Data Science**
1. [Open-Vocabulary Event Anticipation in Satellite Imagery](#item-geoai-1) ⭐️ 9.0/10
2. [RICapBench: A Fine-Grained Visual Benchmark for Remote Sensing VLMs](#item-geoai-2) ⭐️ 9.0/10
3. [SpotDiff: Zero-Shot Remote Sensing Change Detection via Vision Foundation Models](#item-geoai-3) ⭐️ 9.0/10
4. [SkillEarth: Self-Evolving Skill Extraction for Remote Sensing Agents](#item-geoai-4) ⭐️ 9.0/10
5. [Enhancing UAV Image Perception with Vision-Language Models Using AerialVP](#item-geoai-5) ⭐️ 9.0/10
6. [Redundancy and Slimmability in Remote Sensing Foundation Models](#item-geoai-6) ⭐️ 9.0/10
7. [MMEarth-Bench: Evaluating Multimodal Geospatial Model Adaptation and Generalization](#item-geoai-7) ⭐️ 9.0/10
8. [AgroOmni: Multi-View Agricultural Dataset and Multimodal Model](#item-geoai-8) ⭐️ 9.0/10
9. [DisasterVLG: Vision-Language Grounding for Disaster Scene Understanding](#item-geoai-9) ⭐️ 9.0/10

**Climate, Geoscience, Teaching and Funding**
1. [Evaluating Tropical Cyclone Representation in JRA-3Q Versus ERA5](#item-geo-science-edu-1) ⭐️ 8.0/10
2. [DaYu-TC: A Global-Regional Nested AI System for Tropical Cyclone Forecasting](#item-geo-science-edu-2) ⭐️ 8.0/10
3. [HybridCT: Machine Learning Accelerated 3D Cloud Tomography](#item-geo-science-edu-3) ⭐️ 8.0/10
4. [Upscale Energy Transfer from Mesoscale Convective Systems to African Easterly Waves](#item-geo-science-edu-4) ⭐️ 8.0/10
5. [Scaling Storm-Resolving Atmospheric AI Simulation Globally](#item-geo-science-edu-5) ⭐️ 8.0/10
6. [Coupled Multiscale Paleoclimate Reconstruction Using 4D-Var Data Assimilation](#item-geo-science-edu-6) ⭐️ 8.0/10
7. [Predicting Climate Tipping Points and Early-Warning Signals](#item-geo-science-edu-7) ⭐️ 8.0/10

---

## GeoAI and Geospatial Data Science

<a id="item-geoai-1"></a>
### [Open-Vocabulary Event Anticipation in Satellite Imagery](https://arxiv.org/abs/2611.16000) ⭐️ 9.0/10

Researchers introduce an open-vocabulary event anticipation framework for satellite imagery that uses vector differences in vision-language model embeddings to identify changes across time. The authors developed an automated data engine to build a global dataset containing over 21,000 locations and approximately two million PlanetScope and Sentinel-2 images across six continents. Their global-scale model achieved a 93.5% max F1 score for change detection, outperformed baselines 3.6x on predicted event retrieval, and forecast completion dates with a 3-day median error up to nine months in advance.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** This work addresses the limitation of existing remote sensing systems that struggle to jointly identify where a change occurs, what it will become, and when it will finish across an open vocabulary. Vision-language models use joint embeddings to connect textual concepts with visual representations, allowing the framework to detect semantic transformations directly in latent space without manual annotation.

**「Application」** Geospatial instructors and researchers can utilize the open-source code and massive dataset to study advanced GeoAI methods, explore vision-language model embeddings in remote sensing, and teach modern change detection pipelines.

**Tags**: `#GeoAI`, `#Satellite Imagery`, `#Remote Sensing`, `#Vision-Language Models`, `#Change Detection`

---

<a id="item-geoai-2"></a>
### [RICapBench: A Fine-Grained Visual Benchmark for Remote Sensing VLMs](https://arxiv.org/abs/2611.16413) ⭐️ 9.0/10

The authors introduce RICapBench, a benchmark dataset and evaluation framework designed to assess vision-language models on fine-grained remote sensing tasks. The dataset comprises 245,466 instance-level annotations with oriented bounding boxes and 498,005 spatial relation tuples across satellite, UAV, and dense small-object imagery. To measure performance, the authors propose the RelCap-F1 metric and a composite RICScore, which evaluates 15 prominent vision-language models and identifies instance localization as a primary performance bottleneck.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** This work addresses the limitation of existing remote sensing datasets in supporting end-to-end instance localization and captioning without reliance on target-specific textual cues. By combining object-level oriented bounding boxes with natural language descriptions of attributes and spatial relations, the benchmark builds upon current vision-language model evaluations in geospatial artificial intelligence.

**「Application」** Geospatial instructors and researchers can use the open-source dataset, code, and evaluation metrics as a benchmark suite to test vision-language models, design GeoAI coursework, or adapt methods for fine-grained remote sensing image analysis.

**Tags**: `#vision-language models`, `#remote sensing`, `#benchmark dataset`, `#GeoAI`, `#spatial reasoning`

---

<a id="item-geoai-3"></a>
### [SpotDiff: Zero-Shot Remote Sensing Change Detection via Vision Foundation Models](https://arxiv.org/abs/2611.17172) ⭐️ 9.0/10

The source reports on SpotDiff, a training-free framework for zero-shot remote sensing change detection that combines vision foundation models—specifically DINOv3, AnyUp, and SAM 3—without needing annotated training data. Evaluated on benchmarks, SpotDiff achieves 82.46 F1 on LEVIR-CD and improves building change detection by 10.3 IoU on the SECOND benchmark, while demonstrating cross-resolution transferability on PlanetScope and Sentinel-2 imagery.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Traditional remote sensing change detection relies heavily on large collections of pixel-level annotations, which limits scalability across imaging platforms. SpotDiff addresses this by composing complementary foundation models, using a universal feature upsampler \(AnyUp\) and an inference-time multi-scale strategy \(SWIMS\) to localize fine-grained changes reliably across time.

**「Application」** Geospatial instructors and researchers can use SpotDiff as a plug-and-play method for label-free change detection, teaching students how modern vision foundation models compose together to process multi-resolution satellite imagery without fine-tuning.

**Tags**: `#change detection`, `#vision foundation models`, `#remote sensing`, `#zero-shot learning`, `#GeoAI`

---

<a id="item-geoai-4"></a>
### [SkillEarth: Self-Evolving Skill Extraction for Remote Sensing Agents](https://arxiv.org/abs/2611.15481) ⭐️ 9.0/10

The source reports on SkillEarth, a self-evolving skill extraction framework designed to equip general-purpose remote sensing agents with reusable tool-call knowledge without model retraining. The method externalizes tool interactions into retrievable skill files, refining them through observation-grounded evolution, dual-judge feedback, and a grounded observation routing graph. Evaluated on OpenEarth-Bench and Earth-Bench, the source claims SkillEarth improves tool selection, argument correctness, execution-order consistency, and task completion across multiple frontier and open-source large language models.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Remote sensing agents typically rely on predefined expertise or parameter updates to execute complex workflows, limiting their adaptability when new tools or tasks emerge. SkillEarth builds on automated skill extraction by shifting from outcome-based reflection to precise, component-level refinement grounded in real tool-chain execution feedback.

**「Application」** Geospatial instructors and researchers can use OpenEarth-Bench and Earth-Bench alongside the SkillEarth framework as a benchmark and method to teach or study advanced GeoAI agent workflows and modular tool-use strategies.

**Tags**: `#GeoAI`, `#remote sensing`, `#agents`, `#machine learning`, `#tool use`

---

<a id="item-geoai-5"></a>
### [Enhancing UAV Image Perception with Vision-Language Models Using AerialVP](https://arxiv.org/abs/2512.07302) ⭐️ 9.0/10

The authors introduce AerialVP, a training-free prompt-enhancement agent designed to improve vision-language model performance on unmanned aerial vehicle image perception tasks. By utilizing an LLM-based task engine to dynamically integrate image-derived semantics, spatial positions, and object relationships into enhanced prompts, AerialVP avoids parameter optimization while handling small and densely distributed objects in cluttered backgrounds. Alongside the method, the authors present AerialSense, a unified benchmark covering aerial visual grounding, reasoning, and question answering, and report consistent performance improvements across diverse vision-language models.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Vision-language models often struggle with concise prompts in aerial imagery due to small targets and complex backgrounds, while traditional task-specific fine-tuning demands costly large-scale annotations and model updates. This work builds on prompt-centric adaptation strategies to improve image-text alignment without altering backend model parameters.

**「Application」** Geospatial instructors and researchers can use the open-source code and the AerialSense benchmark as a tool to evaluate vision-language models or as a method to adapt existing models for UAV visual grounding, reasoning, and question-answering tasks without requiring retraining.

**Tags**: `#GeoAI`, `#Vision-Language Models`, `#UAV imagery`, `#Remote Sensing`, `#Object Detection`

---

<a id="item-geoai-6"></a>
### [Redundancy and Slimmability in Remote Sensing Foundation Models](https://arxiv.org/abs/2601.22841) ⭐️ 9.0/10

The study investigates representation redundancy and post-hoc slimmability across ten remote sensing foundation models using uniform width reduction of pretrained encoder transformer blocks. The authors report that these models retain over 85% relative accuracy on classification datasets under aggressive width reduction, whereas natural image models degrade sharply under matched computational constraints. The evaluation spans multiple downstream tasks including classification, segmentation, and change detection, supported by open-source code.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** This work evaluates whether computer vision scaling laws properly transfer to remote sensing foundation models, suggesting that remote sensing models enter an overparameterized regime at much smaller scales. The findings indicate that both dataset characteristics and domain-specific pretraining contribute to high representational redundancy.

**「Application」** Geospatial instructors and researchers can use the provided open-source repository as a practical tool for deploying efficient models in resource-constrained environments or as a methodology to teach model efficiency and representation analysis in GeoAI courses.

**Tags**: `#remote sensing`, `#foundation models`, `#GeoAI`, `#model efficiency`, `#spatial data science`

---

<a id="item-geoai-7"></a>
### [MMEarth-Bench: Evaluating Multimodal Geospatial Model Adaptation and Generalization](https://arxiv.org/abs/2602.06285) ⭐️ 9.0/10

The authors introduce MMEarth-Bench, a globally distributed benchmark comprising five environmental tasks with 12 data modalities and both random and geographic test splits. Evaluating diverse pretrained models, the authors find that geographic generalization remains poor despite robust performance on limited data. To address this limitation, they propose test-time training with multimodal reconstruction \(TTT-MMR\), a model-agnostic method that leverages all available test-time modalities as auxiliary tasks to improve performance.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** This work builds on self-supervised learning for Earth observation by addressing the lack of globally representative, multimodal benchmark datasets in geospatial machine learning. Test-time training adapts pretrained models during inference using unlabelled target data, helping overcome distribution shifts between training regions and deployment areas.

**「Application」** Geospatial instructors and researchers can utilize the open-source MMEarth-Bench dataset, code, and visualization tools to evaluate multimodal foundation models or teach advanced GeoAI adaptation techniques like test-time training.

**Tags**: `#GeoAI`, `#Remote Sensing`, `#Machine Learning`, `#Benchmarks`, `#Test-Time Training`

---

<a id="item-geoai-8"></a>
### [AgroOmni: Multi-View Agricultural Dataset and Multimodal Model](https://arxiv.org/abs/2603.14342) ⭐️ 9.0/10

The authors introduce AgroOmni, a large-scale multi-view agricultural training corpus containing 268,119 Visual Question Answering pairs across 56 task categories and 14 task types, spanning ground-level, UAV, and satellite imagery. Using this dataset, they developed AgroNVILA, a vision-language model that achieves a state-of-the-art score of 59.86% on the AgroMind benchmark. The source reports that AgroNVILA effectively mitigates multi-view cross-scale gaps and demonstrates strong generalization capabilities.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** Modern agricultural remote sensing utilizes diverse platforms ranging from ground photography to satellite observation, requiring robust cross-scale spatial understanding. The authors note that existing multimodal large language models suffer from ground-level bias and scale confusion because suitable multi-view benchmarks were lacking.

**「Application」** Geospatial instructors and researchers can utilize the publicly released AgroOmni dataset and AgroNVILA training scripts as a resource for teaching cross-scale remote sensing or as a foundation for developing and testing GeoAI spatial reasoning pipelines.

**Tags**: `#GeoAI`, `#Multimodal Models`, `#Agricultural Remote Sensing`, `#UAV Imagery`, `#Dataset Release`

---

<a id="item-geoai-9"></a>
### [DisasterVLG: Vision-Language Grounding for Disaster Scene Understanding](https://arxiv.org/abs/2611.12144) ⭐️ 9.0/10

The authors introduce DisasterVLG, a large-scale dataset and benchmark containing 1.24 million disaster images from 142 countries paired with 33 million structured annotations. The dataset covers dense captioning with localization, incident assessment, and crisis-grounded visual question answering across diverse global hazards. Evaluated using a human-verified test set of 38,000 images, domain-adapted models demonstrate strong performance while exposing limitations in general-purpose vision-language models.

rss · arXiv cs.CV · Nov 13, 05:00

**「Context」** General-purpose vision-language models struggle with noisy and ambiguous crisis imagery, and prior disaster benchmarks have focused narrowly on basic image classification. DisasterVLG addresses this gap by unifying recognition, grounded reasoning, and uncertainty-aware interpretation with evidence-grounded annotations that link visual observations directly to textual answers.

**「Application」** Geospatial instructors and researchers can use the publicly released dataset, code, and models as a benchmark to evaluate vision-language models or as a training resource for advanced GeoAI and crisis informatics research.

**Tags**: `#GeoAI`, `#Vision-Language Models`, `#Disaster Management`, `#Remote Sensing`, `#Datasets and Benchmarks`

---

## Climate, Geoscience, Teaching and Funding

<a id="item-geo-science-edu-1"></a>
### [Evaluating Tropical Cyclone Representation in JRA-3Q Versus ERA5](https://arxiv.org/abs/2611.15222) ⭐️ 8.0/10

This research evaluates the representation of tropical cyclones in the JRA-3Q reanalysis by comparing it with the higher-resolution ERA5 dataset using the SyCLoPS tracker over the period 1979-2024. The source reports that JRA-3Q achieves a 90% hit rate and a 6% false alarm rate, demonstrating substantially higher detection skill. Furthermore, JRA-3Q maintains stable temporal performance without the pre-satellite era degradation observed in ERA5, driven by reduced model biases and an effective TC bogus scheme.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** Reanalysis products integrate historical observations with numerical weather prediction models to simulate the atmosphere, yet their fidelity for long-term tropical cyclone studies remains imperfect. The analysis attributes JRA-3Q&\#x27;s performance gains to its TC bogus scheme—an artificial insertion of a vortex to represent a storm—and error decomposition methods, though uncertainties related to tracking algorithms and best-track data remain.

**「Relevance」** This study is valuable for teaching advanced earth science or GIS and remote sensing courses that utilize global climate reanalysis datasets. Researchers studying climatology and tropical meteorology can use these findings to select more robust atmospheric products for long-term storm tracking and trend analysis.

**Tags**: `#Climate Science`, `#Tropical Cyclones`, `#Atmospheric Reanalysis`, `#Remote Sensing`

---

<a id="item-geo-science-edu-2"></a>
### [DaYu-TC: A Global-Regional Nested AI System for Tropical Cyclone Forecasting](https://arxiv.org/abs/2611.15266) ⭐️ 8.0/10

The source reports on DaYu-TC, a global-regional nested AI system designed to improve tropical cyclone intensity forecasts by overcoming the traditional underestimation of strong winds and low pressures. Evaluated on 16 western North Pacific tropical cyclones from 2023, the global model reduced five-day maximum-wind root-mean-square error \(RMSE\) by 6-22% compared to other AI models, while regional nesting achieved further RMSE reductions of 22.0-33.1% for maximum wind and 28.6-39.8% for minimum pressure. Complete system forecasts run in under one minute on a single GPU.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** This work builds on AI weather prediction models that often struggle with high-impact storm intensity due to the dampening of extreme wind and pressure signals. The system uses extreme-aware training objectives and links large-scale environmental data with high-resolution regional evolution. Evaluations are limited to a specific set of western North Pacific storms in 2023, and the source notes that performance depends on coupling global forecasts with local regional states.

**「Relevance」** This framework can be integrated into graduate-level meteorology courses covering machine learning applications in atmospheric science or utilized in research focused on high-impact weather forecasting and multiscale modeling. Researchers can also apply its transferable regional nesting approach to improve existing global AI weather models without retraining.

**Tags**: `#tropical cyclones`, `#artificial intelligence`, `#weather forecasting`, `#remote sensing`, `#climate science`

---

<a id="item-geo-science-edu-3"></a>
### [HybridCT: Machine Learning Accelerated 3D Cloud Tomography](https://arxiv.org/abs/2611.16255) ⭐️ 8.0/10

The study introduces HybridCT, a machine learning-accelerated tomographic framework that reconstructs 3D cloud extinction from passive multi-angle observations. Using an ML emulator to map radiances to cloud optical thickness and a Simultaneous Algebraic Reconstruction Technique to invert projections, HybridCT achieves a 500x speedup over the state-of-the-art AT3D framework. It reconstructs extinction with an RMSE of 13.3 per kilometer in 3.5 seconds, compared to 30 minutes for AT3D, using synthetic training data from radiative transfer simulations across nine viewing angles between plus and minus 70 degrees.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** Low-level clouds represent a major source of uncertainty in climate predictions due to a historical lack of detailed 3D internal structure measurements. HybridCT addresses this limitation by offering a scalable pathway for large-scale observations essential for interpreting Earth&\#x27;s radiative budget and evaluating high-resolution cloud simulations.

**「Relevance」** This framework serves as a cutting-edge case study for advanced remote sensing or atmospheric science courses to discuss machine learning applications in Earth sciences. In research, the methodology can be adopted for processing multi-angle imagery to improve cloud feedback analysis and climate model evaluation.

**Tags**: `#Climate Science`, `#Remote Sensing`, `#Machine Learning`, `#Atmospheric Research`, `#Cloud Tomography`

---

<a id="item-geo-science-edu-4"></a>
### [Upscale Energy Transfer from Mesoscale Convective Systems to African Easterly Waves](https://arxiv.org/abs/2611.16941) ⭐️ 8.0/10

The study reports explicit upscale kinetic energy transfer from mesoscale convective systems \(MCSs\) to African easterly waves \(AEWs\) within the West African monsoon. Using 40-day pan-tropical Met Office Unified Model simulations with approximately 5 km grid spacings and turbulence theory diagnostics, the authors find a distinctive upper-troposphere vertical dipole structure of energy transfer at scales below 1,000 km. This upscale transfer prominently leads AEW troughs at 200 hPa and contributes to the eddy kinetic energy growth of strengthening continental AEWs.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** This work builds on understanding multiscale interactions in the tropical atmosphere, specifically how deep convection influences larger-scale circulations. The authors contrast explicitly simulated convection with a simulation using parameterised convection, where upscale signals are weaker and barotropic conversion from a stronger African Easterly Jet dominates. Limitations include reliance on two 40-day model simulations and specific turbulence theory metrics calculated via the LoSSETT software package.

**「Relevance」** This preprint provides valuable methodological insights and turbulence theory applications that can be integrated into graduate-level research and coursework in tropical meteorology, climate dynamics, and high-resolution numerical modeling.

**Tags**: `#tropical meteorology`, `#climate dynamics`, `#mesoscale convective systems`, `#numerical modeling`, `#energy transfer`

---

<a id="item-geo-science-edu-5"></a>
### [Scaling Storm-Resolving Atmospheric AI Simulation Globally](https://arxiv.org/abs/2606.31248) ⭐️ 8.0/10

Researchers introduce STRATA, a tile-based autoregressive AI transformer architecture that emulates global storm-resolving atmospheric dynamics at 4.9-km resolution. Trained on 17 days of high-resolution SCREAM physics-model output featuring 25 million grid cells, STRATA achieves 741 simulated days per wall-clock day on 512 H100 GPUs and delivers 48 simulated days per megawatt-hour, representing a major efficiency gain over traditional numerical models.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** Kilometer-scale convection critically shapes precipitation extremes and cloud feedbacks, but traditional global physics models demand massive computational resources, consuming roughly one megawatt-hour per simulated day on exascale supercomputers. STRATA addresses this bottleneck by leveraging local spatial tiles and overlapping-tile blending to enable stable 24-hour global rollouts, although the study notes that large-scale biases develop as lead times increase.

**「Relevance」** This architecture provides an accessible computational case study for earth science and geographic information science coursework examining machine learning applications in climate modeling. Researchers can also utilize these findings to explore high-performance computing strategies for processing kilometer-scale atmospheric datasets.

**Tags**: `#Climate Modeling`, `#Artificial Intelligence`, `#Atmospheric Science`, `#Remote Sensing`, `#High-Performance Computing`

---

<a id="item-geo-science-edu-6"></a>
### [Coupled Multiscale Paleoclimate Reconstruction Using 4D-Var Data Assimilation](https://arxiv.org/abs/2608.19469) ⭐️ 8.0/10

Researchers introduce LMR4D-Var, a four-dimensional variational data-assimilation framework designed to integrate heterogeneous paleoclimate archives—including PAGES2k, Temp12k, and borehole temperature profiles—without treating them as instantaneous equivalents. Instrumental validation shows that LMR4D-Var achieves the highest skill in reconstructing global mean temperature among existing methods. Furthermore, the assimilation preserves skill against withheld annual records and yields a cooler Little Ice Age ocean.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** This framework addresses the longstanding challenge of combining paleoclimate archives that register different seasons, variables, time averages, and memory lengths while balancing errors in models, observations, and initial conditions. The authors note that modern 130-year ocean heat content trends in the 0-300-m and 300-2000-m layers exceed pre-1870 Common Era trend distributions.

**「Relevance」** This paper provides strong methodological concepts and validation examples suitable for advanced earth science or climate courses focusing on data assimilation and paleoclimatology. It can also support faculty research into past climate trajectories and ocean heat content dynamics.

**Tags**: `#paleoclimate`, `#data assimilation`, `#climate reconstruction`, `#ocean heat content`, `#remote sensing`

---

<a id="item-geo-science-edu-7"></a>
### [Predicting Climate Tipping Points and Early-Warning Signals](https://arxiv.org/abs/2609.10378) ⭐️ 8.0/10

A recent research preprint examines the mathematical complexities and predictability limits of early-warning signals for climate tipping points. The author highlights how out-of-equilibrium dynamics, chaos, and rapidly changing climate conditions blur critical thresholds and hinder the fidelity of these warning signals.

rss · arXiv physics.ao-ph · Nov 13, 05:00

**「Context」** This work builds on growing concerns that simulations show abrupt climate transitions under moderate greenhouse gas scenarios. The preprint notes that using early-warning signals to detect local stability loss faces serious limitations in highly multistable climate systems with multiple alternative states.

**「Relevance」** This paper can be integrated into advanced earth science or climate modeling courses to discuss the limitations of early-warning indicators. Researchers studying dynamical systems can use these insights to motivate new methods based on non-equilibrium statistical mechanics.

**Tags**: `#climate tipping points`, `#early-warning signals`, `#dynamical systems`, `#climate research`, `#non-equilibrium dynamics`

---