# Nurulamin Shaikh

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nurulamin-shaikh/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nurulamin6191@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nurulamin6191)
[![CSIR--UGC NET](https://img.shields.io/badge/CSIR--NET%20JRF-96.89%20Percentile-0052cc?style=for-the-badge)](https://csirnet.nta.ac.in)

**Junior Research Fellow — Computational Biology | Immuno-Oncology | Oncolytic Immuno Virotherapy**  
*Advanced Centre for Treatment, Research and Education in Cancer (ACTREC), Tata Memorial Centre, Navi Mumbai, India*

---

</div>

## 🧬 About Me

I am a **Junior Research Fellow** working at the intersection of **computational genomics**, **systems biology**, and **translational cancer therapeutics** under **Dr. Albeena Nisar** at **ACTREC, Tata Memorial Centre**.

My research focuses on understanding how **oncolytic Immuno virotherapy (OIVT)** remodels the **tumor immune microenvironment (TME)** in solid malignancies. I develop and deploy automated, reproducible computational pipelines integrating **single-cell transcriptomics (scRNA-seq)**, **bulk RNA-seq**, **co-expression network topology (WGCNA)**, and **immuno-informatics** to discover therapeutic targets and biomarkers of viral susceptibility.

- 🔭 **Current Focus:** Target discovery and immune microenvironment remodeling for oncolytic Immuno virotherapy platforms.
- 🧪 **Research Background:** Both computational genomics (NGS, variant calling, neoantigen prediction) and foundational biotechnology laboratory training (fermentation optimization, microbial bioprocessing).
- 🏆 **National Qualifications:** Qualified **CSIR-UGC NET (Life Sciences)** with **96.89 Percentile** (Junior Research Fellowship & Ph.D. eligibility); qualified **JGEEBILS**.
- 💬 **Ask me about:** Single-Cell RNA-seq (scVI), bulk RNA-seq workflows, neoantigen prediction pipelines, WGCNA, Bash/Python automation on PBS HPC clusters.

---

## 🔬 Research Interests

- **Oncolytic Immuno Virotherapy (OIVT):** Dissecting molecular mechanisms of viral-mediated tumor lysis and immune stimulation.
- **Tumor Immune Microenvironment (TME) Remodeling:** Tracking chemokine induction, interferon signaling pathways, and immune effector recruitment in solid tumors.
- **Single-Cell & Bulk Multi-Omics Integration:** Uncovering cell-type specific expression states, gene co-expression modules, and biomarkers of viral susceptibility.
- **Personalised Neoantigen Discovery:** Constructing end-to-end computational pipelines for HLA typing, somatic variant calling, and high-affinity peptide-MHC binding predictions.
- **Reproducible HPC Workflows:** Building robust, scalable Linux shell scripts and Python/R workflows for high-throughput sequencing clusters.

---

## 🛠️ Technical Skills

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Computational Genomics & NGS** | `Single-Cell RNA-seq (scVI, Seurat, Scanpy)` `Bulk RNA-seq (DESeq2)` `WGCNA` `Computational Immune Deconvolution` `STAR Aligner` `FastQC` `Trim Galore` |
| **Immuno-informatics & Variant Calling** | `Somatic Variant Calling (GATK HaplotypeCaller, FreeBayes)` `Variant Annotation (SnpEff, Ensembl VEP)` `HLA Typing (OptiType)` `Neoantigen Prediction (MHCflurry)` |
| **Structural Biology & Networks** | `AlphaFold` `UCSF ChimeraX` `GROMACS` `Amber` `STRING PPI Networks` |
| **AI, Machine Learning & Data Science** | `Classical Machine Learning (Scikit-Learn)` `Lasso Penalized Regression` `Generative AI & Local LLMs` `NumPy` `Pandas` `SciPy` `Matplotlib` `Seaborn` |
| **Languages & Infrastructure** | `Python` `R Programming` `Bash / Linux Shell Scripting` `PBS Torque HPC Scheduler` `Git & GitHub` `Docker` `Ubuntu Linux` |
| **Experimental Biotechnology** | `Microbial Isolation & Culture` `Enzyme Activity Assays` `Process Optimization via One Factor at a Time (OFAT)` `GMP / Green Room Entry-Exit Protocols` `Biowaste Management` |

</div>

---

## 🚀 Key Research Projects & Repositories

### 1. Systems Biology of Oncolytic Virus-Mediated Tumor Priming in HNSCC
* **Institution:** ACTREC, Tata Memorial Centre | **Guide:** Dr. Albeena Nisar
* **Overview:** Investigated therapeutic resistance and immune cell exclusion in Head and Neck Squamous Cell Carcinoma (HNSCC) by modeling how oncolytic viral exposure primes the tumor microenvironment for cellular effectors.
* **Methodology:**
  * Integrated single-cell transcriptomics (**23 samples; deep learning-based scVI**) with bulk RNA-seq cohorts (**TCGA-HNSC; 564 samples**).
  * Performed differential gene expression (**DESeq2**) combined with Weighted Gene Co-expression Network Analysis (**WGCNA**) and **Lasso regression** to identify candidate gene regulatory modules and immune signatures associated with viral susceptibility.
  * Mapped protein-protein interaction networks (**STRING DB**) and conducted computational immune deconvolution to evaluate chemokine-mediated lymphocyte recruitment, antigen presentation machinery, and interferon response signatures.
  * Automated data processing on PBS-scheduled High-Performance Computing (HPC) clusters.

### 2. In Silico Identification of Neoantigens for Personalised Immunotherapy in Glioblastoma
* **Repository:** [Nurulamin6191/GBM-Personalized-NeoAntigen-Vaccine](https://github.com/Nurulamin6191/GBM-Personalized-NeoAntigen-Vaccine)
* **Institution:** BioTecNika Info Labs (Remote) | **Mentor:** Dr. Elamathi Natrajan
* **Overview:** Engineered an automated, end-to-end pipeline in Python and Bash on Ubuntu Linux to detect patient-specific immunogenic neoepitopes from high-throughput patient RNA-seq datasets (SRR30677899, SRR30677902).
* **Methodology:**
  * Pipeline orchestration: FastQC quality control and adapter trimming with **Trim Galore**.
  * Splice-aware alignment against **GRCh38** reference genome using **STAR Aligner**.
  * Somatic variant calling using **GATK HaplotypeCaller** and **FreeBayes**; variant functional consequence prediction via **SnpEff** and **Ensembl VEP**.
  * Four-digit HLA class I allele typing with **OptiType** and peptide-MHC binding affinity prediction via **MHCflurry**.

### 3. Bacterial Fermentation Process Optimization via OFAT
* **Institution:** ISBM University (M.Sc. Dissertation Project, 2022 – 2023)
* **Overview:** Isolated and screened cellulolytic bacterial strains (*Bacillus subtilis* isolate C10) from soil environments using CMC agar and Congo Red assay.
* **Methodology:**
  * Systematically optimized fermentation conditions (pH, temperature, substrate concentration) using **One Factor at a Time (OFAT)** methodology.
  * Achieved a **10% enhancement** in cellulase enzyme yield for industrial bioprocessing applications.

---

## 📑 Publications & Conference Presentations

- **Platform Poster:**  
  *“Development of India’s First Indigenous HSV-1-Based Oncolytic ImmunoVirotherapy Platform for Solid Tumours”*  
  **International Society for Cell & Gene Therapy (ISCT) Annual Meeting, 2026**  
  *Authors:* Hiba Iqbal, Ahmad Adeel, Pritam Poonia, Tanay Rangankar, Ali Ahmed, **Nurulamin Shaikh**, Siddhartha Pandya, Abhilash Nair, Mehak Mehta, Shilpa Bhowmick, Sadhna Singh, Prasad Savkare, Gaurav Narula, Vainav Patel, Albeena Nisar.

- **Systems Biology Poster:**  
  *“Systems Biology Analysis of Oncolytic Virus-Mediated Tumor Priming for CAR-NK Therapy in Head and Neck Cancer”*  
  **International Society for Cell & Gene Therapy (ISCT) Annual Meeting, 2026**  
  *Authors:* Albeena Nisar, Ahmad Adeel, **Nurulamin Shaikh**, Siddhartha Pandya.

---

## 🎓 Honors

* **CSIR-UGC NET (Life Sciences):** Qualified for **Junior Research Fellowship (JRF) & Ph.D.** with **96.89 Percentile** (CSIR-NET 2026 / June 2025).
* **JGEEBILS:** Qualified Joint Graduate Entrance Examination for Biology and Interdisciplinary Life Sciences.
* **Cleanroom / GMP Standards:** Completed institutional training in Biowaste Management and Green Room / Cleanroom Entry–Exit Protocols.
* **AI/ML Training:** Hands-on Workshop on AI, Machine Learning & Generative AI in Oncology, Department of Digital and Computational Oncology, ACTREC, Tata Memorial Centre (2026).

---

## 📬 Get in Touch

* **Email:** [nurulamin6191@gmail.com](mailto:nurulamin6191@gmail.com)
* **LinkedIn:** [linkedin.com/in/nurulamin-shaikh](https://www.linkedin.com/in/nurulamin-shaikh/)
* **GitHub:** [github.com/Nurulamin6191](https://github.com/Nurulamin6191)
* **Lab:** Dr. Albeena Nisar's Laboratory, ACTREC, Tata Memorial Centre, Kharghar, Navi Mumbai, India

---
<div align="center">
<sub>Rigorous science • Reproducible pipelines • Collaborative oncology</sub>
</div>
