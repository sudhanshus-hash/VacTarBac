# VacTarBac: Vaccine Target Database for Bacteria

Welcome to the official repository and documentation overview for **VacTarBac**, a comprehensive web resource designed for the identification of potential subunit vaccine candidates against major pathogenic species of bacteria. This platform utilizes an integrated immunoinformatic approach to screen antigenic proteins—specifically virulence factors and essential gene products—to systematically derive epitope-based vaccine candidates.

**Web Server:** [http://webs.iiitd.edu.in/raghava/vactarbac/](http://webs.iiitd.edu.in/raghava/vactarbac/)



## Citation

Nagpal, G., Usmani, S. S., & Raghava, G. P. S. (2018).
**A Web Resource for Designing Subunit Vaccine Against Major Pathogenic Species of Bacteria.**
*Frontiers in Immunology*, 9:2280.
[https://doi.org/10.3389/fimmu.2018.02280](https://doi.org/10.3389/fimmu.2018.02280)
This tool and dataset is also available on Zenodo at https://doi.org/10.5281/zenodo.20052782



## About the Database

VacTarBac was developed to address the global threat of drug-resistant bacterial strains by facilitating the rapid design of subunit vaccines. It integrates large-scale sequencing data and reverse vaccinology principles to predict epitopes capable of stimulating different arms of the immune system (humoral and cell-mediated).

The database consolidates and analyzes data from:
* **Virulence Factor Database (VFDB):** Core dataset covering experimentally verified virulence genes.
* **Database of Essential Genes (DEG):** Genomic elements mandatory for bacterial survival.
* **Immune Epitope Database (IEDB):** Experimentally reported epitopes mapped onto target proteins for validation.



## Key Features

### Comprehensive Dataset
* **14 Pathogenic Bacteria:** Includes high-priority species such as *Mycobacterium tuberculosis*, *Escherichia coli*, *Staphylococcus aureus*, and *Vibrio cholerae*.
* **Target Proteins:** Detailed analysis of 1,459 virulence factors and 546 essential gene products.
* **Localization-Specific Targets:** Proteins are categorized by cellular location, including membrane, envelope, repair, and secretory proteins.
* **252 Unique Epitopes:** A collection of stringently filtered candidates predicted to be T-cell epitopes, B-cell epitopes, and MHC II binders.

### Built-in Tools
* **Epitope Prediction Pipeline:** Integrates advanced tools like LBtope (B-cell), ProPred (MHC II), CTLpred (T-cell), and VaxinPAD (immunomodulatory adjuvants).
* **Visualization Modules:** Interactive Java-enabled and traditional graphical views to present antigenicity profiles and epitope density.
* **Search & Browse:** Users can query by specific bacterial species or browse recommended top-ranked antigens.



## Overview

VacTarBac is organized to provide streamlined access to immunogenic data through a multi-step pipeline:
1.  **Selection of Targets:** Prioritizing virulence factors and essential proteins likely to be accessible to the immune system.
2.  **Epitope Mapping:** Identification of linear and conformational immunogenic regions.
3.  **Self-Tolerance Filtering:** Identification and removal of "self-epitopes" by mapping candidates against 1,000 human proteomes to ensure safety and prevent autoimmunity.
4.  **Vaccine Candidate Generation:** Final lists of peptide sequences with high probability of activating the immune system.



## Applications

* **Reverse Vaccinology:** Rapid identification of novel vaccine candidates directly from genomic and proteomic sequences.
* **Therapeutic Research:** Reducing experimental overhead by selecting high-density epitope regions for *in vitro* and *in vivo* testing.
* **Public Health:** Accelerating the development of vaccines for diseases where antimicrobial resistance has rendered traditional treatments ineffective.



## Contact & Authors

**Prof. G.P.S. Raghava**
Email: raghava@iiitd.ac.in
Center for Computational Biology, Indraprastha Institute of Information Technology (IIITD), Okhla, New Delhi, India.

---

## License

This resource and the accompanying article are distributed under the terms of the **Creative Commons Attribution License (CC BY 4.0)**, which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.
