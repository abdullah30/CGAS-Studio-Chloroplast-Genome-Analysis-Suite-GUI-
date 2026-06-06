# CGAS Studio — Chloroplast Genome Analysis Suite (GUI)


**Download CGAS Studio:** [https://doi.org/10.6084/m9.figshare.32593494](https://doi.org/10.6084/m9.figshare.32593494) — please see [⬇️ Download & Run](#️-download--run) below

**CGAS Studio** is a graphical user interface (GUI) for the [Chloroplast Genome Analysis Suite (CGAS)](https://github.com/abdullah30/Chloroplast-Genome-Analysis-Suite-CGAS), covering Modules 3–14. It allows researchers to run complete chloroplast genome analyses through a simple point-and-click interface — no command-line experience required.

---

## 🔗 Full Documentation & Command-Line Version

All detailed documentation, module descriptions, example datasets, and the original command-line CGAS are available at the main CGAS repository:

> 📦 **[Chloroplast Genome Analysis Suite (CGAS)](https://github.com/abdullah30/Chloroplast-Genome-Analysis-Suite-CGAS)**

---

## ⬇️ Download & Run

1. [**Download CGAS_Studio_v1.0.zip**](https://figshare.com/ndownloader/files/65328519) (hosted on figshare: https://doi.org/10.6084/m9.figshare.32593494)
2. Extract the zip file anywhere on your computer
3. Double-click **`CGAS_Studio.exe`** to launch

That's it — no installation, no Python, no configuration needed.

> **Recommended:** 16 GB RAM and Intel Core i5 or better for large datasets.

---

## 🧬 Modules Included (3–14)

| Module | Analysis |
|--------|----------|
| **03** | Gene Comparison & Normalization |
| **04** | NCBI Submission Preparation |
| **05** | Gene Comparative Analysis |
| **06** | Gene Content Tables (Word) |
| **07** | Genome Structure — LSC / SSC / IR lengths & GC content |
| **08** | Codon Usage — RSCU heatmap & bar plot |
| **09** | Amino Acid Composition |
| **10** | SNP & Substitution Analysis — Ts/Tv ratio |
| **11** | Gene & tRNA Intron Analysis |
| **12** | SSR / Microsatellite Analysis |
| **13** | Nucleotide Diversity (π) |
| **14** | Phylogenomics — supermatrix builder + IQ-TREE inference |

---

## 📦 What Is Inside the Package

Everything needed to run all analyses is bundled — nothing extra to install:

| Tool | Purpose |
|------|---------|
| **R 4.6.0** | Publication-quality figures (PDF + PNG) |
| **MAFFT** | Multiple sequence alignment (Modules 13, 14) |
| **IQ-TREE 3** | Maximum likelihood phylogeny (Module 14) |
| **Java JRE 21** | Required to run MACSE |
| **MACSE** | Codon-aware CDS alignment (Module 14) |

---

## 📂 Input & Output

- **Input:** GenBank files (`.gb` / `.gbk`) for most modules; pairwise FASTA alignments for Module 10
- **Output:** Excel tables, Word documents, PDF and PNG figures — all saved into an output folder alongside your input data

---

## 📄 Citation

If you use CGAS Studio in your research, please cite:

> Abdullah, Yan, R. and Tian, X. (2026), CGAS (Chloroplast Genome Analysis Suite): An automated python pipeline for comprehensive comparative chloroplast genomics. *iMetaOmics* e70093. https://doi.org/10.1002/imo2.70093

Please also cite bundled tools as appropriate — see the [CGAS repository](https://github.com/abdullah30/Chloroplast-Genome-Analysis-Suite-CGAS) for full citation details.

---

## 👤 Author

**Abdullah** — Plant Evolutionary Genomics & Comparative Plastomics

📧 [abd.ullah30@yahoo.com](mailto:abd.ullah30@yahoo.com)  
🔗 [GitHub: abdullah30](https://github.com/abdullah30)
