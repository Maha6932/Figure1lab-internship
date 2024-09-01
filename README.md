# Figure One Lab-internship
# Exploring the Potential Application of FDA-Approved Antibody Therapies Trastuzumab and Bevacizumab in Additional Cancers
## The KSQ: Using available scRNA-seq data from cancer cell lines, how would you explore using the following FDA-approved antibody therapies in additional cancers?
## Praphrased KSQ: Given the available single-cell RNA sequencing (scRNA-seq) data from various cancer cell lines, how would I investigate the potential application of the following FDA-approved antibody therapies in treating other types of cancers? 

First, I will start by explaining a few important terms:

1. Cancer cell lines are in-vitro model systems derived from patient cancer cells, used for understanding the mechanisms of specific cancers, conducting research, and aiding in drug discovery. These cell lines are essential in cancer research, allowing scientists to study cancer behavior, test new treatments, and explore potential therapeutic targets in a controlled laboratory environment.
2. scRNA stands for single-cell RNA sequencing, it is used to analyze the gene expression of individual cells. This sequencing allows for the study of gene expression profiles of individual cells as opposed to bulk sequencing which gives an average profile of all the cells in the sample. This technique is useful for studying cellular diversity within a tissue, understanding the roles of different cell types, and identifying rare cell populations that might be missed in bulk RNA sequencing.
The significance of scRNA-seq in understanding cancer cell lines:
- Tumor Heterogeneity: Reveals diverse gene expression profiles within cancer cell populations, aiding in understanding tumor progression and drug resistance.
- Rare Cell Populations: Identifies rare cells, such as cancer stem cells, that contribute to tumor initiation and therapy resistance.
- Drug Resistance: Uncovers resistant subclones and adaptive responses to treatments, guiding more effective therapeutic strategies.
- Pathway Analysis: Discovers key signaling pathways and potential therapeutic targets for personalized medicine.
- Microenvironment Interactions: Studies interactions between cancer cells and the tumor microenvironment, providing insights into tumor biology.
- Metastasis: Tracks gene expression signatures linked to metastatic potential and cancer progression.
3. Antibody therapy refers to using antibodies to directly kill target cells, block harmful interactions, or mark cells for destruction by the immune system.
  
## Understanding HER2 and VEGF
#### HER2 (Human epidermal growth factor receptor 2)
- HER2 is a protein that is involved in the growth, division, and repair of cells. It is a member of the epidermal growth factor receptor (EGFR) family and is encoded by the ERBB2 gene. HER2 is primarily known for its role in breast cancer, where it is overexpressed in approximately 20-30% of cases.
- HER2-positive breast cancers tend to be more aggressive and have a higher likelihood of recurrence.
- However, targeted therapies, such as Trastuzumab (Herceptin) and Pertuzumab have been developed specifically to inhibit the HER2 protein, improving the prognosis for patients with HER2-positive cancers.

#### VEGF (Vascular endothelial growth factor)
- VEGF is a protein that plays a critical role in the process of angiogenesis, which is the formation of blood vessels. VEGF stimulates the growth of blood vessels by promoting the proliferation and migration of endothelial cells, which line the interior surface of the blood vessel.
- VEGF is particularly important in normal physiological processes like wound healing and the formation of the vascular system during embryonic development, however, it also plays a role in pathological conditions such as cancer.
- Tumors can secrete VEGF to promote the growth of new blood vessels that supply tumors with oxygen and nutrients, facilitating tumor growth and metastasis.
- VEGF-A has been implicated with poor prognosis in breast cancer. Numerous studies show a decreased overall survival and disease-free survival in those tumors overexpressing VEGF. The overexpression of VEGF-A may be an early step in the metastasis process, a step involved in the "angiogenic" switch.
- Because of its role in cancer, VEGF is a target for anti-angiogenic therapies. Drugs like bevacizumab are designed to inhibit VEGF activity, thereby preventing the growth of blood vessels that tumors need to grow and spread.

## Understanding the mechanism of action of the given two antibodies: Trastuzumab and Bevacizumab

