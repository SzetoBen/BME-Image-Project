# BME-Image-Project
DS4002 Human image emotion classification project

## Group  
**BME –  Eddie Zhang (leader), Ben Szeto, Masato Takedai**  
DS 4002 – 001 – 1pm – November 2025  

---

## Contents of Repository  
- **README.md** – Orientation and instructions for reproducing results  
- **LICENSE.md** – MIT License for reuse of this repository  
- **SCRIPTS/** – Source code for preprocessing and sentiment analysis  
- **DATA/** – Cleaned datasets, plus Data metadata 
- **OUTPUTS/** – Figures, tables, and other analysis results  

---

## Software and Platform  
- **Programming Language:** Python 3.10+  
- **Core Libraries:**  
  - `ultralytics` – used YOLOv11 model for training  
  - `roboflow' - used to download dataset
- **Platform:** Code developed and tested on Windows and MacOS  

---

## Project Folder Map  
 ```
BME-Time-Series-Project

├── DATA
│   ├── METADATA.md
│   ├── Figure_1.png
│   ├── Figure_2.png
├── LICENSE
├── OUTPUTS
│   ├── output graphs and tables
├── README.md
└── SCRIPTS
    ├── ImageProjectTrain.ipynb
```

---

## Instructions for Reproducing Results  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/SzetoBen/BME-Image-Project
2. **Set up Roboflow**
    1) Make an account with Roboflow to be able to download data from it
    2) Create API key for getting data
3. **Train model**
    1) Open ImageProjectTrain.ipynb and replace API key in the first cell
    2) Execute all cells in the file from top to bottom
4. **Analyze Results**
    1) Metrics, visualizations, and saved model outputs are saved into a subfolder

