# Project map

| Area | Primary notebook | Role |
|---|---|---|
| Final pricing | `01_Final_Product/notebooks/Buy_Fee_Model_V14_Range_Based_Pricing_Decision_Tool.ipynb` | Empirical ranges and evidence hierarchy |
| Risk decision | `01_Final_Product/notebooks/Buy_Fee_Model_V13_Risk_Based_Decision_Model (1).ipynb` | Risk flags and pilot-review evidence |
| Data preparation | `02_Data_Preparation/notebooks/Buy_Fee_Model_Dataset_Builder_v6_1.ipynb` | Weekly panel and fee events |
| Matched controls | `03_Causal_Analysis/notebooks/Buy_Fee_Model_V8_2_Low_Memory_DiD.ipynb` | Historical comparison estimates |
| Response model | `04_Response_Models/notebooks/Buy_Fee_Model_V11_Segment_Response_Models.ipynb` | Ridge RPU/conversion/volume models |
| Buyer analysis | `05_Buyer_Analysis/notebooks/` | Buyer diagnostics |
| Diagnostics | `06_Model_Validation/` | Prior quality checks |
| Historical approaches | `07_Research_Archive/` | Retained research |

The directory structure expresses **conceptual order**, not a verified executable workflow. Update hard-coded `DATA_FOLDER` references and output filenames before rerunning.

Key outputs: `01_Final_Product/outputs/01_V14_PRICING_DECISION_TABLE.csv`, `04_V14_PRICING_REVIEW_TABLE.csv`, `06_V14_EXECUTIVE_SUMMARY.csv`, `05_V14_MODEL_LIMITATIONS.csv`.

All original Git blob SHAs are retained and recorded in the manifest.