#### Trastuzumab's Mechanism of Action:

Targeting HER2: Trastuzumab is a monoclonal antibody designed to target the HER2 protein specifically. It works by binding to HER2, which triggers an immune response against the cancer cells. This binding also leads to the internalization and recycling of HER2, reducing its presence on the cell surface.

Impact on Cell Cycle: Trastuzumab may increase the levels of cell cycle inhibitors like p21Waf1 and p27Kip1, which help slow down or stop cell division.

#### Trastuzumab's Effects on HER2 Signaling:

Binding to HER2: Trastuzumab binds to a specific part (domain IV) of the HER2 receptor on the cell surface. This binding can reverse the cancerous behavior of cells that overexpress HER2.

Cell Cycle Arrest: Trastuzumab causes cancer cells to stop dividing by arresting them in the G1 phase of the cell cycle, reducing their proliferation.

Inhibition of AKT Activation: Trastuzumab downregulates the activation of AKT, a protein involved in promoting cell survival and growth.

Inhibition of Angiogenesis: Trastuzumab also suppresses the formation of new blood vessels that feed tumors by affecting various factors involved in angiogenesis.

#### Immune-Mediated Effects:

Antibody-Dependent Cell-Mediated Cytotoxicity (ADCC): Trastuzumab can recruit immune cells to attack and kill the cancer cells it binds to, through a process known as ADCC.
Trastuzumab and Resistance:

#### Mechanism of Action of Bevacizumab

Targeting VEGF-A:
VEGF-A is a protein that plays a critical role in angiogenesis, which is the process of forming new blood vessels. This is essential for normal growth and development but is also exploited by tumors to ensure they have an adequate blood supply to grow and spread (metastasize).
Bevacizumab is designed to specifically bind to VEGF-A, preventing it from interacting with its receptors on the surface of endothelial cells (the cells that line blood vessels).

Inhibition of Angiogenesis:
By binding to VEGF-A, bevacizumab blocks the signal that would normally stimulate endothelial cells to form new blood vessels. Without the formation of new blood vessels, tumors are starved of the necessary nutrients and oxygen needed for growth.
This inhibition of angiogenesis not only restricts tumor growth but can also prevent the spread of cancer to other parts of the body.

Tumor Growth and Metastasis Suppression:
Tumors rely heavily on the formation of new blood vessels to support their growth. By cutting off the blood supply through the inhibition of VEGF-A, bevacizumab can reduce tumor size and limit metastasis.
Additionally, bevacizumab can enhance the effectiveness of other cancer treatments (like chemotherapy or radiation) by normalizing the abnormal blood vessels in tumors, improving the delivery of these therapies to the tumor cells.

Impact on Existing Blood Vessels:
Bevacizumab also affects existing blood vessels within tumors, making them more stable and less leaky. This can reduce the pressure inside tumors (interstitial pressure), improving the delivery of chemotherapeutic drugs.

#### With this literature review, we have understood the mechanism of action of both drugs so now, we can look for other cancers that share similar pathways or express the same target antigens that the antibody therapy is designed to act upon.

## Questions and Interesting Things noticed
1. While doing my literature search, I found that many patients who took Trastuzumab developed resistance to the drug later, so how do we tackle this drawback with this drug?
2.  One observation that I would like to put down is that: Both drugs contribute to inhibiting angiogenesis, thereby starving the tumor of its blood supply and nutrients. Bevacizumab directly targets the angiogenesis process through VEGF-A, whereas trastuzumab primarily targets the HER2 receptor, with angiogenesis inhibition as a secondary effect.
 
## References
1. https://www.mdpi.com/2072-6694/11/8/1098
2. https://en.wikipedia.org/wiki/Single-cell_sequencing
3. https://en.wikipedia.org/wiki/Monoclonal_antibody_therapy
4. https://en.wikipedia.org/wiki/HER2
5. https://en.wikipedia.org/wiki/Vascular_endothelial_growth_factor
6. https://www.sciencedirect.com/science/article/pii/S1044579X22000670
8. https://en.wikipedia.org/wiki/Trastuzumab
9. https://www.cancer.gov/about-cancer/treatment/drugs/bevacizumab
10. https://en.wikipedia.org/wiki/Bevacizumab

