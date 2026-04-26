# Mode of action analysis
## ...via RNA-seq of cell-sorted and drug-treated organoids

In this repo, we document code to analyze transcriptomics data of cancer core organoids subjected to control (medium), DMSO (vehicle) as well as auranofin (AUF) or temozolomide (TMZ) treatment followed by sorting of healthy and glioma cells, whose transcriptomes were then sequenced separately.

In an initial step, raw RNA-seq data were processed using the pipeline documented in https://github.com/MaikTungsten/RNAseq_pipeline. The resulting count data is deposited in ``post_processing_countData/countData``.

We then performed preliminary QC in Python (``post_processing_countData``) following differential expression analysis ``DE_enrichment_analysis_final.ipynb``. 

The Python environment for processing is available (``env_MoA_organoids.yml``), all required R packages for DE analysis are documented in the code.