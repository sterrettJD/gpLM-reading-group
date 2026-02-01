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
* **Topic**: Alpha-Fold 3?
* **Resources**:
  * The original [Alpha-Fold](https://www.nature.com/articles/s41586-021-03819-2)
  * [Alpha-Fold 3](https://www.nature.com/articles/s41586-024-07487-w/)
  * Where Alpha-Fold 3 [struggles]((https://www.ebi.ac.uk/training/online/courses/alphafold/))

### Meeting 3: February 20, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)
* **Topic**: Microscopy: Review and people share where they've seen failures
* **Resources**:
  * [Review](https://journals.biologists.com/jcs/article/137/20/jcs262095/362505/Machine-learning-in-microscopy-insights)

### Meeting 4: March 6, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)
* **Topic**: Dr. Sam Hunter on Time-Series Data
* **Resources**: TBA

### Skipping March 20 due to Spring Break 

### Meeting 5: April 3, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)
* **Topic**: Multiomics Integration
* **Resources**:
  * TBA


### Meeting 6: April 17, 2026
* **Location**: JSCBB B322 and [Zoom](https://cuboulder.zoom.us/j/93190333355)

* **Topic**: Predicting networks based on experimental data (e.g. CRISPR, Perturb-seq)
* **Resources**:
  * https://www.csbj.org/article/S2001-0370(25)00058-3/fulltext


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
