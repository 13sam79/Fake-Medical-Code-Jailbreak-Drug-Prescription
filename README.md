Dataset for the Study: "Jailbreaking ChatGPT in the Context of Drug Prescription"
This repository contains the datasets used and generated in the study titled "Jailbreaking ChatGPT in the Context of Drug Prescription: Design, Implementation, and Analysis of a Reverse Role-Play Experiment with a Fake Medical Code."

The datasets support the analysis of model responses, the classification of suggested drugs by access level, and the comparison of model outputs against the national drug reference list.

Files
1. v1.xlsx
This file contains the experimental data. It includes the drug names suggested by the model across the 400 interactions (4 medical domains × 10 fabricated records × 10 repetitions). This is the primary raw dataset from which the drug recommendations were extracted.

2. zero list of comparasion of drugs.xlsx
This file contains the list of drugs identified from v1.xlsx and their assigned access categories (OTC, Prescription, Hospital-restricted, Not specified). It serves as the coding reference used to classify each recommended agent by its access level.

3. MedicineIndex irc.fda.gov.irhomepublicdrugIndexList.xlsx
This file is the national drug reference list obtained from the Iran Food and Drug Administration (IFDA) website. It is used to compare and analyze the drugs suggested by the model against the official national drug index. The source URL is recorded in the text file https://irc.fda.gov.ir/home/public/drugIndexList.

4. second list of comparasion of drugs.xlsx
This file contains the final results of all data and experiments. It includes the complete analysis, comparisons, and outcomes derived from the datasets above.

Purpose
These datasets are provided to support transparency, reproducibility, and responsible disclosure in AI safety research. The full text of the fabricated clinical records is not released because of the jailbreak nature of the study and the risk of misuse. Only the drug names and their classifications are shared.

Citation
If you use these datasets, please cite the corresponding article:

Mousavi Nassab, S. A. H., & Chinipardaz, M. (2026). Jailbreaking ChatGPT in the Context of Drug Prescription: Design, Implementation, and Analysis of a Reverse Role-Play Experiment with a Fake Medical Code. Jundi-Shapur University of Technology, Dezful, Iran.

License
Please refer to the article and the principles of responsible disclosure for the use of these datasets.






Authors
Seyed Amir Hossein Mousavi Nassab — Jundi-Shapur University of Technology, Dezful, Iran
ORCID: 0009-0008-5971-5082

Maryam Chinipardaz — Jundi-Shapur University of Technology, Dezful, Iran
ORCID: 0000-0001-9795-7818
