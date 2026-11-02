# Buy Fee Model — Organized Project

**Status:** Research / decision support. Not an approved automatic pricing engine.

This branch reorganizes the existing project without changing notebook contents or historical data. The original `main` branch is unchanged.

## Start here
1. **01_Final_Product/** — Latest V14 range-based pricing review and V13 risk-based decision outputs.
2. **02_Data_Preparation/** — Current V6.1 dataset builder and source audits.
3. **03_Causal_Analysis/** — V8.2 matched-control DiD workflow and V7 causal-readiness work.
4. **04_Response_Models/** — V11 segment response models, validation, and predictions.
5. **05_Buyer_Analysis/** — V12 buyer behavior experiments and their outputs.
6. **06_Model_Validation/** — Diagnostics and a planned 2026 out-of-time backtest.
7. **07_Research_Archive/** — Superseded notebooks and older outputs.
8. **08_Documentation/** — Project map, migration manifest, and limitations.

## Recommended logical workflow
V6.1 dataset builder → V8.2 matched-control DiD → V11 response models → V13 risk decisions → V14 range-based pricing tool.

**Important:** Existing notebooks contain absolute local Windows paths and refer to original output folder names. Reorganizing files does NOT make them runnable from their new locations without updating paths and checking the upstream dependencies. Existing intermediate files are retained. Do not run notebooks blindly or overwrite historical outputs.

## Historical 2026 backtest
Create a distinct out-of-time pipeline: train with only outcome-complete events before 2026, score 2026 events, then evaluate only when the full post-event observation window is available. The prior backtest package is not committed here.

See [Project map](08_Documentation/PROJECT_MAP.md), [migration manifest](08_Documentation/MIGRATION_MANIFEST.csv), and [limitations](08_Documentation/LIMITATIONS.md).
