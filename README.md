[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/group-assignment-2021-group_11_bdo_production/main)

# 27410 - Group assignment - Group 11 - 1,4-Butanediol (BDO) Production

## Project summary (<300 words)

The aim of this project is to assess the production of 1,4 – Butanediol (BDO) through a metabolic engineered *E. coli* strain and use computational methods to optimize the model and enhance the production. In order to achieve optimal production of BDO, two different pathways were introduced separately in the initial model and were later examined. First pathway includes the synthesis of BDO from α-ketoglutarate (α-KG), while in the second one BDO is produced by the central metabolite succinyl-CoA (Suc-D). Opt-Gene and Opt-Knock were implemented in order to optimize the models, but non significant results derived from both analysis. Knock-outs, that were identified through literature research, were manually introduced, but had no substantial impact on growth or production rates. Further than that, both models were analyzed for a variety of substrates, showing promising results for substrates such as ethanol. Co-factor swap analysis revealed that there is no specific substance that could be switched in order to improve the already-optimized overall yield in production for our method. *E. coli* rocks!


## Project overview

- You can find the main report in Report.ipynb notebook
- Folder <b>Pics</b> hosts all the pictures used in the report 
- Folder <b>Analysis</b> hosts all the code used for analysis of our GSM. In more detail: 
  1. ExistingAssess.ipynb: Memote analysis of three existing models (iML1515, iJO1366,iAF1260)
  2. Model.ipynd: Formation of two models using iML1515 and visualization using Escher 
  3. Medium.ipynb: Analysis of different substrates  
  4. PhPP.ipynb: Phenotype phase plane analysis
  5. Knockouts-Optimaziton.ipynb: Knockout of targeted genes and optimization algorithms
  6. FSEOF.ipynb: FSEOF Analysis
  7. Co_Factor_Swap.ipynb: Co-factor swapping 

