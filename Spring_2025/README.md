# Curriculum for Spring 2025

## Meeting 1: Feb 17th: LATEST EXTENSION OF LLMs IN BIOLOGY
* Reading: [Large language models in bioinformatics: applications and perspectives](https://pmc.ncbi.nlm.nih.gov/articles/PMC10802675/)
* Optional Resource: A **much** longer [review](https://arxiv.org/abs/2401.14656)

## Meeting 2: March 3rd: PREDICTING GENE SET FUNCTION (Text to Function)
* Reading: [Evaluation of large language models for discovery of gene set function](https://doi.org/10.1038/s41592-024-02525-x)

## Meeting 3: March 17th: GUEST SPEAKER
* Speaker: [Kumar Thurimella](https://kthurimella.github.io/) - [Protein Language Models Uncover Carbohydrate-Active Enzyme Function in Metagenomics](https://pubmed.ncbi.nlm.nih.gov/37961379/)
  * PhD, Class of 2024, University of Cambridge (Gates Cambridge Scholar)
  * MD Candidate, Class of 2026, University of Colorado - School of Medicine

## Meeting 3: March 31st: CHAT ABOUT OUR SUCCESSES/FAILURES IN TRYING MODELS
* Have done: Check out a LLM focused model (read/scan the paper and **try** to run the model). Some Ideas are below:

| Input Data | Task | Tools/Models |
|------------|------|-------------|
| **DNA sequence** | Predicts genome-wide variant effects | DNABERT1/2, GPN (variant effects in coding regions), Nucleotide transformer |
| | Predicts cis-regulatory regions | DNABERT1/2, BERT-Promoter, iEnhancer-BERT, Nucleotide Transformer |
| | Predicts DNA-protein interaction (e.g., which proteins bind) | DNABERT 1/2, TFBert, GROVER, MoDNA |
| | Predicts DNA methylation | BERT6mA, iDNA-ABF, iDNA-ABT, MuLan-Methyl |
| | Predicts RNA splice sites | DNABERT, DNABERT-2 |
| **RNA sequence** | Predict 2D/3D structure of RNA | RNA-FM (predict structures), RNA-MSM (uses homologous sequences), RNA-FM |
| | RNA structural alignment or clustering | RNABERT |
| | Predict RNA splice sites | SpliceBERT |
| | Predict N7-methylguanosine modification | BERT-m7G |
| | Predict RNA 2’-O-methylation modification | Bert2Ome |
| | Predict RNA modifications | Rm-LR |
| | Predict association between miRNA, lncRNA, and disease | BertNDA |
| | Predict lncRNAs | LncCat |
| | Predict lncRNA coding potential | LSCPP-BERT |
| | Predict protein expression | CodonBERT |
| **Protein sequences, MSAs, Gene ontology annotations, Triplets of protein-relation-attribute, Protein property descriptions** | Predict Secondary structure & contact | MSA Transformer, ProtTrans, SPRoBERTa, TAPE, KeAP |
| | Generate protein sequences | ProGen, ProtGPT |
| | Predict protein function | SPRoBERTa, ProtST, PromptProtein |
| | Predict major PTMs | ProteinBERT |
| | Predict evolution and mutation | SPRoBERTa, UniRep, ESM-1b, TAPE |
| | Predict biophysical properties | TAPE, PromptProtein |
| | PPI and binding affinity | KeAP |
| | Predict antigen-receptor binding | MHCRoBERTa, BERTMHC, TCR-BERT, SC-AIR-BERT |
| | Predict antigen-antibody binding | AbLang, AntiBERTa, EATLM |
| **Molecular SMILES** | Predict molecular properties | SMILES-BERT, ChemBERTa, K-BERT |
| | Generating molecules | MolGPT |
| **Molecular graphs** | Predict molecular properties (e.g., Absorption, Distribution, Metabolism, Extraction, Toxicology, Pharmacokinetics) | MOLE-BERT |
| **Molecular fingerprints and protein sequences** | Predict drug-target interaction | DTI-BERT |
| **Molecular SMILES and protein sequences** | Predict Synergistic Effects | TransDTI, C2P2 |
| **scRNA-seq data** | Cell clustering | tGPT, scFoundation |
| | Cell type annotation | CIForm, TOSICA, scTransSort, TransCluster, scBERT, scGPT |
| | Gene function analyses (gene expression prediction, gene network inference, gene) | scGPT, scFoundation, Geneformer |


* During Meeting: We'll talk through what was difficult, cool, confusing, helpful, etc about trying to get the models to work. We will also pick a model to play with for next meeting


## Meeting 4: April 14th: REVIEW of LLM models for genetic variant classification
* We read this review: [Language modeeling techniques for analyzing the impact of human genetic variants](https://arxiv.org/html/2503.10655v1)

## Meeting 5: April 28th: WORKSHOP DNA-BERT2 with Toy Data
* We went through fine-tuning DNABERT2 to classify sequences and then used SHAP to interpret what features/tokens the model was using to classify the sequences.
* Code for this can be found at Testing_BERT_Toy.ipynb

## Meeting 6: May 12th: TBD
