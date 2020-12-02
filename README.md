# sig2lead_beta
Sig2Lead is an applications that implements a new appraoch for drug discovery, dubbed connectivity enhanced Structure Activity Relationship (ceSAR). ceSAR improves on current methods by combining docking and virtual screening approaches with pharmacogenomics and transcriptional signature connectivity analysis, capitalizing on the landmark LINCS library of transcriptional signatures of over 20,000 drug-like molecules and ~5,000 gene knock-downs (KDs) to connect small molecules and their potential targets. For a set of candidate molecules and specific target gene, Sig2Lead ranks candidate molecules by chemical similarity to their ‘concordant’ LINCS analogs that share signature similarity with a knock-down of the target gene. An efficient method for chemical similarity search, optimized for sparse binary fingerprints of chemical moieties, is used to enable fast searches for large libraries of small molecules. A small subset of candidate compounds identified in the first step can be then re-scored by combining signature connectivity with docking simulations (Sig2Lead was benchmarked in conjunction with AutoDock and MTiOpenScreen). For details please see the paper listed below and the user manual.

Please cite for now the biorxiv preprint: https://www.biorxiv.org/content/10.1101/2020.11.25.399238v1
