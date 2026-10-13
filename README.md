# Andrzej Machowski

MSc Data Science, University of Sheffield (2026). I work on clinical prediction from multimodal hospital data: structured health records (EHR), 12-lead ECGs and radiology report text.

## Prognosis after acute pulmonary embolism

Three linked projects on the same clinical question: who is at risk after a pulmonary embolism (PE), and which data show it. Each repository holds the analysis code, the aggregate results and the figures. No patient-level data are shared.

| Part | Project | Question | Main finding |
|---|---|---|---|
| 1 | [pe-multimodal-prognosis-msc](https://github.com/andmahoff/pe-multimodal-prognosis-msc)<br>MSc dissertation | Does late fusion of EHR, ECG, CTPA report and CXR features improve the prediction of 30-day outcomes? | Fusing EHR, ECG and CTPA predicted 30-day death with an AUROC of 0.8715, above the best single modality and the simplified PESI. |
| 2 | [pe-fusion-transfer](https://github.com/andmahoff/pe-fusion-transfer)<br>Fusion across hospitals | Which fusion methods still help when models move between Stanford INSPECT and MIMIC-IV? | Across hospitals, no fusion method was significantly better than the EHR alone on the primary contrast. Within one hospital, a block-stratified forest reached a nested cross-validated AUROC of 0.897 for 30-day death. |
| 3 | [pe-survival-prognosis](https://github.com/andmahoff/pe-survival-prognosis)<br>Time-to-event re-analysis | When is risk concentrated, and how well can death and readmission be predicted up to one year? | Pre-registered: the ECG's signal for death was concentrated in the first 30 days after discharge. Survival super learners reached AUROCs of 0.867 at diagnosis and 0.925 at discharge for 30-day death. |

Data: MIMIC-IV with MIMIC-IV-ECG, MIMIC-IV-ED, MIMIC-IV-Note and MIMIC-CXR (PhysioNet), PTB-XL, and INSPECT (Stanford AIMI), each used under its own licence or data use agreement.

Tools: Python (scikit-learn, PyTorch), R (survival, glmnet, randomForestSRC, riskRegression), SQL on Google BigQuery, and Slurm jobs on a university HPC cluster.
