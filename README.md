# SC-AgeSpePCa
Single-cell and spatial RNA sequencing identify the age-associated divergent microenvironments and progression patterns in prostate cancer

Brief descriptions of scripts:

1.data_processing.R:

The quality control of scRNA-seq matrix.

2.harmony.R

Batch effect removal and clustering based on harmony, and general celltype annotation.

3.Doublet_and_inferCNV.R

Doublets removal through DoubletFinder, and inferCNV-based malignant epithelial cells identification.

4.1.Epi_NMF.R

Extract transcriptional meta-programs of malignant epithelial cells using cNMF. 
Subsequent functional and clinical analyses for malignant epithelial cells, and corresponding validation with publicly available data.

4.2.Myeloid_harmony.R

Clustering, annotation of myeloid cells. 
Functional analyses, clinical analyses of myeloid cells, and corresponding validation with publicly available data.

4.3.Tcell_harmony.R

Clustering, annotation of T cells. 
Functional analyses, clinical analyses of T cells.

4.4.Fibro_harmony.R

Clustering, annotation of mesenchymal cells. 
Functional analyses, clinical analyses of mesenchymal cells, and corresponding validation with publicly available data.

5.1.CellCommunication.R

Inter-cellular communication analyses between malignant epithelial cells, myeloid cells and T cells through CellChat and CellPhoneDB.

5.2.CellCommunication_epi_all.R

Cellular communication analyses dissecting the mechanism of TME cells regulating AR-MP of malignant epithelial cells through NicheNet.

6.ST.R

ST-seq data analyses and the spatial validation for findings of scRAN-seq analyses.

