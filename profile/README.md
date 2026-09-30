<!-- Profile README of the GitHub organization FLC-QU-hep.
     Lives in the repository FLC-QU-hep/.github at profile/README.md and is
     shown at the top of https://github.com/FLC-QU-hep. -->

# DESY FTX and UHH Particles & Detectors – Generative Modeling

Machine learning for particle physics in the FTX group at DESY and the
Particles & Detectors group at Universität Hamburg. We build generative models
for fast calorimeter simulation and study how they transfer between detector
geometries. This organization hosts the code of our publications. Trained
weights are on [Hugging Face](https://huggingface.co/FLC-QU-hep).

## Publications and code

Most recent first, by arXiv date.

| Paper | Journal | Code | Weights |
|---|---|---|---|
| | | [`LayerFM`](https://github.com/FLC-QU-hep/LayerFM) | [`LayerFM`](https://huggingface.co/FLC-QU-hep/LayerFM) |
| Transferable Fast Calorimeter Shower Generation via Multi-Geometry Pre-training, [arXiv:2608.18233](https://arxiv.org/abs/2608.18233) | | [`AllShowers`, branch `multi-geometry`](https://github.com/FLC-QU-hep/AllShowers/tree/multi-geometry) · [`PointCountFM`, branch `multi-geometry`](https://github.com/FLC-QU-hep/PointCountFM/tree/multi-geometry) · [`multi-calorimeter-dataset`](https://github.com/FLC-QU-hep/multi-calorimeter-dataset) | [`AllShowers-multi-geometry`](https://huggingface.co/FLC-QU-hep/AllShowers-multi-geometry), [`PointCountFM-multi-geometry`](https://huggingface.co/FLC-QU-hep/PointCountFM-multi-geometry) |
| AllShowers: One model for all calorimeter showers, [arXiv:2601.11716](https://arxiv.org/abs/2601.11716) | [SciPost Phys. 21, 076 (2026)](https://doi.org/10.21468/SciPostPhys.21.3.076) | [`AllShowers`](https://github.com/FLC-QU-hep/AllShowers) · [`PointCountFM`](https://github.com/FLC-QU-hep/PointCountFM) | |
| Cross-Geometry Transfer Learning in Fast Electromagnetic Shower Simulation, [arXiv:2512.00187](https://arxiv.org/abs/2512.00187) | [JINST 21 (2026) P07037](https://doi.org/10.1088/1748-0221/21/07/P07037) | [`CaloTransfer`](https://github.com/FLC-QU-hep/CaloTransfer) | |
| A First Full Physics Benchmark for Highly Granular Calorimeter Surrogates, [arXiv:2511.17293](https://arxiv.org/abs/2511.17293) | | [`key4hep/DDML`](https://github.com/key4hep/DDML) | |
| CaloClouds3: Ultra-Fast Geometry-Independent Highly-Granular Calorimeter Simulation, [arXiv:2511.01460](https://arxiv.org/abs/2511.01460) | [JINST 21 (2026) P03018](https://doi.org/10.1088/1748-0221/21/03/P03018) | [`CaloClouds-3`](https://github.com/FLC-QU-hep/CaloClouds-3) · [`container_CaloClouds-3`](https://github.com/FLC-QU-hep/container_CaloClouds-3) | |
| CaloHadronic: a diffusion model for the generation of hadronic showers, [arXiv:2506.21720](https://arxiv.org/abs/2506.21720) | [JINST 21 (2026) P01042](https://doi.org/10.1088/1748-0221/21/01/P01042) | [`CaloHadronic`](https://github.com/FLC-QU-hep/CaloHadronic) | |
| Convolutional L2LFlows: Generating Accurate Showers in Highly Granular Calorimeters Using Convolutional Normalizing Flows, [arXiv:2405.20407](https://arxiv.org/abs/2405.20407) | [JINST 19 (2024) P09003](https://doi.org/10.1088/1748-0221/19/09/P09003) | [`ConvL2LFlow`](https://github.com/FLC-QU-hep/ConvL2LFlow) | |
| CaloClouds II: Ultra-Fast Geometry-Independent Highly-Granular Calorimeter Simulation, [arXiv:2309.05704](https://arxiv.org/abs/2309.05704) | [JINST 19 (2024) P04020](https://doi.org/10.1088/1748-0221/19/04/P04020) | [`CaloClouds-2`](https://github.com/FLC-QU-hep/CaloClouds-2) | |
| CaloClouds: Fast Geometry-Independent Highly-Granular Calorimeter Simulation, [arXiv:2305.04847](https://arxiv.org/abs/2305.04847) | [JINST 18 (2023) P11025](https://doi.org/10.1088/1748-0221/18/11/P11025) | [`CaloClouds`](https://github.com/FLC-QU-hep/CaloClouds) | |
| Getting High: High Fidelity Simulation of High Granularity Calorimeters with High Speed, [arXiv:2005.05334](https://arxiv.org/abs/2005.05334) | [Comput. Softw. Big Sci. 5 (2021) 13](https://doi.org/10.1007/s41781-021-00056-0) | [`getting_high`](https://github.com/FLC-QU-hep/getting_high) | |

## Datasets

| Dataset | Content | Where |
|---|---|---|
| Multi-Geometry Calorimeter Showers (2026) | Geant4 shower point clouds for SimpleBox, the four LEMURS detectors (CLD, ODD, Par04 SciPb, Par04 SiW) and ALLEGRO, with held-out test sets, about 465 GB | Universität Hamburg Research Data Repository, [doi:10.25592/uhhfdm.19103](https://doi.org/10.25592/uhhfdm.19103) (card on [Hugging Face](https://huggingface.co/datasets/FLC-QU-hep/calorimeter-showers-multi-geometry)) |
| AllShowers Dataset (2026) | Geant4 showers of electrons, photons and charged and neutral hadrons in the ILD detector, point clouds, about 78 GB | Zenodo, [doi:10.5281/zenodo.18020348](https://doi.org/10.5281/zenodo.18020348) |
| CaloHadronic (2025) | Pion showers of 10 to 90 GeV in the ILD ECAL and HCAL, point clouds, 4.1 GB | Zenodo, [doi:10.5281/zenodo.15301636](https://doi.org/10.5281/zenodo.15301636) |
| CaloClouds training data | Photon showers of 10 to 90 GeV in the ILD ECAL, point clouds with up to 6000 points per shower, used by CaloClouds, CaloClouds II and CaloClouds3 | [DESY Sync&Share](https://syncandshare.desy.de/index.php/s/XfDwx33ryERwPdi) |
| High Granularity Electromagnetic Shower Images (2020) | About 24,000 photon showers in the ILD ECAL as 30 x 30 x 30 voxel images, sample of the Getting High training data | Zenodo, [doi:10.5281/zenodo.3826103](https://doi.org/10.5281/zenodo.3826103) |

Shared tooling: [`ShowerData`](https://github.com/FLC-QU-hep/ShowerData), a
library to store and load calorimeter shower data for machine learning.

To add a paper, a dataset or a release, open a pull request editing `profile/README.md` in
[`FLC-QU-hep/.github`](https://github.com/FLC-QU-hep/.github).
