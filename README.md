## UCSC Cell Browser Activity

### 1. Assigned Gene and Disease
   
**Name:** Torres, Rica Jane M.  
**Assigned Gene:** HEXA  
**Associated Disease:** Tay-Sachs disease  
**Date:** 09/24/26

### 2. Organ/Tissue Choice and Dataset Information

| **Item** | **Information** |
|---|---|
| **Dataset** | Adult Cortex Meta-Atlas |
| **Organ/Tissue** | Human brain (cortex) |
| **Cell Types** | IT, Oligodendrocyte, VIP, SST, Astrocyte, PVALB, OPC, Microglia, Endothelial, L6 CT, and other cortical cell types |
| **Gene** | HEXA |
| **Reason for Selection** | The brain is relevant to Tay-Sachs disease because the disease affects the nervous system. The Adult Cortex Meta-Atlas allows us to examine gene expression in different human brain cell types. |
| **Dataset URL** | https://cells.ucsc.edu/?ds=adult-ctx-meta-atlas |

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/dd2bb565-b90c-4385-98c6-3ca81c66800d" />

**Figure 1.** Adult Cortex Meta-Atlas in the UCSC Cell Browser showing the human brain cortex dataset and its different cell types and clusters.

### 3. Understanding the Cell Map

| **Item** | **Information** |
|---|---|
| **Visualization Type** | Full UMAP |
| **What the Dots Represent** | Individual cells |
| **What the Clusters Represent** | Groups of cells with similar characteristics or cell types |
| **Cell Labels Observed** | Oligodendrocyte, Astrocyte, Microglia |

### 4. Assigned Gene Expression

| **Part** | **Answer** |
|---|---|
| **a. Assigned gene symbol** | HEXA |
| **b. Dataset used** | Adult Cortex Meta-Atlas |
| **c. Is expression widespread, restricted, or low/undetected** | Low overall and relatively restricted |
| **d. Which cluster(s) appear to contain cells with stronger expression?** | IT, L4 IT, L5 ET |
| **e. Which cluster(s) appear to contain little or no detectable expression?** | Oligodendrocyte, Microglia, Astrocyte, OPC |

<img width="917" height="576" alt="Screenshot 2026-09-24 175649" src="https://github.com/user-attachments/assets/46285143-b67d-4619-8d06-a2fba0d2e0fd" />

**Figure 2.** Cell-type annotation map of the Adult Cortex Meta-Atlas showing the major annotated cell clusters, including IT, Oligodendrocyte, Astrocyte, Microglia, VIP, SST, PVALB, OPC, L6 CT, and other cortical cell populations.

### 5. Cell Types and Clusters

| **Part** | **Answer** |
|---|---|
| **a. Cell type/cluster with the strongest visible expression** | IT |
| **b. Another cell type/cluster with detectable expression** | L4 IT |
| **c. Cell type/cluster with relatively low or undetected expression** | L5/6 IT Car3 |
| **d. Is the expression pattern broad or cell-type restricted?** | Relatively cell-type restricted |
| **e. Biological explanation** | Based on the selected Adult Cortex Meta-Atlas dataset, the HEXA expression appears at different levels across the brain cell clusters. The stronger visible expression in some cortical clusters and lower expression in other clusters suggests that HEXA expression varies among cell types in this dataset. |

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/55faf090-19a0-440e-a60b-29f46d419f4f" />

**Figure 3.** HEXA gene expression map of the Adult Cortex Meta-Atlas showing differences in expression across major annotated cell clusters, including IT, L4 IT, L5 ET, Oligodendrocyte, Astrocyte, Microglia, and other cortical cell populations.

### 6. Expression Plot

| **Part** | **Answer** |
|---|---|
| **a. Selected cell type/cluster** | IT |
| **b. Expression compared with other cell types** | IT shows detectable HEXA expression, with an average expression of 0.16 and about 29% of IT cells showing non-zero expression. |
| **c. What does the plot add beyond the UMAP?** | The expression plot gives a clearer comparison of HEXA expression between different cell types. It shows both the average expression level and the percentage of cells with detectable expression. |

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/35e8bbbd-ea59-4727-b6da-860d93d5b450" />

