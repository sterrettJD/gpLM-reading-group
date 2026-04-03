# Curriculum for Spring 2026: 

This semester, we are continuing where we left off in Fall to discuss the boom of AI, how to keep up with it, and how it's actually be used.

All meetings are 12:30pm-1:30pm unless noted otherwise.

## Schedule
To be determined based on the topic ideas below!
### Meeting 1: January 23, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)
* **Topic**: Fine-tuning vs Transfer Learning
  * What's the difference. When to use fine-tuning vs transfer learning.
* **Resources**:
  * Fine-tuning help:
    * [Super simple](https://www.geeksforgeeks.org/machine-learning/what-is-the-difference-between-fine-tuning-and-transfer-learning/)
    * [Simple](https://greennode.ai/blog/fine-tuning-vs-transfer-learning) -- I'm pretty sure they had AI make the images and writing on this because it's almost exactly the above link but with more information
    * [More](https://www.tensorflow.org/tutorials/images/transfer_learning) with example
  * [Powerpoint](https://docs.google.com/presentation/d/1ihu4TLXeae-3OYWSFp69h5shg5ggHWCwd93Gfl5EW-Y/edit?usp=sharing) 

### Meeting 2: February 6, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)
* **Topic**: Alpha-Fold 3 (Protein & Ligand Folding)
* **Homework**: Please at least watch the **two short videos** and *if possible* read the benchmarking paper under resources
  * [5 min Video](https://www.youtube.com/watch?v=7q8Uw3rmXyE) on AlphaFold (the OG)
  * [8 min Video](https://www.youtube.com/watch?v=CYncNBMPLLk) on AlphaFold3
* **Resources**:
  * Powerpoint -- Slides on ALpha Fold and diffusion models have been added to the **Tools section** of our [Visual Dictionary](https://docs.google.com/presentation/d/18GktKtegG00VJ-YeRNsjlSoRydSro1z7DQZ1CS_J1ng/edit?usp=sharing)
  * More Videos:
    * 12 min on [more details](https://www.youtube.com/watch?v=3gSy_yN9YBo) on AlphaFold innerworkings
  * Papers
    * [Third-party benchmarking](https://academic.oup.com/bib/article/26/6/bbaf616/8351050) of Alpha-Fold3
    * [AlphaFold](https://www.nature.com/articles/s41586-021-03819-2) original paper
    * [Alpha-Fold 3](https://www.nature.com/articles/s41586-024-07487-w/) original paper
  * Blogs
    * [Problems](https://www.deeporigin.com/blog/alphafold-3-exciting-advance-yet-unresolved-major-issues-remain) with AlphaFold 3
    * [Practical Guide](https://www.ebi.ac.uk/training/online/courses/alphafold/) for AlphaFold 3


### Meeting 3: February 20, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)
* **Topic**: Microscopy: Review and people share where they've seen failures
* **Homework**:
  * [Review](https://journals.biologists.com/jcs/article/137/20/jcs262095/362505/Machine-learning-in-microscopy-insights)
* **Resources**:
  * [Powerpoint](https://docs.google.com/presentation/d/1sLOLa0W-ZiFwsdwweB0OvhvfhfppaHDwigkirZBJPq0/edit?usp=sharing)
  * [Github](https://github.com/jwtay1) of Dr. Jian Wei Tay with some great code examples
  * Older (2023) but very accessible [review](https://doi.org/10.1002/cpz1.819)
  * Added Reinforcement learning and Active learning to [Visual Dictionary](https://docs.google.com/presentation/d/18GktKtegG00VJ-YeRNsjlSoRydSro1z7DQZ1CS_J1ng/edit?usp=sharing)

### Meeting 4: March 6, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)
* **Topic**: Dr. Sam Hunter on Time-Series Data
* **Resources** (OPTIONAL): TBA
  * [In-depth resource](https://doi.org/10.1155/2013/203681) for designing RNA-seq time series analyses with classical models
  * [Cool approach](https://doi.org/10.1093/bib/bbac586) using deep learning
### Skipping March 20 due to Spring Break 

### Meeting 5: April 3, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)
* **Topic**: Multiomics Integration
  * [Technical review](https://doi.org/10.1093/bib/bbaf355) on multiomics integration methods (August 2025)
* **Resources**:
  * [Helpful blog](https://frontlinegenomics.com/a-guide-to-multi-omics-integration-strategies/) on multiomics integration methods
  * Dec 2025 [Review](https://www.sciencedirect.com/science/article/pii/S2215017X25000657) on translationally focused (direct disease) multiomics integration
  * Another journal club from a diff university and [their resources and example analyses](https://med.nyu.edu/research/scientific-cores-shared-resources/multi-omics-study-design-data-integration-resource)
  * A [2026 workshop](https://www.ebi.ac.uk/training/materials/introduction-to-multiomics-data-integration-and-visualisation-materials/course-content/) whose slides/practicals are available
  * Network-based approaoches/resources
    * [Example](https://www.nature.com/articles/s41467-022-29998-8) usage: Systems genomics approach to uncover patient-specific pathogenic pathways
    * [Signalink](http://signalink.org/): Resource with signaling pathways and such to allow merging with expression data to identify relevant pathways
    * [NetworkCommons](https://academic.oup.com/bioinformatics/article/41/2/btaf048/8002097): Resource to unify programming efforts to access 1) prior knowledge, 2) omics data, and 3) network contextualization methods
    * [OmniPath](https://omnipathdb.org/) contains LOTs of prior knowledge about pathways
  * Understanding latent factors & representation learning
    * Accessible [review](https://rnajournal.cshlp.org/content/32/4/504.long) from 2026 in SC data
  * Very commonly used tools 
    * [MOFA](https://biofam.github.io/MOFA2/)
      * "interpretable low-dimensional representation in terms of a few latent factors. These learnt factors represent the driving sources of variation across data modalities, thus facilitating the identification of cellular states or disease subgroups"
      * [Presentation](https://ftp.ebi.ac.uk/pub/training/2026/Introduction-to-multi-omics-data-integration-visualisation_2026/Day_2/Lecture3_mofa_2026.pdf) from a workshop
      * [Practical](https://www.ebi.ac.uk/training/materials/introduction-to-multiomics-data-integration-and-visualisation-materials/group-projects/multi-omics-integration-for-personalised-medicine/) example usage 


### Meeting 6: April 17, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)

* **Topic**: Predicting networks based on experimental data (e.g. CRISPR, Perturb-seq)
* **Resources**:
  * https://www.csbj.org/article/S2001-0370(25)00058-3/fulltext

### Meeting 7: April 24, 2026
* **Location**: [Zoom](https://cuboulder.zoom.us/j/93190333355)

* **Topic**: AI in Microscopy Tips and Caveats with [Dr. Jian Tay](https://www.linkedin.com/in/jwtay/)
* **Resources**:
  *

## Topic Ideas 
**Microscopy**

**Batch Effects**
* Should models correct batch effects or expose them?
* Is removing batch effect erase biological truth? How can we tell?
* Examples: ComBat, totalVI 
* Regression approaches: DESeq/Limma, [Combat-seq](https://academic.oup.com/nargab/article/2/3/lqaa078/590951)
* Generative model approaches: [TotalVI](https://www.nature.com/articles/s41592-020-01050-x)

**Multiomics Integration**
* Is AI actually better at integrating a bunch of datasets compared to humans?
* When does adding a modality reduce signal-to-noise? 
* Should modalities be fused early, late, or not at all?
* How do we interpret disagreement between modalities?

**Causality with experiments?**
* e.g. Perturb-seq + ML


**Guest Speakers and looking at code**
* Matt to share his research
* Michael Shiferaw to share his LLM project?

**Learning about the capabilities and limitations of current models**
* Google's TxGemma (Focuses on therapeutic development): 
  * [Paper](https://storage.googleapis.com/research-media/txgemma/txgemma-report.pdf)
  * [Blog](https://developers.googleblog.com/en/introducing-txgemma-open-models-improving-therapeutics-development/)
* [Lyra](https://arxiv.org/abs/2503.16351) (Multi-task, like protein fitness, antibody design, RNA function prediction)
