---
layout: default
title: "Horizon Summary: 2026-11-18 (EN)"
date: 2026-11-18
lang: en
---

> From 396 items, 16 important content pieces were selected

---

**GeoAI and Geospatial Data Science**
1. [SARVIA: Fast-Adapting Multimodal Models for Synthetic Aperture Radar Tasks](#item-geoai-1) ⭐️ 9.0/10
2. [High-Resolution Canopy Height and Carbon Mapping in the Atlantic Forest](#item-geoai-2) ⭐️ 9.0/10
3. [Any2Building: Unifying Point Clouds and Images for 3D Building Reconstruction](#item-geoai-3) ⭐️ 9.0/10
4. [PRUE: Practical Field Boundary Segmentation at Scale](#item-geoai-4) ⭐️ 9.0/10
5. [Flow Matching for Sentinel-2 Super-Resolution and Land Cover Mapping](#item-geoai-5) ⭐️ 9.0/10
6. [Rethinking Perceptual Similarity for Remote Sensing via Multi-Layer Attention](#item-geoai-6) ⭐️ 8.0/10
7. [Segmentation-Guided Direct Capacity Estimation of Rooftop Photovoltaics](#item-geoai-7) ⭐️ 8.0/10
8. [SpatialMind: Adaptive Multi-Level Geometric Fusion for 3D Spatial Reasoning](#item-geoai-8) ⭐️ 8.0/10
9. [Reliability-Driven Feature Correction for Hyperspectral and LiDAR Classification](#item-geoai-9) ⭐️ 8.0/10

**Climate, Geoscience, Teaching and Funding**
1. [Projected Global Daily CO2 Emissions for 2026](#item-geo-science-edu-1) ⭐️ 8.0/10
2. [Multimodal Data-Driven Models for Oceanographic Eddy Detection](#item-geo-science-edu-2) ⭐️ 8.0/10
3. [Learning Calibrated Predictive Distributions of Surface-Ocean Delta pCO2](#item-geo-science-edu-3) ⭐️ 8.0/10
4. [DARWIN: A Geospatial Foundation Model for Marine Intelligence](#item-geo-science-edu-4) ⭐️ 8.0/10
5. [Diagnosing a Damaging Nocturnal Tornado in Iloilo, Philippines](#item-geo-science-edu-5) ⭐️ 8.0/10
6. [PyOTIS: Open-Source Python Package for Stream Solute Transport and Transient Storage](#item-geo-science-edu-6) ⭐️ 8.0/10
7. [Low-Viscosity Lavas Reveal Insights into Mars&\#x27;s Volcanic History](#item-geo-science-edu-7) ⭐️ 8.0/10

---

## GeoAI and Geospatial Data Science

<a id="item-geoai-1"></a>
### [SARVIA: Fast-Adapting Multimodal Models for Synthetic Aperture Radar Tasks](https://arxiv.org/abs/2611.22273) ⭐️ 9.0/10

The source reports on SARVIA, an adaptive post-pretraining method that specializes modern multimodal large language models \(MLLMs\) for synthetic aperture radar \(SAR\) Earth observation tasks. Using self-supervised spatial and SAR-specific questions with a shared answer-prediction objective, SARVIA jointly trains low-rank adapters in just 600 steps and 2 GPU-hours. Evaluations across six detection and segmentation benchmarks show that SARVIA outperforms dedicated SAR foundation models while drastically reducing training costs.

rss · arXiv cs.CV · Nov 18, 05:00

**「Context」** This work builds on the observation that modern MLLM visual encoders can surpass dedicated SAR foundation models as downstream initializations, challenging the need for costly large-scale domain pretraining. SARVIA introduces a paradigm shift toward brief specialization of existing visual capabilities.

**「Application」** Geospatial instructors and researchers can use the open-source code and dataset to teach efficient domain adaptation methods or apply the SARVIA backbone as a high-performance tool for SAR detection and segmentation workflows.

**Tags**: `#GeoAI`, `#Synthetic Aperture Radar`, `#Foundation Models`, `#Remote Sensing`, `#Multimodal Models`

---

<a id="item-geoai-2"></a>
### [High-Resolution Canopy Height and Carbon Mapping in the Atlantic Forest](https://arxiv.org/abs/2611.23048) ⭐️ 9.0/10

Researchers released 10-meter canopy height and 30-meter aboveground carbon maps for the Brazilian Atlantic Forest for 2024. The method uses a deep learning network fusing Sentinel-2 reflectance, Sentinel-1 and ALOS PALSAR backscatter, and ALOS elevation, trained on extensive airborne LiDAR data from São Paulo state. Evaluated on held-out test patches, the model achieved a root mean square error of 3.05 meters at 10 meters and 2.58 meters at 30 meters, outperforming existing global products.

rss · arXiv cs.CV · Nov 18, 05:00

**「Context」** This work addresses the limitations of global canopy height maps, which often lack regional accuracy when applied to local carbon estimation. The authors demonstrate that global products can exhibit more than twice the error of locally calibrated models, highlighting the necessity of regional validation for carbon accounting.

**「Application」** Geospatial instructors and researchers can use this study as a case study for deep learning sensor fusion in remote sensing, comparing regional models against global datasets. Practitioners can also utilize the datasets for carbon accounting and regional conservation planning in tropical forests.

**Tags**: `#canopy height`, `#aboveground carbon`, `#deep learning`, `#Sentinel-1`, `#Sentinel-2`, `#ALOS PALSAR`, `#LiDAR`, `#Atlantic Forest`

---

<a id="item-geoai-3"></a>
### [Any2Building: Unifying Point Clouds and Images for 3D Building Reconstruction](https://arxiv.org/abs/2611.23187) ⭐️ 9.0/10

The source reports the release of Any2Building, a unified framework and large-scale dataset for Level of Detail 2 \(LoD2\) 3D building reconstruction from partial point clouds, overhead images, or both. The method uses occupancy-grounded shared spatial queries within a common 3D grid to connect observations to target geometry. To support this, the authors introduce BuildingWorld-Image, a dataset containing approximately one million paired samples across 18 cities, with evaluations demonstrating improved geometric reconstruction accuracy over existing methods.

rss · arXiv cs.CV · Nov 18, 05:00

**「Context」** This work fits into 3D urban modeling and digital twins by addressing the challenge of abstracting structured buildings from limited observations like partial point clouds or overhead images. It builds on the connection between geometric and visual cues, utilizing a voxel conditional surface-generation and low-poly remeshing pipeline to produce compact LoD2 building models from predicted structures.

**「Application」** Geospatial instructors and researchers can use the BuildingWorld-Image dataset and the Any2Building framework as a benchmark for multi-modal urban reconstruction tasks or adapt the method for advanced coursework in GeoAI and digital twin generation.

**Tags**: `#3D building reconstruction`, `#Point clouds`, `#Overhead imagery`, `#GeoAI`, `#Urban modeling`

---

<a id="item-geoai-4"></a>
### [PRUE: Practical Field Boundary Segmentation at Scale](https://arxiv.org/abs/2603.27101) ⭐️ 9.0/10

The authors introduce PRUE, a practical U-Net-based approach for field boundary segmentation that combines a U-Net backbone, composite loss functions, and targeted data augmentations. Evaluated systematically on the Fields of The World \(FTW\) benchmark alongside 18 models including geospatial foundation models, PRUE achieves a 76% Intersection over Union and 47% object-F1, outperforming previous baselines by 6% and 9%. The authors release all code, models, and model-derived field boundary datasets for five countries.

rss · arXiv cs.CV · Nov 18, 05:00

**「Context」** Large-scale agricultural monitoring relies on accurate field boundary maps, but existing deep learning approaches remain sensitive to illumination, spatial scale, and geographic shifts. This work provides the first systematic evaluation of semantic segmentation and geospatial foundation models \(GFMs, pre-trained AI models designed for Earth observation data\) under unified settings to improve scalable delineation.

**「Application」** Geospatial instructors and researchers can use the newly released datasets across five countries and the open-source PRUE framework as a reproducible baseline or teaching tool for agricultural remote sensing and deep learning workflows.

**Tags**: `#field boundary segmentation`, `#agricultural monitoring`, `#geospatial foundation models`, `#remote sensing`, `#open dataset`

---

<a id="item-geoai-5"></a>
### [Flow Matching for Sentinel-2 Super-Resolution and Land Cover Mapping](https://arxiv.org/abs/2605.00367) ⭐️ 9.0/10

Researchers introduce a flow matching model for 4x super-resolution of 10-m Sentinel-2 visible and near-infrared bands, trained on 120,851 Sentinel-2 and NAIP image pairs. The authors report that the model outperformed diffusion and Real-ESRGAN alternatives in pixel-wise accuracy using a single Euler step, and generated realistic imagery in 20 steps using a Midpoint solver. This approach enabled the production of a 2.5-m 4-band CONUS product spanning over 1.58 trillion pixels and a yearly 2.5-m Chesapeake Bay watershed land cover product achieving an overall accuracy of 89.11% against 25,000 ground truth points.

rss · arXiv cs.CV · Nov 18, 05:00

**「Context」** This work addresses the persistent trade-off between spectral fidelity and perceptual quality in satellite imagery super-resolution. It builds upon generative modeling techniques, demonstrating that flow matching can surpass traditional diffusion and generative adversarial network methods in both efficiency and accuracy.

**「Application」** Geospatial instructors and researchers can use this method and its resulting datasets to teach advanced generative AI techniques for remote sensing and to explore high-resolution land cover classification workflows.

**Tags**: `#super-resolution`, `#Sentinel-2`, `#flow matching`, `#generative AI`, `#land cover classification`

---

<a id="item-geoai-6"></a>
### [Rethinking Perceptual Similarity for Remote Sensing via Multi-Layer Attention](https://arxiv.org/abs/2611.21816) ⭐️ 8.0/10

The authors introduce Remote Sensing Perceptual Distance \(RSPD\), a multi-layer attention-based quality metric utilizing RemoteCLIP to evaluate generated remote sensing imagery. By averaging seven independently calibrated layer distances without human-label tuning, RSPD outperforms basic cosine distance and matches strong generic baselines. The authors validate RSPD using a new blind, reference-conditioned 2AFC benchmark featuring five 300-triplet subsets and an ordered misregistration benchmark.

rss · arXiv cs.CV · Nov 18, 05:00

**「Context」** Standard natural image perceptual metrics transfer poorly to remote sensing because geospatial and semantic errors often remain visually plausible while failing downstream uses. This work builds on foundational vision-language models like RemoteCLIP, applying layer-wise Aligned Attention Scores to better capture domain-specific remote sensing artifacts.

**「Application」** Geospatial instructors and researchers can use the RSPD metric and the introduced preference benchmarks as evaluation tools for assessing image generation tasks like super-resolution, SAR-to-optical translation, and timeseries controls.

**Tags**: `#GeoAI`, `#Remote Sensing`, `#Image Generation`, `#Evaluation Benchmark`, `#Foundation Models`

---

<a id="item-geoai-7"></a>
### [Segmentation-Guided Direct Capacity Estimation of Rooftop Photovoltaics](https://arxiv.org/abs/2611.22076) ⭐️ 8.0/10

The paper introduces Direct Head, a segmentation-guided neural network architecture that directly regresses rooftop photovoltaic capacity from aerial imagery features and area descriptors instead of using a fixed area-density product. Evaluated across 7,590 French rooftop installations using both original splits and a department-based holdout, the authors report that Direct Head reduces mean absolute error by 8.7% and 12.5%, and symmetric mean absolute percentage error by 14.0% and 20.7%, compared to a parameter-matched area-density neural model.

rss · arXiv cs.CV · Nov 18, 05:00

**「Context」** Distribution planners often rely on incomplete interconnection records or conventional image-based estimators that convert segmentation masks to physical area and multiply by an estimated power density. This work builds on standard U-Net segmentation by retaining soft-mask pooling while decoupling capacity prediction from strict mask-derived area constraints.

**「Application」** Geospatial instructors and researchers can use this method as a deep learning architecture to adapt for renewable energy planning workflows and teach advanced GeoAI segmentation-regression pipelines.

**Tags**: `#GeoAI`, `#remote sensing`, `#photovoltaic estimation`, `#image segmentation`, `#spatial data science`

---

<a id="item-geoai-8"></a>
### [SpatialMind: Adaptive Multi-Level Geometric Fusion for 3D Spatial Reasoning](https://arxiv.org/abs/2611.22415) ⭐️ 8.0/10

The paper introduces SpatialMind, a multimodal large language model framework designed to improve 3D spatial reasoning by dynamically integrating multi-level geometric representations. It features a GeoFus module built with a gating network conditioned on text, visual semantics, and geometry, regulated by a negative-entropy loss to prevent gate collapse. Evaluated on spatial benchmarks, SpatialMind achieves a competitive score of 72.3 on VSI-Bench, with source code made publicly available.

rss · arXiv cs.CV · Nov 18, 05:00

**「Context」** Multimodal Large Language Models typically excel in 2D visual understanding but struggle with 3D spatial reasoning tasks like distance estimation and route planning. Previous approaches using 3D reconstruction models relied on rigid geometric fusion schemes, which SpatialMind replaces with a task-adaptive framework matching geometric granularity to specific cognitive requirements.

**「Application」** Geospatial instructors and researchers can use the publicly available source code to study advanced GeoAI architectures or adapt the GeoFus multi-layer fusion method for 3D spatial reasoning tasks.

**Tags**: `#Spatial Reasoning`, `#Multimodal Large Language Models`, `#GeoAI`, `#3D Spatial Data`

---

<a id="item-geoai-9"></a>
### [Reliability-Driven Feature Correction for Hyperspectral and LiDAR Classification](https://arxiv.org/abs/2611.22508) ⭐️ 8.0/10

The authors propose a reliability-driven framework \(ReDF\) to quantify, correct, and fuse complementary features from hyperspectral imaging and LiDAR data for land-cover classification. The method uses a class prototype bank to estimate spatially varying feature reliability and applies neighborhood agreement to guide bidirectional cross-modal correction. Experiments on three public datasets demonstrate that ReDF achieves higher mean overall accuracy and Kappa coefficients compared to existing methods.

rss · arXiv cs.CV · Nov 18, 05:00

**「Context」** Integrating hyperspectral imagery and LiDAR provides rich spectral and elevation details, but cross-modal fusion often suffers when weak or ambiguous features are poorly modeled. This approach builds on multi-modal data fusion by explicitly evaluating class-discriminative reliability to condition feature reweighting and representation.

**「Application」** Geospatial researchers and advanced students can use this framework as a methodological reference or adapt its reliability-guided feature correction and reweighting techniques for multi-modal remote sensing classification tasks.

**Tags**: `#hyperspectral imaging`, `#lidar`, `#land-cover classification`, `#data fusion`, `#geoai`

---

## Climate, Geoscience, Teaching and Funding

<a id="item-geo-science-edu-1"></a>
### [Projected Global Daily CO2 Emissions for 2026](https://arxiv.org/abs/2611.22406) ⭐️ 8.0/10

Researchers project global fossil-fuel and industrial carbon dioxide emissions to reach 38.1 gigatons in 2026, marking a marginal increase of 0.10% or 36.6 megatons over 2025 levels. By combining Carbon Monitor activity data from January 2019 through September 2026 with Prophet time-series projections for the remainder of the year across 47 region-sector series, the study reveals that regional shifts largely cancel each other out globally. Specifically, decreases in China totaling 0.19 gigatons are offset by increases in India totaling 0.19 gigatons.

rss · arXiv physics.ao-ph · Nov 18, 05:00

**「Context」** This work addresses the difficulty of assessing recent growth slowdowns before conventional inventories become available by examining daily emissions departures during major climate and energy disruptions. The authors note a reference 68% confidence range for the year-on-year growth rate between +0.011% and +0.18%, highlighting that 94% of the gross movement cancels out in the global sum.

**「Relevance」** This study can be utilized in earth science and regional geography courses to teach global carbon cycles, near-term emissions modeling, and the contrasting trajectories of major industrial economies like China and India.

**Tags**: `#carbon emissions`, `#climate change`, `#global geography`, `#energy policy`, `#emissions modeling`

---

<a id="item-geo-science-edu-2"></a>
### [Multimodal Data-Driven Models for Oceanographic Eddy Detection](https://arxiv.org/abs/2611.22601) ⭐️ 8.0/10

Researchers present a multimodal, multi-task, data-driven framework utilizing convolutional U-Nets to improve oceanographic eddy detection and sea surface temperature anomaly reconstruction. The approach features two model variants, NADIRnet and SWOTnet, trained on conventional nadir altimetry and SWOT-enriched maps respectively. The authors report high pixel- and structure-wise detection scores against ground-truth data, successfully recovering a larger and finer eddy population than traditional dynamically-based references.

rss · arXiv physics.ao-ph · Nov 18, 05:00

**「Context」** Traditional physically-based eddy detection algorithms often rely on hard-coded thresholds that make detected structures sensitive to minor field variations. By framing the problem as an optimization task using coupled sea surface temperature regression, the new framework sharpens and regularizes eddy boundaries. The source notes that residual disagreements stem primarily from boundary placement rather than missed structures, and highlights the method&\#x27;s low computational cost for operational deployment.

**「Relevance」** This framework offers advanced remote sensing and machine learning methodologies that can be integrated into graduate-level GIS or physical oceanography coursework. Researchers in oceanography and hydrology can adapt these multimodal U-Net architectures for high-resolution spatial analyses and near-real-time operational data processing.

**Tags**: `#Remote Sensing`, `#Oceanography`, `#Machine Learning`, `#GIS`, `#Water Resources`

---

<a id="item-geo-science-edu-3"></a>
### [Learning Calibrated Predictive Distributions of Surface-Ocean Delta pCO2](https://arxiv.org/abs/2611.21769) ⭐️ 8.0/10

Researchers apply a tabular conditional diffusion model called Treeffuser to estimate calibrated predictive distributions and uncertainties for surface-ocean delta pCO2 from sparse observational data. Using 13 environmental, spatial, and temporal predictors, the model achieves a continuous ranked probability score of 8.229 microatmospheres and well-calibrated coverage levels on a held-out Surface Ocean CO2 Atlas test set while maintaining competitive point-prediction skill.

rss · arXiv physics.ao-ph · Nov 18, 05:00

**「Context」** Quantifying the oceanic carbon sink requires estimating surface-ocean carbon dioxide from spatially and temporally sparse observations, yet most existing machine-learning approaches rely on deterministic values with post hoc uncertainty approximations. The authors note that extending this generative approach to spatially coherent field reconstruction will require modeling dependence across grid cells and evaluation on spatially held-out data.

**「Relevance」** This methodology can be incorporated into graduate-level coursework on environmental data science or applied in research focused on ocean carbon cycle estimation and probabilistic uncertainty quantification.

**Tags**: `#carbon cycle`, `#oceanography`, `#machine learning`, `#climate research`, `#uncertainty quantification`

---

<a id="item-geo-science-edu-4"></a>
### [DARWIN: A Geospatial Foundation Model for Marine Intelligence](https://arxiv.org/abs/2611.22496) ⭐️ 8.0/10

The source reports the introduction of DARWIN, a geospatial foundation model designed for marine intelligence using 26 years of global Copernicus reanalysis and GEBCO bathymetry. To address marine challenges like data missingness and non-stationary dynamics, the authors adapt a masked-autoencoder backbone with specialized encoding, masking, and Fourier-style embeddings. For chlorophyll-a prediction in 2022, the pretrained model achieved the lowest monthly relative error across all months, outperforming baseline models and achieving better performance with only 10% of supervised training data than a random-init model using 100% of the data.

rss · arXiv physics.ao-ph · Nov 18, 05:00

**「Context」** This work builds upon recent Earth-observation foundation models that have predominantly focused on terrestrial domains rather than the unique challenges of the marine realm, such as sparse labels and multi-modal physical and biogeochemical variables. A masked-autoencoder is a type of neural network that learns representations by predicting masked-out portions of input data. The source notes that embedding analysis demonstrates the model captures coherent oceanographic structures, offering a scalable backbone for downstream tasks like anomaly detection and environmental monitoring.

**「Relevance」** This model can be incorporated into remote sensing and GIS courses to teach advanced spatial-temporal machine learning and foundation models for environmental monitoring. Researchers in oceanography and water resources can use DARWIN as a scalable backbone for downstream tasks such as species distribution modeling and marine anomaly detection.

**Tags**: `#Geospatial Foundation Model`, `#Marine Intelligence`, `#Remote Sensing`, `#Oceanography`, `#Machine Learning`

---

<a id="item-geo-science-edu-5"></a>
### [Diagnosing a Damaging Nocturnal Tornado in Iloilo, Philippines](https://arxiv.org/abs/2611.19987) ⭐️ 8.0/10

The paper examines a significant nocturnal tornado that struck Iloilo City, Philippines, at approximately 2230 LST on 08 August 2026. The 2.9-kilometer-long and 340-meter-wide damage path was rated IF2 on the International Fujita Scale across 31 surveyed indicators. The parent supercell formed within the southwest monsoon enhanced by Typhoon Dolphin, driven by a nocturnal low-level jet, an MUCAPE of roughly 2000 J kg-1, and low-level shear of 16 m s-1 captured by the newly operational Iloilo S-band dual-polarization radar.

rss · arXiv physics.ao-ph · Nov 18, 05:00

**「Context」** This research highlights how significant tornadoes can develop at night during the Philippine monsoon under weak synoptic forcing. The study notes that standard operational radar quality control, including processor smoothing and specific cross-correlation coefficient thresholds, initially masked the tornadic vortex and debris signatures.

**「Relevance」** Faculty can use this case study in advanced meteorology courses to teach dual-polarization radar interpretation, severe weather forecasting during monsoons, and the challenges of operational radar quality control in detecting concealed vortices.

**Tags**: `#meteorology`, `#tornadoes`, `#radar remote sensing`, `#climate and weather`, `#monsoon`

---

<a id="item-geo-science-edu-6"></a>
### [PyOTIS: Open-Source Python Package for Stream Solute Transport and Transient Storage](https://arxiv.org/abs/2611.12915) ⭐️ 8.0/10

The source reports the release of PyOTIS, an open-source Python package that integrates stream solute transport, transient storage, parameter estimation, and water-quality reactions into a scriptable workflow featuring a browser-based graphical user interface. Evaluations against legacy OTIS manual examples show steady-state iron profile agreement to seven significant figures, while comparisons with the nine-species MATLAB E-OTIS implementation report maximum absolute differences of order 10$^\{-14\}$ mg L$^\{-1\}$. For Clackamas River calibration tests, residual sums of squares differ from OTIS-P by 3.65 to 5.12%, though individual parameter estimates vary by up to 39.1%.

rss · arXiv physics.geo-ph · Nov 18, 05:00

**「Context」** The package unifies the capabilities of legacy OTIS, OTIS-P, and E-OTIS by inheriting their established Crank-Nicolson formulations and reaction networks within a modern Python environment. The source notes that these evaluations support implementation consistency for the tested cases rather than establishing unique parameter estimates or validating every reaction pathway.

**「Relevance」** This software can be incorporated into hydrology and water-resources courses to teach stream solute transport modeling through interactive browser-based interfaces, or utilized in research workflows requiring scriptable parameter estimation and sensitivity analysis.

**Tags**: `#hydrology`, `#water resources`, `#software`, `#stream transport`, `#python`

---

<a id="item-geo-science-edu-7"></a>
### [Low-Viscosity Lavas Reveal Insights into Mars&\#x27;s Volcanic History](https://eos.org/articles/low-viscosity-lavas-reveal-a-key-to-marss-past) ⭐️ 8.0/10

Data from the Mars Perseverance rover&\#x27;s PIXL instrument reveals that the nearly 4-billion-year-old Séítah formation in Jezero Crater was created by low-viscosity, komatiite-like lava flows. Researchers applied a magma viscosity model to geochemical measurements, indicating that a lava lake cooled over hundreds or thousands of years and traveled about 200 kilometers from its vent.

rss · Eos \(AGU\) · Nov 18, 13:36

**「Context」** The findings support the idea that the long-term mantle evolution of Mars and Earth shared similar trends, despite Mars having a cooler interior that complicates olivine formation. The study helps rule out subsurface intrusive origins that would otherwise require active plate tectonics on Mars.

**「Relevance」** Educators can use this study in introductory earth science and planetary geology courses to discuss planetary volcanology, magma viscosity, and the interpretation of geochemical rover data.

**Tags**: `#planetary geology`, `#volcanology`, `#Mars Perseverance rover`, `#geochemistry`, `#earth science education`

---