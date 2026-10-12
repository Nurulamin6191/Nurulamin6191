# Nurulamin Shaikh

<p align="left">
  <a href="https://www.linkedin.com/in/nurulamin-shaikh/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:nurulamin6191@gmail.com"><img src="https://img.shields.io/badge/Email-nurulamin6191@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Nurulamin6191"><img src="https://img.shields.io/badge/GitHub-Nurulamin6191-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://img.shields.io/badge/CSIR--UGC%20NET-JRF%2096.89%25ile-0052cc?style=flat-square" alt="CSIR-NET JRF" />
  <img src="https://img.shields.io/badge/Location-Navi%20Mumbai%2C%20India-blue?style=flat-square&logo=google-maps&logoColor=white" alt="Location" />
</p>

> **Junior Research Fellow | Computational Biology & Immuno-Genomics**  
> *Laboratory of Dr. Albeena Nisar | Advanced Centre for Treatment, Research and Education in Cancer (ACTREC), Tata Memorial Centre*

---

### 🧬 About Me

I am a **Computational Biologist** and **Junior Research Fellow** at **ACTREC, Tata Memorial Centre**, working at the interface of **computational genomics**, **systems biology**, and **translational cancer therapeutics**. 

My core research focuses on understanding how **oncolytic Immuno virotherapy (OIVT)** remodels the **tumor immune microenvironment (TME)** in solid malignancies. I develop and deploy automated, reproducible computational pipelines integrating **single-cell transcriptomics (scRNA-seq)**, **bulk RNA-seq**, **co-expression network topology (WGCNA)**, and **immuno-informatics** to discover therapeutic targets and biomarkers of viral susceptibility.

* 🔬 **Current Research:** Systems biology target discovery and tumor immune microenvironment remodeling for oncolytic Immuno virotherapy platforms.
* 🧪 **Dual Training:** Bilingual research background spanning computational genomics (NGS, variant calling, neoepitope prediction) and wet-lab biotechnology (microbial bioprocessing, OFAT fermentation optimization, cleanroom GMP protocols).
* 🏆 **Academic Honors:** Qualified **CSIR-UGC NET (Life Sciences)** with **96.89 Percentile** for Junior Research Fellowship (JRF) & Ph.D. admissions; qualified **JGEEBILS**.
* ⚡ **Open To:** Interdisciplinary collaborations on single-cell genomics, translational immuno-oncology, and viral therapeutic target discovery.

---

### 🔬 Core Research Domains

```
├── Oncolytic Immuno Virotherapy (OIVT) ─── Viral tropism, immune priming & pro-inflammatory remodeling
├── Single-Cell & Bulk Transcriptomics ──── scVI deep generative models, DESeq2 & WGCNA co-expression
├── Personalised Immuno-Genomics ────────── Somatic variant calling, HLA-I typing & neoantigen discovery
└── Structural Biology & Biophysics ─────── Macromolecular modeling, AlphaFold & protein interaction networks
```

---

### 🛠️ Technical Stack & Workflow Architecture

| Workflow Phase | Frameworks & Tools |
| :--- | :--- |
| **Single-Cell & Spatial Omics** | `scVI` • `Scanpy` • `Seurat` • `Single-Cell RNA-seq (23-sample integration)` |
| **Transcriptomics & Systems Biology** | `DESeq2` • `WGCNA` • `Computational Immune Deconvolution` • `TCGA-HNSC Multi-Omics` |
| **NGS & Somatic Variant Calling** | `STAR Aligner` • `FastQC` • `Trim Galore` • `GATK HaplotypeCaller` • `FreeBayes` • `Ensembl VEP` • `SnpEff` |
| **Immuno-Informatics** | `OptiType (4-digit HLA Class I Typing)` • `MHCflurry (Peptide-MHC Binding Affinity)` |
| **Structural Biology & Biophysics** | `AlphaFold` • `UCSF ChimeraX` • `GROMACS` • `Amber` • `STRING PPI Networks` |
| **Statistical Modeling & ML** | `Scikit-Learn` • `Penalized Lasso Regression` • `Generative AI & Local LLMs` • `NumPy` • `Pandas` • `SciPy` |
| **Scientific Computing & HPC** | `Python` • `R Programming` • `Bash / Linux Shell Scripting` • `PBS Torque HPC Scheduler` • `Docker` • `Git / GitHub` |
| **Laboratory & GMP Standards** | `Microbial Isolation & Culture` • `One Factor at a Time (OFAT)` • `Cleanroom / Green Room GMP Protocol` • `Biowaste Mgmt` |

---

### 🚀 Featured Repositories & Scientific Projects

