# RECETOX GitHub Organization

<div align="center">

**RECETOX** — Research Center for Toxic Compounds in the Environment

[![Masaryk University](https://img.shields.io/badge/Masaryk%20University-RECETOX-blue)](https://www.muni.cz)
[![EIRENE RI](https://img.shields.io/badge/ESFRI-EIRENE-orange)](https://eirene.eu/)
[![License](https://img.shields.io/badge/license-MIT-green)](#license)

</div>

---

## About RECETOX

**RECETOX** is engaged in research and education on managing the environmental and health risks associated with the chemicals around us. Based at **Masaryk University in Brno, Czech Republic**, we conduct cutting-edge environmental health research and develop diagnostic and preventive tools.

### Our Mission

We study the **human exposome** — the totality of non-genetic factors influencing health over the life course — to understand how chemical exposures impact human health and to develop evidence-based solutions for risk assessment and policy-making.

---

## Research Focus

Our work spans several key areas:

| Area | Description |
|------|-------------|
| **Chemical Exposure Assessment** | Mapping environmental chemicals and their transformations in human biospecimens |
| **Biomarker Analysis** | Targeted quantification of protein and chemical biomarkers using mass spectrometry |
| **Exposomics & Metabolomics** | High-resolution profiling of metabolites and environmental compounds |
| **Data Services** | Processing, analyzing, and interpreting complex spectrometric data |
| **Population Studies** | Cohort studies through CELSPAC and European collaborations |

---

## EIRENE ERIC

RECETOX coordinates the **EIRENE ERIC** (European Research Infrastructure Consortium), a sustainable European infrastructure enabling advanced exposome research across Europe.

### Goals

- Unite and harmonise European capacities for chemical-exposure and health studies
- Provide open-access infrastructure for developing new technologies
- Translate research results into public health actions

Learn more: [https://eirene.eu](https://eirene.eu)

---

## Software & Tools

This organization hosts open-source software developed by RECETOX for environmental health research.

### Mass Spectrometry Data Processing

| Repository | Language | Description |
|------------|----------|-------------|
| **[recetox-aplcms](https://github.com/RECETOX/recetox-aplcms)** | R | Feature detection from LC/MS spectra. Generates feature tables from mzML files with noise filtering and peak alignment. Available on Bioconda as `r-recetox-aplcms`. |
| **[epyraw](https://github.com/RECETOX/epyraw)** | Python | Python wrapper for Thermo Fisher RawFileReader library. Read `.raw` mass spectrometry files in Python (Windows, Linux, macOS). Install via `pip install epyraw`. |
| **[mzmlr](https://github.com/RECETOX/mzmlr)** | R | Validate and read mzML files. Schema validation, spectrum/chromatogram extraction with lazy loading for memory efficiency. Available on CRAN. |
| **[MsBackendMzmlr](https://github.com/RECETOX/MsBackendMzmlr)** | R | MsBackend implementation for the Spectra package using mzmlr. Memory-efficient on-disk access without requiring mzR. |
| **[recetox-xMSannotator](https://github.com/RECETOX/recetox-xMSannotator)** | R | Custom adaptation of xMSannotator for annotated MS data processing. Complete rewrite following original program structure. |
| **[MSMetaEnhancer](https://github.com/RECETOX/MSMetaEnhancer)** | Python | Tool for mass spectra metadata annotation via web services. |
| **[RIAssigner](https://github.com/RECETOX/RIAssigner)** | Python | Retention index (RI) computation for GC-MS data. Supports .msp, .csv, and .tsv formats. |

### Galaxy Workflows & Tools

| Repository | Language | Description |
|------------|----------|-------------|
| **[galaxytools](https://github.com/RECETOX/galaxytools)** | XML/Python/R | Galaxy tool wrappers for untargeted mass spectrometry analysis. Available at [Galaxy UMSA](https://galaxy-umsa.grid.cesnet.cz). MIT licensed. |
| **[ei_spectra_predictions](https://github.com/RECETOX/ei_spectra_predictions)** | - | Workflow for quantum chemistry-based prediction of electron ionization mass spectra for environmental chemicals. |

### Infrastructure & Utilities

| Repository | Language | Description |
|------------|----------|-------------|
| **[fs-irods](https://github.com/RECETOX/fs-irods)** | Python | PyFilesystem2 extension for iRODS data management system. |
| **[specdatri_reporting](https://github.com/RECETOX/specdatri_reporting)** | - | Scripts and GitHub Actions for gathering RECETOX impact metrics and reporting. |
| **[biobank-module](https://github.com/RECETOX/biobank-module)** | TypeScript | Biobank data handling module. Licensed under CC-BY-4.0. |

### Distribution

Our tools are distributed via multiple channels:

| Channel | Purpose |
|---------|---------|
| **Bioconda / Biocontainers** | Easy installation of R and Python packages |
| **PyPI** | Python packages (`epyraw`, `RIAssigner`) |
| **CRAN** | R packages (`mzmlr`) |
| **Galaxy/UMSA** | Web-based workflow execution at [umsa.cerit-sc.cz](https://umsa.cerit-sc.cz/) |
| **GitHub** | Source code access and contribution |

---

## Collaborations

RECETOX collaborates with:
- Academic institutions worldwide
- Industry partners for knowledge transfer
- Policy makers for evidence-based regulations
- European research infrastructure consortia

---

## Contact

**RECETOX**
Masaryk University, Kamenice 753/5, pavilion A29, 625 00 Brno, Czech Republic
- Website: [https://www.recetox.muni.cz](https://www.recetox.muni.cz)
- Email: See [contact page](https://www.recetox.muni.cz/en/contact)
- EIRENE: [https://eirene.eu](https://eirene.eu)

---

## License

Most packages in this organization are released under permissive open-source licenses. See individual repositories for specific license terms.

---

## Acknowledgments

This work is supported by:
- Masaryk University and the Ministry of Education, Youth and Sports of the Czech Republic
- European Union research and innovation programs

---
