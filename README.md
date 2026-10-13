# Hi there, I'm Andrzej 👋

I recently completed an MSc in Data Science at the University of Sheffield (2026), and I have a passion for uncovering insights in healthcare and environmental data. For example, my recent projects combine health records, ECGs and radiology reports to predict outcomes after a pulmonary embolism.

### Research Projects: Prognosis After Pulmonary Embolism 🫁
These three linked projects address one clinical question: who is at risk after a pulmonary embolism (PE), and which data show it. Each repository holds the analysis code, aggregate results and figures. However, no patient-level data are shared, in line with each dataset's data use agreement.

| Part | Project | Question | Main finding |
|---|---|---|---|
| 1 | [pe-multimodal-prognosis-msc](https://github.com/andmahoff/pe-multimodal-prognosis-msc)<br>MSc dissertation | Does late fusion of EHR, ECG, CTPA report and CXR features improve the prediction of 30-day outcomes? | Fusing EHR, ECG and CTPA predicted 30-day death with an AUROC of 0.8715, above the best single modality and the simplified PESI. |
| 2 | [pe-fusion-transfer](https://github.com/andmahoff/pe-fusion-transfer)<br>Fusion across hospitals | Which fusion methods still help when models move between Stanford INSPECT and MIMIC-IV? | Across hospitals, no fusion method was significantly better than the EHR alone on the primary contrast. However, within one hospital a block-stratified forest reached a nested cross-validated AUROC of 0.897 for 30-day death. |
| 3 | [pe-survival-prognosis](https://github.com/andmahoff/pe-survival-prognosis)<br>Time-to-event re-analysis | When is risk concentrated, and how well can death and readmission be predicted up to one year? | In the pre-registered analysis, the ECG's signal for death was concentrated in the first 30 days after discharge. In addition, survival super learners reached AUROCs of 0.867 at diagnosis and 0.925 at discharge for 30-day death. |

Each project re-tested the conclusions of the one before it, so most earlier results were confirmed, while a few were reframed or left open and one did not reproduce. For example, the side project confirmed that fusion helps least when one modality dominates, which the dissertation had first shown by strengthening the EHR modality. However, the side project did not reproduce the dissertation's small transfer cost for CTPA report text. In addition, the survival project separated what is known at diagnosis from what is learned later in the stay, which the earlier models had mixed. The README of each repository lists which results held and which changed, with the numbers behind each one.

### Professional Skills <img width="28" height="28" alt="human_11515564" src="https://github.com/user-attachments/assets/3687db06-b89a-4a85-94ed-a9f3bbccfc55" />
* **Languages:** R (Tidyverse, ggplot2, survival, glmnet), Python (scikit-learn, PyTorch), SQL.
* **Data Science:** Machine Learning (Random Forest, Regression, Survival Analysis, Ensemble Learning), Multimodal Data Fusion, Time-Series Analysis, Data Visualisation.
* **Tools:** Git, RStudio, Positron, Google BigQuery, HPC clusters (Slurm), Microsoft Office.

### Research Interests <img width="28" height="28" alt="pie-chart_14993297" src="https://github.com/user-attachments/assets/ff91ff98-eb09-41bc-93c0-69397f9ba1dd" />
* **Healthcare:** Deeply interested in how data and AI can be used in medicine to improve patient outcomes.

### Coursework Projects
The links to my university projects:

* **[IJC437: Predicting Air Quality in Sheffield Using Weather Data](https://github.com/andmahoff/sheffield_air_pollution_analysis)**
    * *An analysis of meteorological drivers of NO2 pollution in Sheffield using Linear Regression and Random Forest models.*
* **[IJC445: Visualising Air Quality in Sheffield Over Time](https://github.com/andmahoff/sheffield_air_pollution_data_visualisation)**
    * *Visualisation of NO2 pollution patterns in Sheffield according to the time of day, month, and year.*

### Hobbies <img width="28" height="28" alt="mountain_5705805" src="https://github.com/user-attachments/assets/4b6cf044-3710-4209-9b8c-64e0e42ac62c" />
Apart from coding, I love:
* **Sports:** Massive Arsenal fan and regular 6-aside football player. I also enjoy surfing and hiking in the Peaks.
* **Music:** Regular live music goer. I also play the keyboard.
* **Movies:** Big movie fan - regular Letterboxd reviewer and volunteer at my local Film Unit.
