# <img src="https://coursesandconferences.wellcomeconnectingscience.org/wp-content/themes/wcc_courses_and_conferences/dist/assets/svg/logo.svg" width="300" height="50"> Add Course Title Informatics Guide

**Software used during the course**      

## Software used during the course

| Software | Version (if not latest) | Module | Notes |
|----------|--------------------------|--------|-------|
| [Chrome](https://www.google.com/chrome/) | Latest | All modules | Required for browser-based tools |
| [Firefox](https://www.mozilla.org/firefox/) | Latest | All modules | Alternative browser support |
| [Miniforge](https://github.com/conda-forge/miniforge) | 25.3.1 | General setup | Used for managing Python/R environments |
| [Python](https://www.python.org/) | 3.12.11 | General setup | Core environment for notebooks |
| [Jupyter Notebook](https://jupyter.org/) | 7.4.7 | MPRA QC | Used for interactive analysis |
| [JupyterLab](https://jupyter.org/) | 4.4.9 | MPRA QC | Enhanced notebook interface |
| [marimo](https://github.com/marimo-team/marimo) | 0.16.5 | MPRA QC | Lightweight notebook runner |
| [R](https://www.r-project.org/) | 4.3.3 | MPRA QC | Used for data analysis and visualisation |
| [RStudio](https://posit.co/download/rstudio-desktop/) | 2025.09.2+418 | MPRA QC | IDE for R |
| [Enrich2](https://github.com/FowlerLab/Enrich2) | 2.0.2 | MAVE Data Analysis II | For variant enrichment analysis |
| [CountESS](https://github.com/varianteffect/countess) | 0.1.10 | MAVE Data Analysis II | For sequence counting |
| [tidyverse](https://www.tidyverse.org/) | Latest | MPRA QC | R package suite for data wrangling |
| [ggplot2](https://ggplot2.tidyverse.org/) | Latest | MPRA QC | R package for plotting |
| [dplyr](https://dplyr.tidyverse.org/) | Latest | MPRA QC | R package for data manipulation |
| [Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel) | Latest | Clinical validation | For reviewing clinical datasets |
| [Docker](https://www.docker.com/) | Latest | MAVE Data Analysis I | Used for containerised environments |
| [Nextflow](https://www.nextflow.io/) | Latest | MAVE Data Analysis I | Workflow management system |
| [QUANTS](https://github.com/varianteffect/QUANTS) | 3.1.0.0 | MAVE Data Analysis I | Analysis software for MAVE |
| [MAVE-QC](https://github.com/varianteffect/maveqc) | v0.2.9.229 | MAVE Data Analysis I | QC pipeline for MAVE data |
| [Ensembl VEP](https://www.ensembl.org/info/docs/tools/vep/index.html) | 115.2 | Annotation | 23 GB cache required for local use |


## Bookmarks and Resources

| Resource | Link |
|----------|------|
| DECIPHER | [https://www.deciphergenomics.org/](https://www.deciphergenomics.org/) |
| Mol* Viewer | [https://molstar.org/viewer/](https://molstar.org/viewer/) |
| ClinVar | [https://www.ncbi.nlm.nih.gov/clinvar/](https://www.ncbi.nlm.nih.gov/clinvar/) |

## Rolling Nextflow to version 23.10.1
### notebook bash kernel
```bash
pip install bash_kernel
python -m bash_kernel.install
```
### netflow roll back
```bash
export NXF_VER=23.10.1
curl -s https://get.nextflow.io | bash
mv nextflow ~/.local/bin/nextflow
chmod +x ~/.local/bin/nextflow
```

## Informatics Set-Up
For installation and setup, please refer to the following guides:

- **[Oracle VM VirtualBox Installation Guide](https://github.com/WCSCourses/WCS_Informatics_Guides/blob/main/Installation_Guides/VM_Guide.md)** – Detailed instructions for installing and configuring VirtualBox on different operating systems. *(Note: Separate installations are needed for Intel-based and ARM-based Macs, and the VDI files will differ.)*
- **[Docker Installation Guide](https://github.com/WCSCourses/WCS_Informatics_Guides/blob/main/Installation_Guides/Docker_guide.md)** – Step-by-step guide for installing Docker on Windows, macOS, and Linux.

The Host Operating System Requirements are: <br />
- RAM requirement: 8GB (preferably 12GB) <br />
- Processor requirement: 4 processors (preferably 8) <br />
- Hard disk space: 200GB <br />
- Admin rights to the computer <br />

## Citing and Re-using Course Material

The course data are free to reuse and adapt with appropriate attribution. All course data in these repositories are licensed under the <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/">Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)</a>. <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /> 

Each course landing page is assigned a DOI via Zenodo, providing a stable and citable reference. These DOIs can be found on the respective course landing pages and can be included in CVs or research publications, offering a professional record of the course contributions.

## Interested in attending a course?

Take a look at what courses are coming up at [Wellcome Connecting Science Courses & Conference Website](https://coursesandconferences.wellcomeconnectingscience.org/our-events/).

---

[Wellcome Connecting Science GitHub Home Page](https://github.com/WCSCourses) 

For more information or queries, feel free to contact us via the [Wellcome Connecting Science website](https://coursesandconferences.wellcomeconnectingscience.org).<br /> 
Please find us on socials [Wellcome Connecting Science Linktr](https://linktr.ee/eventswcs)

---