## Additional Information
- Monoclonal antibody: Engineered antibody that targets specific antigens in cancer cells/pathogens. eg: Trastuzumab for HER2-positive breast cancer.
- Bispecific Antibodies: Designed to bind to two different antigens simultaneously, enhancing targeting and immune response. Example: Blinatumomab, used for certain leukemias.
- Conjugated Antibodies: Antibodies linked to a drug or toxin that delivers a therapeutic agent directly to the target cells. Example: Adcetris (brentuximab vedotin) for lymphoma.
- Checkpoint Inhibitors: Antibodies that block proteins on immune cells or cancer cells that inhibit the immune response. Example: Pembrolizumab (Keytruda) for various cancers.
- Antibody-Drug Conjugates (ADCs): Combine antibodies with cytotoxic drugs to deliver the drug directly to cancer cells. Example: Kadcyla (trastuzumab emtansine) for HER2-positive breast cancer.

#### HER2
- Receptor tyrosine-protein kinase erbB-2 is a protein that normally resides in the membranes of cells and is encoded by the ERBB2 gene. ERBB is abbreviated from erythroblastic oncogene B, a gene originally isolated from the avian genome. The human protein is also frequently referred to as HER2 (human epidermal growth factor receptor 2) or CD340 (cluster of differentiation 340).
- The ErbB family consists of four individual plasma membrane-bound receptor tyrosine kinases. One of which is erbB-2, and the other members are erbB-1, erbB-3 (neuregulin-binding; lacks kinase domain), and erbB-4. All four contain an extracellular ligand binding domain, a transmembrane domain, and an intracellular domain that can interact with a multitude of signaling molecules and exhibit both ligand-dependent and ligand-independent activity. Notably, no ligands for HER2 have yet been identified. HER2 can heterodimerize with any of the other three receptors and is considered to be the preferred dimerization partner of the other ErbB receptors. Dimerization results in the autophosphorylation of tyrosine residues within the cytoplasmic domain of the receptors and initiates a variety of signaling pathways.
#### Signal transduction
Signaling pathways activated by HER2 include:
- mitogen-activated protein kinase (MAPK)
- phosphoinositide 3-kinase (PI3K/Akt)
- phospholipase C γ
- protein kinase C (PKC)
- Signal transducer and activator of transcription (STAT)
  
In summary, signaling through the ErbB family of receptors promotes cell proliferation and opposes apoptosis, and therefore must be tightly regulated to prevent uncontrolled cell growth from occurring.

  #### TRASTUZUMAB
- Trastuzumab, sold under the brand name Herceptin among others, is a monoclonal antibody used to treat breast cancer and stomach cancer. It is specifically used for cancer that is HER2 receptor-positive. It may be used by itself or together with other chemotherapy medication. Trastuzumab is given by slow injection into a vein and injection just under the skin.
- Efficacy: Studies have shown that trastuzumab-containing therapies improve survival outcomes. The hazard ratios (HR) indicate how much the treatment reduces the risk of death or disease progression:
          Overall Survival (OS): HR = 0.82, meaning an 18% reduction in the risk of death compared to the control group.
          Progression-Free Survival (PFS): HR = 0.61, meaning a 39% reduction in the risk of the disease worsening.
- Improved Survival: Trastuzumab-containing treatments significantly improve survival:
          Overall Survival: HR = 0.66, meaning a 34% reduction in the risk of death.
          Disease-Free Survival: HR = 0.60, meaning a 40% reduction in the risk of cancer recurrence.
- Cardiac Risks: There is an increased risk of heart-related side effects:
          Heart Failure: The risk is more than five times higher than in patients not receiving trastuzumab (RR = 5.11).
          Decline in Heart Function: A nearly doubled risk of reduced left ventricular ejection fraction (RR = 1.83).
- Shorter vs. Longer Treatment: Shorter treatment regimens of trastuzumab were found to be as effective as longer ones but caused less heart toxicity.

