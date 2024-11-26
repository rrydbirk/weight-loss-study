This repository holds information for reproducing data and figures for the paper **Cellular and Transcriptional Dynamics of the Human Adipose Tissue during different Weight Loss Modalities** by Loft _et al._.

We provide objects necessary to produce all figures presented in the manuscript, except for QC which we provide as reports due to GDPR restrictions.

# Documents overview

- QC for [visits 1 & 2 (HTML)](https://htmlpreview.github.io/?https://raw.githubusercontent.com/rrydbirk/weight-loss-study/main/QC_visit1and2.html) or [visit 3 (HTML)](https://htmlpreview.github.io/?https://raw.githubusercontent.com/rrydbirk/weight-loss-study/main/QC_visit3.html)
  
- [Objects preparations in R including exports to Python (R Markdown)](https://www.github.com/rrydbirk/weight-loss-study/blob/main/Objects_preparations.Rmd)
  
- [Objects preparations in Python (Jupyter Notebook)](https://www.github.com/rrydbirk/weight-loss-study/blob/main/Objects_preparations.ipynb)
  
- Manuscript figures in R, [HTML](https://htmlpreview.github.io/?https://raw.githubusercontent.com/rrydbirk/weight-loss-study/main/Manuscript_figures.html) / [R Markdown](https://www.github.com/rrydbirk/weight-loss-study/blob/main/Manuscript_figures.Rmd)

- [Velocity figures (Jupyter Notebok)](https://www.github.com/rrydbirk/weight-loss-study/blob/main/Velocity.ipynb)

- [Scenic figures (Jupyter Notebook)](https://www.github.com/rrydbirk/weight-loss-study/blob/main/Scenic.ipynb)

- [Liana figures (Jupyter Notebook)](https://www.github.com/rrydbirk/weight-loss-study/blob/main/Liana.ipynb)

# Data overview

Most data objects are saved in .qs format. In R, please load with the [qs](https://cran.r-project.org/web/packages/qs/index.html) package.

- Conos objects
  
  [Major object, all nuclei and cell types (3 GB)](https://osf.io/w5rk6)
  
  Size: 3218459076 bytes; MD5 checksum: 
  
  [Adipocytes, ASPCs, macrophages (2.4 GB)](https://osf.io/6cku8)
  
  Size: 2474431446 bytes; MD5 checksum: 0ee26b30eab846a16bfe4e75f0155729
  
  [Adipocytes, ASPCs (2 GB)](https://osf.io/fbdy2)
  
  Size: 2066110834 bytes; MD5 checksum: 425fc9cc7756e834657d9b5d28033092
  
  [Adipocytes 1.4 GB](https://osf.io/s857p)
  
  Size: 1428795783 bytes; MD5 checksum: d9a5504e42c4137916fa61d9fb651f8e
  
  [ASPCs (1.2 GB)](https://osf.io/eytx9)
  
  Size: 1257729123 bytes; MD5 checksum: bbc06f0346fcebc3b7c2d98e504a984a
  
  [All immune cells (1.2 GB)](https://osf.io/zce8n)
  
  Size: 1188064109 bytes; MD5 checksum: 16a2b258b16f26d5bec472d3817e8243
  
  [Lymphoid immune cells (540 MB)](https://osf.io/grbn9)
  
  Size: 565546377 bytes; MD5 checksum: 652641d15f7cfe4e77476f2510349fa5
  
  [Myeloid immune cells (1.1 GB)](https://osf.io/23v7t)
  
  Size: 1126006766 bytes; MD5 checksum: 654f426990c21c842b581b6eb4e184a4
  
  [Vascular cells (1.2 GB)](https://osf.io/wupk6)
  
  Size: 1237156917 bytes; MD5 checksum: f0927029b746c62fc3771af928094e33
  
- [Cell correlations (582 MB)](https://osf.io/f68bp)
  
  Zip file containing files for calculating cell correlations to the WATLAS study
  
  Size: 609624031 bytes; MD5 checksum: bd71f5dd2cdd76be232d1665b89b1fc5
  
- [Other objects (3.4 GB)](https://osf.io/gqdfz)
  
  Zip file containing remaining files, e.g., meta data, annotations, files for velocity, etc.
  
  Size: 3624339940 bytes; MD5 checksum: be4160f6fe450dd5ad815565e574aed8