#### 1. [GBM-Personalized-NeoAntigen-Vaccine](https://github.com/Nurulamin6191/GBM-Personalized-NeoAntigen-Vaccine)
> **Automated In Silico Pipeline for Neoantigen Identification in Glioblastoma**  
> *Developed under Dr. Elamathi Natrajan (BioTecNika)*
* Automated, reproducible end-to-end pipeline in Python and Bash on Ubuntu Linux for detecting patient-specific immunogenic neoepitopes from high-throughput patient RNA-seq cohorts (`SRR30677899`, `SRR30677902`).
* Performs FastQC quality control, Trim Galore adapter trimming, splice-aware alignment via **STAR Aligner** (GRCh38), and cross-validated somatic variant calling with **GATK** and **FreeBayes**.
* Integrates **OptiType** for 4-digit HLA class I allele typing and **MHCflurry** for high-affinity peptide-MHC binding predictions.
* 🔗 [Explore Repository →](https://github.com/Nurulamin6191/GBM-Personalized-NeoAntigen-Vaccine)

#### 2. Systems Biology of Oncolytic Virus Priming in Solid Tumors (HNSCC)
> *ACTREC, Tata Memorial Centre | Laboratory of Dr. Albeena Nisar*
* Dissected immune cell exclusion in Head and Neck Squamous Cell Carcinoma (HNSCC) by modeling how oncolytic viral exposure primes the tumor microenvironment for cellular effectors.
* Integrated single-cell transcriptomics (**23 samples; deep learning via scVI**) with **TCGA-HNSC bulk RNA-seq cohorts (564 samples)**.
* Applied **DESeq2**, **WGCNA**, and **Lasso regression** to isolate core gene regulatory modules and immune signatures linked to viral susceptibility.
* Mapped **STRING DB** protein-protein interaction networks and computed immune cell deconvolution to assess chemokine recruitment, antigen presentation, and interferon pathways on PBS-scheduled HPC clusters.

#### 3. [LabScribe-AI](https://github.com/Nurulamin6191/LabScribe-AI)
> **Privacy-First Meeting & Scientific Companion for Biomedical Researchers**
* Tailored for laboratory PIs, oncologists, geneticists, and research teams to document lab seminars, journal clubs, and scientific discussions with zero data leakage.
* 🔗 [Explore Repository →](https://github.com/Nurulamin6191/LabScribe-AI)

#### 4. Community Resources
* [Bioinformatics_Tools](https://github.com/Nurulamin6191/Bioinformatics_Tools) — Curated collection of high-impact computational biology packages and resources.
* [Learn_Bioinformatics](https://github.com/Nurulamin6191/Learn_Bioinformatics) — Structured curriculum and roadmap for self-directed computational biology training.

---

### 📑 Publications & Conference Presentations

* **Platform Presentation:**  
  *“Development of India’s First Indigenous HSV-1-Based Oncolytic ImmunoVirotherapy Platform for Solid Tumours”*  
  **International Society for Cell & Gene Therapy (ISCT) Annual Meeting, 2026**  
  *Co-authors:* Hiba Iqbal, Ahmad Adeel, Pritam Poonia, Tanay Rangankar, Ali Ahmed, **Nurulamin Shaikh**, Siddhartha Pandya, Abhilash Nair, Mehak Mehta, Shilpa Bhowmick, Sadhna Singh, Prasad Savkare, Gaurav Narula, Vainav Patel, Albeena Nisar.

* **Systems Biology Presentation:**  
  *“Systems Biology Analysis of Oncolytic Virus-Mediated Tumor Priming for CAR-NK Therapy in Head and Neck Cancer”*  
  **International Society for Cell & Gene Therapy (ISCT) Annual Meeting, 2026**  
  *Authors:* Albeena Nisar, Ahmad Adeel, **Nurulamin Shaikh**, Siddhartha Pandya.

---

### 🎓 Academic Qualifications & Training

* **Master of Science (M.Sc.) in Biotechnology** (2021 – 2023) | *ISBM University* (64.87%)  
  *Dissertation:* Microbial process optimization via One Factor at a Time (OFAT) methodology, achieving a 10% increase in cellulase yield from *Bacillus subtilis* (isolate C10).
* **Bachelor of Science (B.Sc.) in Biotechnology** (2018 – 2021) | *VES College, Mumbai University*  
  *Score:* **CGPA: 8.92 / 10.00 (Distinction)**
* **CSIR-UGC NET (Life Sciences):** Qualified for **Junior Research Fellowship (JRF) & Ph.D.** with **96.89 Percentile** (CSIR-NET 2026 / June 2025).
* **JGEEBILS:** Qualified Joint Graduate Entrance Examination for Biology and Interdisciplinary Life Sciences.
* **Specialized Training:**  
  * Good Manufacturing Practice (GMP) & Green Room / Cleanroom Entry–Exit Protocols (ACTREC).  
  * Hands-on Workshop on AI, Machine Learning & Generative AI in Oncology (ACTREC, 2026).

---

### 📊 GitHub Activity

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Nurulamin6191&show_icons=true&theme=tokyonight&hide_border=true" alt="Nurulamin's GitHub Stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nurulamin6191&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="150" />
</p>

---

### 📬 Connect & Collaborate

* 📧 **Email:** [nurulamin6191@gmail.com](mailto:nurulamin6191@gmail.com)
* 💼 **LinkedIn:** [linkedin.com/in/nurulamin-shaikh](https://www.linkedin.com/in/nurulamin-shaikh/)
* 💻 **GitHub:** [github.com/Nurulamin6191](https://github.com/Nurulamin6191)
* 🏛️ **Affiliation:** Dr. Albeena Nisar's Laboratory, ACTREC, Tata Memorial Centre, Kharghar, Navi Mumbai, Maharashtra 410210, India

<p align="center">
  <sub><em>Translational Computational Oncology • Reproducible Multi-Omics Pipelines • Open Science</em></sub>
</p>