- Impact on Survival in Late-Stage Cancer:
          Metastatic Breast Cancer: Trastuzumab has been shown to extend the survival of patients with advanced HER2-positive breast cancer, from 20.3 months to 25.1 months.
          Early-Stage Cancer Benefits: In early-stage HER2-positive breast cancer, trastuzumab reduces the chance of the cancer returning after surgery. Over three years:
          Reduction in Recurrence: The risk of cancer coming back was reduced by 9.5%.
          Reduction in Death Risk: The risk of death was reduced by 3%.
- Cardiac Toxicity: While trastuzumab increases the risk of serious heart problems by 2.1%, these issues may be resolved if treatment is discontinued.
- Combination with Chemotherapy:
          Increased Survival and Response: When combined with chemotherapy, trastuzumab improves both the survival rate and the effectiveness of the treatment compared to using 
          trastuzumab alone.
- Tumor Testing (erbB2 Status):
          Eligibility for Treatment: Tumors can be tested for erbB2 (also known as HER2) status. If a tumor overexpresses HER2 and the patient does not have significant heart disease, 
          they can be treated with trastuzumab.

  #### HER2 Pathway and Cancer:
Normal Function: In healthy cells, the HER2 pathway helps regulate normal cell growth and division. However, when HER2 is overexpressed, it causes cells to grow and divide uncontrollably, leading to cancer.

HER Family Receptors: The HER family includes four receptors—HER1 (EGFR), HER2, HER3, and HER4. When certain molecules (ligands) bind to these receptors, they activate pathways that promote cell growth and survival, like the MAP kinase pathway and the PI3 kinase/AKT pathway.
Overexpression of HER2 in Cancer:

Overexpression: In some cancer cells, the HER2 protein can be expressed up to 100 times more than in normal cells, driving rapid tumor growth.
Dimerization and Signaling: HER2 receptors on the cell surface can pair up (dimerize) with other HER receptors, leading to stronger and longer-lasting signals that promote cancer cell growth and blood vessel formation (angiogenesis).

- Bevacizumab, also known by its brand name Avastin, is a monoclonal antibody that targets and inhibits vascular endothelial growth factor A (VEGF-A). VEGF-A is a key protein responsible for promoting the growth of new blood vessels (angiogenesis). Bevacizumab is used in the treatment of various cancers, including colorectal cancer, lung cancer, glioblastoma, renal cell carcinoma, and certain types of ovarian and cervical cancers. It is often used in combination with other chemotherapeutic agents.



# WEEK 2 MEMO - Read the Paper
#### 1. How did the authors handle the potential caveat of co-culturing cell lines before profiling by scRNA-seq? Why do you think that caveat was or was not adequately addressed?
The authors handled the potential caveat of co-culturing cell lines before profiling by single-cell RNA sequencing (scRNA-seq) by:
- First using separate and Consistent Pools; The study involved profiling cells from different cell lines pooled together. However, these cell lines were chosen based on similar proliferation rates. They were derived from diverse lineages, reducing the likelihood of significant inter-line competition or cross-interaction affecting gene expression patterns.
- Second, Control Experiments with and without Co-culture; To directly assess the impact of co-culturing, the authors performed control experiments in which six cell lines were profiled with and without being co-cultured for three days. These experiments showed that co-culturing had only a modest effect on the average gene expression of each cell line. More importantly, the patterns of heterogeneity within each cell line remained highly consistent regardless of co-culturing.
- Third, Genetic and Expression-Based Assignment of Cells; To ensure accurate cell line identification, the authors used gene expression profiles and single-nucleotide polymorphisms (SNPs) detected in the scRNA-seq reads. This dual approach allowed them to confidently assign cells to their respective cell lines and exclude those with inconsistent assignments, primarily due to low data quality.
- Fourth, Comparative Analysis Across Pools; The study found that patterns of heterogeneity were as similar between cell lines from the same co-cultured pool as they were between cell lines from different pools. This finding suggests that the co-culture environment did not introduce significant batch effects that could alter the inherent heterogeneity patterns of the individual cell lines.