**Figure 4.** Dot plot showing HEXA gene expression across different cell types in the Adult Cortex Meta-Atlas, with color indicating average expression and dot size representing the percentage of cells with detectable expression.

### 7. Marker Genes

| **Part** | **Answer** |
|---|---|
| **a. Cluster/cell type examined** | IT |
| **b. Marker gene 1** | MLIP |
| **c. Marker gene 2** | SATB2 |
| **d. Marker gene 3** | SV2B |
| **e. Does the assigned gene behave like a cell-type marker in this dataset?** | HEXA does not appear to behave like a specific cell-type marker in this dataset because its expression is not limited to the IT cluster. |

<img width="1366" height="768" alt="Screenshot (163)" src="https://github.com/user-attachments/assets/fe1d2ce4-ce5e-4836-85eb-f5b02093a5b4" />

**Figure 5.** Cluster marker genes for the IT cell type in the Adult Cortex Meta-Atlas, showing MLIP, SATB2, SV2B, and other marker genes.

### 8. Disease Gene vs. Marker Gene

| **Part** | **Answer** |
|---|---|
| **a. Assigned disease gene** | HEXA |
| **b. Marker gene** | MLIP |
| **c. Which gene shows a more cell-type-restricted expression pattern?** | MLIP |
| **d. Which gene appears more broadly expressed?** | HEXA |
| **e. What does this comparison teach you?** | MLIP shows a more cell-type-associated expression pattern in the IT cluster, while HEXA is detected across a broader range of cell types in this dataset. This shows that a cell-type marker gene can have a more restricted expression pattern, while a disease-associated gene can still be biologically important even when it is expressed in multiple cell types. |

### 9. Connection to Genome Browser and ClinVar

**1. On which chromosome is your assigned gene located? Use your previous UCSC Genome Browser activity.**
- HEXA is located on chromosome 15.

**2. What disease-associated variant did you examine previously?**
- The disease-associated variant I examined previously was NM_000520.6(HEXA):c.1274_1277dup (p.Tyr427fs), which is associated with Tay-Sachs disease.

**3. In the current Cell Browser dataset, which cell type(s) express the gene?**
- HEXA expression was detected in several cell types in the Adult Cortex Meta-Atlas, including IT, L4 IT, and L5 ET.

**4. Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease? Explain in 3-5 sentences.**
- Yes, the expression in the human brain makes sense because Tay-Sachs disease affects the nervous system. HEXA is involved in lysosomal function, and problems with HEXA can affect nerve cells. The Cell Browser shows that HEXA is expressed in different brain cell types in this dataset. However, the expression pattern alone does not explain the whole disease.

**5. Can this single Cell Browser dataset prove that the gene causes the disease? Explain why or why not.**
- No. The Cell Browser only shows gene expression in the selected dataset. It cannot prove that HEXA causes Tay-Sachs disease because disease causation requires genetic, clinical, and other biological evidence.

### 10. Reflection

**1. What does the UCSC Cell Browser show that the Genome Browser does not?**

The UCSC Cell Browser shows where the HEXA gene is expressed in different cell types. The Genome Browser mainly shows the gene's location, structure, and variants.

**2. What did you notice about HEXA expression across different cell types?**

I noticed that HEXA expression was different across the cell types in the Adult Cortex Meta-Atlas. Some cell types showed more detectable expression, while others showed little or no detectable expression.

**3. Why should low or undetected expression be interpreted carefully?**

Low or undetected expression does not always mean that the gene is not important. Expression can depend on the tissue, cell type, samples, and methods used in the dataset.

**4. How does combining genomic, variant, and expression information improve your understanding?**

Combining the Genome Browser, ClinVar, and Cell Browser gives a better understanding of HEXA. The Genome Browser shows the gene's location and structure, ClinVar provides information about the disease-associated variant, and the Cell Browser shows where the gene is expressed.

**5. What was the most interesting observation you made in this activity?**

The most interesting observation for me was that HEXA was expressed at different levels across the brain cell types. This helped me understand that a disease-associated gene does not necessarily have to be a specific marker for only one cell type.

