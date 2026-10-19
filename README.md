# ISPmu1 TnpB data analysis

Custom code used in Bonuzzi, Conci, Ciciani *et al.*, 2026. Data required to reproduce the analyses is provided in `data`. Sequencing data is publicly available at https://www.ncbi.nlm.nih.gov/sra/PRJNA1533856.

Use `conda create --file environment.yml` to install all dependencies necessary to reproduce the analysis. Then, `conda activate TnpB_data_analysis`.

* `get_conserved_residues.ipynb` was used to align TnpB variants active in *E. coli* and identify conserved amino acid residues.
* `TnpB_tree.ipynb` was used to generate the maximum likelyhood phylogeny of selected TnpB variants.
* `quantify_editing.ipynb` was used to analyze sequencing data to assess the editing efficiency of 6 reference and 25 candidate TnpB variants.
* `ISPmu1_locus.ipynb` was used to predict the boundaries of the IS605 element encoding ISPmu1.
* `domain_annotation.ipynb` was used to generate domain annotations for ISPmu1 by aligning it to ISDra2.
* `ISPmu1_TAM.ipynb` was used to analyze the seqeuncing data for the TAM characterization assay for ISPmu1. 