#### Whether the Caveat Was Adequately Addressed?
The authors did handle the caveat adequately, the combination of control experiments, rigorous cell line assignment methods, and comparative analyses indicates that the authors took significant steps to address the caveat of co-culturing. By demonstrating that the heterogeneity patterns were consistent with and without co-culturing and by confirming cell identity through SNPs and gene expression, the authors minimized the potential impact of co-culture on their findings. 
Though they have handled it properly, there are a few limitations, The modest effect observed on average gene expression due to co-culturing suggests that subtle changes might still occur, potentially influencing low-abundance transcripts or specific stress-response pathways. Additionally, even with the control experiments, co-culture conditions might introduce interactions that are challenging to fully replicate or control for, given the complexity of cell signaling and microenvironmental factors.
        
#### 2. The authors identified discrete subpopulations of cells within a subset of individual cell lines (Fig. 2A-B). What might be the reason why some cell lines have these discrete subpopulations while others do not?
The presence or absence of discrete subpopulations in cell lines is likely influenced by a combination of genetic, epigenetic, and environmental factors. Cell lines that exhibit more intrinsic genetic diversity, greater cellular plasticity, or have been subject to specific selective pressures (either during tumor development or in culture) are more likely to harbor distinct subpopulations. In contrast, cell lines that are more genetically or epigenetically uniform or have less capacity for differentiation and adaptation may not exhibit such heterogeneity. 

#### 3. What are Recurrent Heterogeneous Programs (RHPs) and how were they defined?
Recurrent Heterogeneous Programs (RHPs) are gene expression patterns or transcriptional programs that are consistently observed across multiple cancer cell lines and tumor types, indicating their fundamental role in cancer biology. RHPs represent cellular states that vary within a population of cancer cells, contributing to intra-tumor heterogeneity (ITH). These programs are involved in key biological processes, such as proliferation, stress responses, epithelial-mesenchymal transition (EMT), immune response, and senescence, which are crucial for cancer development, metastasis, and response to therapy. RHPs can be thought of as sets of genes that are co-expressed and exhibit variability in their expression levels within a population of cells, suggesting that different subpopulations of cells within the same tumor or cell line might activate different programs at different times. This variability allows the tumor to adapt to various microenvironmental conditions and therapeutic pressures, thus playing a role in drug resistance and disease progression.

They were identified through single-cell RNA sequencing and computational analysis using methods like non-negative matrix factorization (NMF), clustering, and cross-sample comparison, mainly it's the NMF which is a computational technique, to decompose the gene expression matrix into a set of underlying factors, or programs. NMF identifies basis genes that are consistently co-expressed and separates the data into modules that represent different transcriptional programs. The factors derived from NMF were then analyzed to identify those that were recurrent, meaning they appeared consistently across multiple cell lines.

#### 4. How do the identified RHPs relate to in vivo programs of heterogeneity in tumors, and what evidence supports this relationship?
The identified RHPs reflect in vivo programs of heterogeneity in tumors by capturing critical biological processes and states observed in actual tumor samples. The authors compared the gene expression profiles of the RHPs identified from cell lines to those from actual tumor samples using bulk RNA sequencing and single-cell RNA sequencing data. They found that several RHPs almost 7 out of 10 in cell lines were highly similar to heterogeneity programs observed in vivo. 

For example:
The EpiSen (epithelial senescence-associated) program (RHP 7) identified in cell lines resembled senescence programs found in keratinocytes and lung bronchial cells and was also observed in head and neck squamous cell carcinoma (HNSCC) tumors. This similarity was supported by consistent expression of senescence-associated genes and markers, indicating a shared biological function between cell lines and tumors.
Also, the computational method (NMF) used to identify RHPs was consistent across different cell lines and tumor types, suggesting that these programs are not artifacts of cell line culture conditions but represent real, recurrent patterns of gene expression found in human tumors.
        
#### 5. Where can you download the scRNA-seq data as shown in Figure 1B?
The data is available at GEO: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE157220







