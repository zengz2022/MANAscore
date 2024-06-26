# A minimal gene set characterizes multiple classes of tumor-specific TIL among different cancer types
* 00.integration.R Integration CD8 T cells from NSCLC and melanoma  
* 01.MANAscore.data.prepare.R   
* 02.ROC.curves.R ROC curves generated for different models including published signatures (NeoTCR8 and CXCL13) on test and validation data   
* 03.cutoff.R Patient specific cutoffs for defining MANAscorehi T cells and pTRC   
* 04.signature.comparison.pTRC.vs.non-pTRC.R Signatures including checkpoint, cytotoxicity, TCR signaling, TRM and clonal size were compared between pTRC and non-pTRC   
* 05.signature.comparison.pTRC.R.vs.NR.R Signatures including checkpoint, cytotoxicity, TCR signaling, TRM and clonal size were compared between pTRC in responder and non-responder   
* 06.pseudobulk.dge.analysis.R DGE anlyses between pTRC and non-pTRC, pTRC in R and NR   
* 07.tissue.compartment.comparison.R Tissue compartment comparison based on MANAscore   
* 08.MANAscore.on.Oral_cancer.R   
* 09.MANAscore.on.metastatic_cancer.R   
* 10.MANAscore.on.MCPyV_pos_MCC.R   
* combined_model_me.py Model construction, and the score prediction on unseen data
