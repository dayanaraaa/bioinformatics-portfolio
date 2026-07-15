# Bioinformatics Portfolio

I'm a master of Data Science (Bioinformatics) student at Durham University, working on protein sequence and structural analysis, drug-target discovery, and machine learning on protein sequence data. I came into this through undergrad work engineering a point mutation in β-glucosidase, and that's what pulled me toward protein language models.

## Current Work

**MDS Dissertation** - [NirK-PCuAC co-occurrence in bacteria](https://github.com/dayanaraaa/predicting-nirk-pcuac-cooccurrence)

I'm investigating whether the bacterial co-occurrence of two copper-handling proteins, a PCu chaperone (PCuAC) and copper-containing nitrite reductase (NirK), can be predicted from protein sequence features alone. I am currently building a dataset through BLASTp homology searches against the NCBI RefSeq Protein database, filtering candidate homologues using conserved copper-binding residues identified from the literature, and classifying species into three co-occurrence groups to investigate sequence-level signals associated with protein partnership. Model development will use scikit-learn, pandas, and NumPy, with R used for statistical evaluation as the project progresses.

## Selected Projects

- **[WNV NS5 drug target discovery](https://github.com/dayanaraaa/wnv-ns5-analysis)**
NIH-funded CURIE programme project screening the West Nile Virus NS5 protein for druggable pockets, combining sequence alignment, disorder prediction (IUPRED), and pocket druggability scoring (PockDrug). Narrowed 11 candidate binding pockets down to 2 high-priority sites by integrating conservation data with structural confidence. WNV causes 96% of US arboviral neuroinvasive disease cases and still has no approved human vaccine.
- **Coronavirus NSP12/NSP13 comparative analysis**
Compared four coronavirus clades (HCoV, BCoV, MERS, SARS) to find conserved, high-druggability pockets as broad-spectrum antiviral targets. Scored 4 candidate pockets (PockDrug 0.89–0.96) and identified Pocket 1 (0.96) as the strongest target based on conservation and surface accessibility.
- **TERT evolutionary and structural analysis**
Structural and evolutionary analysis of telomerase reverse transcriptase (UniProt O14746), a protein implicated in hepatocellular carcinoma, HPV-associated cancer, and Gaucher's disease. Ran BLAST homology search across three databases, multiple sequence alignment in Jalview, and phylogenetic tree construction, at the Siltberg-Liberles Lab, FIU.
- **β-glucosidase protein engineering (N293L)**
The project that got me into this field. Engineered and characterised the N293L mutation in *Paenibacillus polymyxa* β-glucosidase B, then compared it against N293C/M/V mutants to see how residue polarity affects catalytic efficiency (T50 = 30.0 ± 18.1 °C, Kcat = 0.3 ± 0.1 min⁻¹). Results submitted to the D2D database.

## Research Interests  
I'm mainly interested in whether sequence-derived features and protein language model embeddings carry enough signal to predict structural and functional properties: binding partners, druggable pockets, stability. All without needing a resolved structure. That question runs through the dissertation and most of the drug-target work above. Genomics and transcriptomics come up too, mostly through RNA-seq/DESeq2 coursework.

## Technical Skills

Python, R, Bash/Linux, scikit-learn, pandas, NumPy, Bioconductor (DESeq2, clusterProfiler), BLAST, HMMER, PyMOL, AlphaFold

## Portfolio Website

Full portfolio (including undergrad work and visual summaries) coming soon.
