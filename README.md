# TFBS-explorer

Exploration of Transcription Factor Binding Sites in promoter regions of IFN-stimulated genes

## Scripts

[TFBS_explorer](scripts/TFBS_explorer_pipeline.ipynb)

1. Retrieve the promoter sequence from ensembl using rest api
2. Fetch the Trasncription Factor Binding Site sequence from JASPAR database using pyJASPAR
3. Scan TFBS in the promoter sequences
