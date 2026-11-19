---
layout: default
title: "Horizon Summary: 2026-11-19 (EN)"
date: 2026-11-19
lang: en
---

> From 446 items, 17 important content pieces were selected

---

**GeoAI and Geospatial Data Science**
1. [ShadowTransfer: Geographic Transfer Benchmark for Overhead Shadow Detection](#item-geoai-1) ⭐️ 9.0/10
2. [RPC-GS: Native Gaussian Splatting for Satellite Imagery](#item-geoai-2) ⭐️ 9.0/10
3. [Any2Building Unifies Point Clouds and Images for 3D Building Reconstruction](#item-geoai-3) ⭐️ 9.0/10
4. [GRID-UAV Integrates Geometry and Ray-Depth for Aerial Navigation](#item-geoai-4) ⭐️ 8.0/10
5. [Do 3D Point Representations Encode Architectural Functions on Urban Facades?](#item-geoai-5) ⭐️ 8.0/10
6. [TOGBench: Benchmarking Tiny-Object Generation Fidelity in Aerial Imagery](#item-geoai-6) ⭐️ 8.0/10
7. [Visual Board Harness Improves Multimodal Agent Reasoning on SolidGeo](#item-geoai-7) ⭐️ 8.0/10
8. [Freeforward4d: Annotation-Free Feed-Forward 4D Reconstruction of Driving Scenes](#item-geoai-8) ⭐️ 8.0/10
9. [HyGeoBench and HyGeoAgent for Geological Remote Sensing Interpretation](#item-geoai-9) ⭐️ 8.0/10

**Climate, Geoscience, Teaching and Funding**
1. [Evidence Indicates Ongoing Slowing of the Atlantic Meridional Overturning Circulation](#item-geo-science-edu-1) ⭐️ 8.0/10
2. [Data-Driven Versus Numerical Weather Prediction for Extreme Weather](#item-geo-science-edu-2) ⭐️ 8.0/10
3. [Enabling Joint Chemical and Meteorological Data Assimilation with AuroraChem](#item-geo-science-edu-3) ⭐️ 8.0/10
4. [Angular Momentum Versus Kinetic Energy in Tropical Cyclone Formation](#item-geo-science-edu-4) ⭐️ 8.0/10
5. [Quantifying AI Data Center Nitrogen Oxide Emissions from Space](#item-geo-science-edu-5) ⭐️ 8.0/10
6. [Diagnosing a Damaging Nocturnal Tornado in Iloilo, Philippines](#item-geo-science-edu-6) ⭐️ 8.0/10
7. [Global Daily CO2 Emissions Projections for 2026](#item-geo-science-edu-7) ⭐️ 8.0/10
8. [National Academies Launch ESAS 2028 Earth Science Decadal Survey](#item-geo-science-edu-8) ⭐️ 8.0/10

---

## GeoAI and Geospatial Data Science

<a id="item-geoai-1"></a>
### [ShadowTransfer: Geographic Transfer Benchmark for Overhead Shadow Detection](https://arxiv.org/abs/2611.24904) ⭐️ 9.0/10

ShadowTransfer introduces a human-verified benchmark of 4,500 shadow masks across three U.S. cities at two resolutions, accompanied by a leave-one-city-out evaluation protocol for overhead imagery. The authors report that vanilla training across four architectures suffers a 3.5 to 7.8 mIoU drop when holding out test cities, and six of eight tested adaptation methods underperform vanilla training. To address this, the source proposes a diagnostic framework and the Spectral Information Bottleneck \(SIB\) plug-in module, which achieves the smallest mean gap to the within-city upper bound among evaluated methods.

rss · arXiv cs.CV · Nov 19, 05:00

**「Context」** Overhead aerial imagery pipelines are frequently trained in one region and deployed in another, yet prior shadow datasets lacked rigorous geographic transfer protocols or relied on automated labels. The diagnostic framework reveals that cross-region failure operates in feature space as a confidence collapse on shadow pixels, offering new insights into domain generalization challenges for dense prediction in remote sensing.

**「Application」** GeoAI researchers and instructors can use the open-source ShadowTransfer benchmark, code, and trained models as a dataset and evaluation tool to study domain adaptation and geographic generalization in remote sensing courses.

**Tags**: `#GeoAI`, `#Remote Sensing`, `#Dataset`, `#Benchmark`, `#Domain Adaptation`

---

<a id="item-geoai-2"></a>
### [RPC-GS: Native Gaussian Splatting for Satellite Imagery](https://arxiv.org/abs/2606.06690) ⭐️ 9.0/10

The authors present RPC-GS, a Gaussian Splatting framework for satellite imagery that operates natively with Rational Polynomial Camera \(RPC\) models without relying on perspective or affine approximations. By projecting Gaussian means and covariances directly through the RPC model via a robust Jacobian-based covariance projection and a metric ray-based depth formulation, the method reduces geometric reconstruction errors. Benchmarked on the DFC2019 and IARPA2016 datasets, the native RPC renderer achieves lower mean altitude errors than approximations, improving performance by up to 34.3% on DFC2019.

rss · arXiv cs.CV · Nov 19, 05:00

**「Context」** RPC models are the de facto standard for representing the complex imaging geometry of modern pushbroom satellite sensors. Prior satellite Gaussian Splatting approaches replaced these RPC models with simplified camera approximations, which introduced geometric errors during 3D reconstruction.

**「Application」** Geospatial researchers and instructors can use the publicly available code repository as a tool to test advanced 3D reconstruction workflows or teach modern GeoAI methods for satellite remote sensing.

**Tags**: `#Gaussian Splatting`, `#Satellite Imagery`, `#Remote Sensing`, `#3D Reconstruction`, `#GeoAI`

---

<a id="item-geoai-3"></a>
### [Any2Building Unifies Point Clouds and Images for 3D Building Reconstruction](https://arxiv.org/abs/2611.23187) ⭐️ 9.0/10

The source reports the release of Any2Building, a unified GeoAI framework and large-scale dataset for Level of Detail 2 \(LoD2\) building reconstruction using partial point clouds, overhead images, or multimodal inputs. Utilizing an occupancy-grounded shared spatial queries representation across a 3D grid, the method connects observational evidence to target geometry and converts predicted structures into compact models via a remeshing pipeline. Evaluated across multiple benchmarks using the new BuildingWorld-Image dataset of one million paired samples from 18 cities, the authors state that the model outperforms existing methods in geometric reconstruction accuracy across various unimodal and multimodal tasks.

rss · arXiv cs.CV · Nov 19, 05:00

**「Context」** This work addresses core challenges in 3D urban modeling and digital twins by aligning geometric and visual cues from limited observations to recover missing structures. It builds on traditional point-cloud completion and single-image generation techniques by introducing a shared framework that handles flexible input modalities.

**「Application」** Geospatial instructors and researchers can use the BuildingWorld-Image dataset and the Any2Building model as a practical tool for multimodal 3D urban reconstruction and advanced GIS coursework in digital twins.

**Tags**: `#building reconstruction`, `#point clouds`, `#overhead imagery`, `#GeoAI`, `#3D urban modeling`

---

<a id="item-geoai-4"></a>
### [GRID-UAV Integrates Geometry and Ray-Depth for Aerial Navigation](https://arxiv.org/abs/2611.23491) ⭐️ 8.0/10

The paper introduces GRID, a framework that integrates explicit ray-corrected 3D lifting and implicit multi-view geometry alignment to enhance vision-language-action model navigation for UAVs. Evaluated on the TravelUAV benchmark across 3,005 test episodes, GRID achieves state-of-the-art success rates with relative gains of 9.5% on seen splits, 17.1% on unseen objects, and 25.4% on unseen maps.

rss · arXiv cs.CV · Nov 19, 05:00

**「Context」** Standard vision-language-action models rely on 2D encoders that lack robust 3D structure, while direct monocular depth inputs often fail over long aerial routes and varying altitudes. The authors demonstrate that combining explicit 3D lifting—which reduces collisions en route—with implicit multi-view geometry alignment—which improves target completion—overcomes these limitations.

**「Application」** Geospatial instructors and robotics researchers can study the TravelUAV benchmark dataset and adapt the GRID framework as a method for improving spatial reasoning and depth-aware navigation in aerial remote sensing platforms.

**Tags**: `#UAV`, `#computer vision`, `#spatial reasoning`, `#GeoAI`, `#remote sensing`

---

<a id="item-geoai-5"></a>
### [Do 3D Point Representations Encode Architectural Functions on Urban Facades?](https://arxiv.org/abs/2611.23720) ⭐️ 8.0/10

The study investigates whether 3D point representations from mobile LiDAR data encode architectural functions rather than just physical forms. Evaluating 22 buildings with 15 functional attributes per element, the authors compared hand-crafted descriptors, models trained from scratch, and frozen self-supervised transformers. The source reports that frozen pretrained representations reached 0.732 mean average precision on functionally ambiguous elements, outperforming networks trained from scratch and hand-crafted descriptors, while fine-tuning eroded these pretrained benefits at current data scales.

rss · arXiv cs.CV · Nov 19, 05:00

**「Context」** This research addresses the limitation where semantic labels describe physical elements rather than their functional roles, such as distinguishing load-bearing columns from decorative ones. It builds on comparative evaluations of mobile LiDAR point clouds, hand-crafted descriptors, and self-supervised point transformers like PTv3 and Utonia.

**「Application」** Geospatial instructors and researchers can use this study&\#x27;s methodology and findings to benchmark point cloud models or teach advanced urban remote sensing courses focused on GeoAI and self-supervised representations.

**Tags**: `#3D point clouds`, `#LiDAR`, `#pretrained models`, `#urban facade analysis`, `#GeoAI`

---

<a id="item-geoai-6"></a>
### [TOGBench: Benchmarking Tiny-Object Generation Fidelity in Aerial Imagery](https://arxiv.org/abs/2611.23840) ⭐️ 8.0/10

The authors introduce TOGBench, a quantitative, object-level benchmark designed to evaluate tiny-object generation fidelity in aerial imagery. Because aerial and wide-area imaging is dominated by small elements like vehicles, ships, and aircraft occupying only a few pixels, existing generative models struggle with faithful rendering. To address this, the paper also proposes two train- and inference-time techniques that improve layout-to-image generators in rendering these small objects.

rss · arXiv cs.CV · Nov 19, 05:00

**「Context」** Prior work on generative evaluation heavily emphasizes general prompt following or human preference rather than the precise rendering of small objects. This benchmark targets a significant oversight in deep generative models, which traditionally struggle more with tiny objects than with larger ones in remote sensing contexts.

**「Application」** Geospatial researchers and instructors can use TOGBench as a quantitative tool to evaluate layout-to-image generators or adapt the proposed training and inference techniques to improve synthetic aerial dataset generation for computer vision tasks.

**Tags**: `#GeoAI`, `#remote sensing`, `#aerial imagery`, `#generative models`, `#benchmarking`

---

<a id="item-geoai-7"></a>
### [Visual Board Harness Improves Multimodal Agent Reasoning on SolidGeo](https://arxiv.org/abs/2611.23872) ⭐️ 8.0/10

The authors report a Visual Board harness for multimodal agents that separates raw visual observations from uncertain interpretations and derived reasoning in a structured workspace. Evaluated across 4B to 32B configurations without task-specific training, the harness improves performance on benchmarks including SolidGeo, Euclid30K, and ChartQA by up to 18.42, 11.68, and 24.82 percentage points, respectively, while using 7.9% to 38.2% fewer tokens than free-form notes.

rss · arXiv cs.CV · Nov 19, 05:00

**「Context」** Multi-step visual reasoning often fails when early visual misinterpretations persist as incorrect premises in a growing dialogue history. This work builds on and improves multi-step reasoning by making premises explicit and auditable, allowing conflicts to trigger targeted reinspection of the original image.

**「Application」** Geospatial instructors and researchers can use this harness as a method to adapt for multimodal GeoAI workflows and agents handling complex spatial tasks like SolidGeo.

**Tags**: `#GeoAI`, `#Multimodal Models`, `#Visual Reasoning`, `#Geospatial Data Science`

---

<a id="item-geoai-8"></a>
### [Freeforward4d: Annotation-Free Feed-Forward 4D Reconstruction of Driving Scenes](https://arxiv.org/abs/2611.24007) ⭐️ 8.0/10

The authors introduce FreeForward4D, an annotation-free feed-forward framework for 4D reconstruction of driving scenes using only RGB video inputs. By reconciling inconsistent pretrained visual priors into a single metric frame, the method recovers metric-scale cameras and depth without requiring dataset-provided cameras, LiDAR, or 3D bounding boxes. Evaluated on the Waymo dataset, the framework achieves 27.66 dB PSNR and 0.836 SSIM on 8-second windows, outperforming several annotation-dependent baselines while offering adaptability to nuScenes and Argoverse 2.

rss · arXiv cs.CV · Nov 19, 05:00

**「Context」** Feed-forward 4D reconstruction creates renderable driving scenes for autonomous driving simulation, but existing techniques traditionally depend heavily on external annotations like LiDAR depth and 3D bounding boxes. This work builds upon pretrained visual models by solving their mutual inconsistencies—such as independent scales across multi-view windows and monocular depth limitations—to replace manual dataset annotations entirely.

**「Application」** Geospatial instructors and autonomous driving researchers can use the upcoming open-source code as a scalable tool to generate renderable 4D driving simulations and metric-scale reconstructions from unannotated RGB video data.

**Tags**: `#4D reconstruction`, `#autonomous driving`, `#computer vision`, `#neural rendering`, `#geospatial data science`

---

<a id="item-geoai-9"></a>
### [HyGeoBench and HyGeoAgent for Geological Remote Sensing Interpretation](https://arxiv.org/abs/2611.24068) ⭐️ 8.0/10

The authors introduce HyGeoBench, a 10,000-question diagnostic benchmark using hyperspectral imagery to evaluate multimodal large language models across reasoning reliability, prior-evidence contrast, and spectral discrimination. Covering ten task types with multiple-choice and open-ended formats, evaluations reveal limitations in fine-grained recognition and evidence-grounded interpretation. To address these gaps, the authors propose HyGeoAgent, a tool-augmented framework integrating region observation, text knowledge retrieval, band image retrieval, and native principal component analysis to improve geological image interpretation.

rss · arXiv cs.CV · Nov 19, 05:00

**「Context」** This work addresses the unclear reliability of multimodal large language models in specialized remote-sensing geological applications, moving beyond general vision tasks into complex hyperspectral analysis. Principal component analysis \(PCA\) is a statistical technique used here as a native tool to reduce data dimensionality and highlight spectral features.

**「Application」** Geospatial instructors and researchers can use HyGeoBench as a benchmark dataset to evaluate vision-language models, or adopt the HyGeoAgent framework to teach and explore tool-augmented GeoAI workflows for hyperspectral geological analysis.

**Tags**: `#GeoAI`, `#Hyperspectral Imaging`, `#Multimodal Large Language Models`, `#Remote Sensing`, `#Geological Interpretation`

---

## Climate, Geoscience, Teaching and Funding

<a id="item-geo-science-edu-1"></a>
### [Evidence Indicates Ongoing Slowing of the Atlantic Meridional Overturning Circulation](https://arxiv.org/abs/2611.23429) ⭐️ 8.0/10

This preprint compiles and discusses heterogeneous evidence regarding the Atlantic Meridional Overturning Circulation \(AMOC\), focusing on latitudes south of 45 degrees north. The authors conclude that multiple lines of data strongly support a past and ongoing slowing of the AMOC driven by global warming, though uncertainties remain regarding its exact magnitude and timing.

rss · arXiv physics.ao-ph · Nov 19, 05:00

**「Context」** While continuous direct monitoring spans only the last two decades—a period too short to fully separate natural variability from anthropogenic climate change—longer-term reconstructions involve debated limitations. Understanding whether the AMOC is currently weakening is crucial for evaluating climate models that have long predicted a slowdown and potential future tipping points.

**「Relevance」** This comprehensive synthesis is valuable for teaching climate change dynamics and ocean-atmosphere interactions in earth science courses, and for informing ongoing research in climatology and water resources.

**Tags**: `#AMOC`, `#climate change`, `#oceanography`, `#climate dynamics`

---

<a id="item-geo-science-edu-2"></a>
### [Data-Driven Versus Numerical Weather Prediction for Extreme Weather](https://arxiv.org/abs/2611.23863) ⭐️ 8.0/10

This review paper compares data-driven weather forecasting models with physics-based numerical weather prediction \(NWP\) models across timescales from nowcasting to subseasonal lead times. The authors report that while data-driven models frequently outperform NWP on temperature extremes, tropical cyclone tracks, and synoptic feature locations, evidence is mixed for precipitation and atmospheric rivers. Physics-based models generally retain the advantage for event intensity and record-breaking events outside the training distribution, where data-driven models often underestimate frequency and magnitude.

rss · arXiv physics.ao-ph · Nov 19, 05:00

**「Context」** The study examines why conclusions in the literature vary, attributing discrepancies to differences in headline scores, verification choices, and case selection, and highlights that hybrid systems coupling machine learning with physics deliver consistent gains. Reanalysis data refers to long-term meteorological datasets produced by assimilating historical observations into numerical models, while synoptic features describe large-scale weather systems spanning hundreds to thousands of kilometers.

**「Relevance」** This review provides an ideal foundational reading for graduate seminars in atmospheric science or climatology to discuss the methodological shift toward machine learning in weather forecasting. Researchers can also use its evaluation recommendations to design more robust benchmarking frameworks for extreme weather detection algorithms.

**Tags**: `#weather forecasting`, `#machine learning`, `#extreme weather`, `#numerical weather prediction`, `#climate science`

---

<a id="item-geo-science-edu-3"></a>
### [Enabling Joint Chemical and Meteorological Data Assimilation with AuroraChem](https://arxiv.org/abs/2611.24020) ⭐️ 8.0/10

Researchers introduce AuroraChem, a fine-tuned atmospheric foundation model designed to jointly simulate meteorology and GEOS-Chem chemical fields in order to constrain tropospheric oxidants like the hydroxyl radical. A one-year model rollout completes in 12 minutes on a single GPU. Idealized data assimilation tests demonstrate that chemical observations can constrain meteorological states and vice versa, leveraging learned variable covariances.

rss · arXiv physics.ao-ph · Nov 19, 05:00

**「Context」** Tropospheric oxidants such as hydroxyl radicals control major chemical sinks like methane, but traditional chemistry-climate models are too computationally expensive to perform joint data assimilation effectively. The authors note that while free rollouts remain stable for a year, they fail to fully capture seasonal cycles, and the observed cross-variable constraints stem from learned covariances rather than direct physical coupling.

**「Relevance」** This paper can be incorporated into graduate-level courses on atmospheric modeling or machine learning applications in geoscience to discuss data assimilation trade-offs. Researchers working in climate science and atmospheric chemistry can use this framework as a reference for developing computationally efficient, coupled data-driven models.

**Tags**: `#atmospheric chemistry`, `#meteorology`, `#data assimilation`, `#machine learning`, `#climate science`

---

<a id="item-geo-science-edu-4"></a>
### [Angular Momentum Versus Kinetic Energy in Tropical Cyclone Formation](https://arxiv.org/abs/2611.24476) ⭐️ 8.0/10

A recent study investigates why tropical cyclones rarely form near the equator despite the widespread availability of ocean heat energy. Analyzing ERA5 winds over the western Pacific, the authors report that absolute angular momentum and wind energy are supplied separately, with absolute angular momentum drawn from mesoscale turbulence. Their findings show that rotational turbulence content collapses equatorward of approximately six degrees north, while rare equatorial storms like Typhoon Vamei are preceded by anomalous rotational variance.

rss · arXiv physics.ao-ph · Nov 19, 05:00

**「Context」** This research addresses the fundamental atmospheric dynamics governing tropical cyclone genesis by contrasting ocean heat engines with the localized rotational requirements of storms. The analysis relies on ERA5 reanalysis data to evaluate one-dimensional wind spectra along latitude circles, though specific limitations involve regional dataset constraints and the theoretical approximations of rotating stratified turbulence.

**「Relevance」** This study provides valuable quantitative metrics and conceptual frameworks suitable for advanced undergraduate or graduate coursework in atmospheric dynamics and climate science. Researchers investigating tropical cyclogenesis and mesoscale turbulence can use these findings to refine numerical simulations of storm formation limits.

**Tags**: `#tropical cyclones`, `#atmospheric dynamics`, `#angular momentum`, `#climate research`, `#mesoscale turbulence`

---

<a id="item-geo-science-edu-5"></a>
### [Quantifying AI Data Center Nitrogen Oxide Emissions from Space](https://arxiv.org/abs/2608.22153) ⭐️ 8.0/10

Researchers use observations from the geostationary TEMPO satellite to quantify nitrogen oxide \(NOx\) emissions from natural gas turbines powering the SpaceXAI Colossus 2 power plant in Southaven, Mississippi. The study detects a strong increase in local mean NO2 column concentrations after operations began in late 2025, with two-week-average NOx emissions reaching 870±165 kg h−1 after February 2026. This observed rate is roughly 19 times higher than expected from the facility&\#x27;s March 2026 permit for 41 turbines operating under best available control technology.

rss · arXiv physics.ao-ph · Nov 19, 05:00

**「Context」** The study addresses the growing environmental concern of NOx pollution driven by the rapid deployment of natural gas turbines for AI data center power demand, which previously lacked atmospheric quantification. The authors calibrated satellite observations against continuous emission monitoring system data from US power plants, while noting that emissions at permitted levels would fall below the detection threshold of their TEMPO analysis.

**「Relevance」** This paper provides a concrete case study for teaching remote sensing, GIS, and atmospheric chemistry courses by demonstrating how geostationary satellite data can monitor trace gases and anthropogenic emissions from modern infrastructure. Researchers studying energy policy and environmental justice can also use these methods to independently verify facility emissions against regulatory permits.

**Tags**: `#remote sensing`, `#atmospheric pollution`, `#satellite observations`, `#AI infrastructure`, `#air quality`

---

<a id="item-geo-science-edu-6"></a>
### [Diagnosing a Damaging Nocturnal Tornado in Iloilo, Philippines](https://arxiv.org/abs/2611.19987) ⭐️ 8.0/10

The source reports a meteorological diagnosis of a rare damaging nocturnal tornado that struck the Mandurriao and Jaro districts of Iloilo City, Philippines, at roughly 2230 LST on 08 August 2026. Utilizing ERA5 reanalysis and data from the newly operational Iloilo S-band dual-polarization radar, the author documents an IF2-rated tornado with a 2.9 km path length and 340 m width. The parent supercell developed under weak synoptic forcing during the southwest monsoon enhanced by Typhoon Dolphin, driven by a nocturnal low-level jet, high instability, and strong low-level shear.

rss · arXiv physics.ao-ph · Nov 19, 05:00

**「Context」** This case study builds on observational analysis of tropical severe convective storms, highlighting how significant tornadoes can form at night in Southeast Asia. The author notes that processor smoothing and quality control thresholds on the radar masked the direct tornadic vortex and debris signatures, indicating a critical limitation in operational radar data processing for narrow vortices.

**「Relevance」** This study can be utilized in advanced meteorology and radar remote sensing courses to teach dual-polarization radar interpretation, hook echoes, and severe storm dynamics in tropical monsoon environments. It also provides strong material for research discussions focusing on operational radar quality control and nocturnal tornado forecasting limitations.

**Tags**: `#tornadoes`, `#meteorology`, `#radar remote sensing`, `#climate and weather`, `#southeast asia`

---

<a id="item-geo-science-edu-7"></a>
### [Global Daily CO2 Emissions Projections for 2026](https://arxiv.org/abs/2611.22406) ⭐️ 8.0/10

Researchers project global fossil-fuel and industrial carbon dioxide emissions will reach 38.0 gigatons in 2026, marking a near-zero change of minus 0.1 percent compared to 2025. By fitting Prophet time-series models to Carbon Monitor activity estimates across 47 region-sector series, the study reveals that 95 percent of gross regional emission shifts cancel out globally. Specifically, reductions in China driven by industry and ground transport offset increases in India led by power and industry.

rss · arXiv physics.ao-ph · Nov 19, 05:00

**「Context」** This research addresses the difficulty of assessing recent growth slowdowns before conventional inventories become available by combining activity estimates through September with projections for the final quarter. The authors note that Prophet models exhibit lower mean daily errors but larger mean absolute annual biases compared to a seasonal-naive benchmark. Furthermore, the analysis highlights that heat-period power anomalies vary by country and can be muted by summer averaging.

**「Relevance」** This study can be utilized in geography and earth science courses as a case study on regional carbon disparities, contrasting emission reductions in China with continued growth in India. Researchers studying near-term climate mitigation progress can also apply these daily activity modeling frameworks to assess sector-specific disruptions.

**Tags**: `#carbon emissions`, `#climate change`, `#energy consumption`, `#carbon monitor`, `#regional geography`

---

<a id="item-geo-science-edu-8"></a>
### [National Academies Launch ESAS 2028 Earth Science Decadal Survey](https://news.google.com/rss/articles/CBMikAFBVV95cUxPZElvUGUzSjdNRmR4bVV4QjAzYWI1MHFpMVpia0xyejlfbENMOTU2cWNtZ0JySDloZWozenlmNFNpZTJZUkhfQm91T1A4OEczODhOeXRPUlZXSWk0ZnNTeVZVN3lHb3pUY3UyT0RYa2tpOGxOY0t3NmtSdXNuaC0xRm9JeWZhNjZ1MTktVjBmYjQ?oc=5) ⭐️ 8.0/10

The National Academies have initiated the ESAS 2028 Earth Science Decadal Survey at NASA&\#x27;s request, as reported by CASRAI. This strategic evaluation will shape future federal research priorities, space missions, and funding directions for the earth sciences.

rss · Google News: research funding · Nov 19, 01:55

**「Context」** Decadal surveys serve as essential community-driven policy frameworks that guide multi-year federal investments and strategic planning in space-based remote sensing and earth observation.

**「Relevance」** Faculty can use this upcoming survey process in research planning to align institutional proposals with emerging NASA priorities, or incorporate the decadal planning framework into graduate seminar discussions on science policy.

**Tags**: `#earth science`, `#decadal survey`, `#NASA`, `#remote sensing`, `#research policy`

---