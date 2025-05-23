# SAHA: Spatial Atlas of Human Anatomy

The **Spatial Atlas of Human Anatomy (SAHA)** is an open-science initiative to build a subcellular-resolution, multimodal reference atlas of healthy human tissues across organs and systems. This repository reproduces all figures from the SAHA manuscript and provides transparent access to data, analysis scripts, and adapted methods.

## Repository Structure

- `notebooks/` — Jupyter notebooks for each main/extended data figure
- `data/` — Source data for figures (or scripts to download from Zenodo)
- `scripts/` — Python/R scripts for processing and visualization
- `figures/` — Output figures in `.svg` and `.pdf`
- `methods/` — Notes on customized workflows (e.g., MaxFuse, SCIMAP)
- `utils/` — Shared functions (e.g., plotting, statistics)

## Data Access

All large datasets used in this study are publicly available via Zenodo: [https://zenodo.org/communities/saha/](https://zenodo.org/communities/saha/) 

_See `data/zenodo_download.md` for instructions on retrieval._

## Related Tools

- [`saha-maxfuse`](https://github.com/saha-project/saha-maxfuse): Multimodal spatial integration pipeline
- [`saha-scimap`](https://github.com/saha-project/saha-scimap): Cell typing for spatial proteomics data

## Citation

If you use SAHA resources, please cite:
_> [SAHA Manuscript Title], [Authors], [Journal/BioRxiv], [DOI] - To be updated._

## Contact and Contributions

We welcome contributions and extensions. Please open issues or pull requests for discussion.
