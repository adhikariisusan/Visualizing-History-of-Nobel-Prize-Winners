# Nobel Prize Laureate Analysis (1901 - 2023)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-444444?style=for-the-badge&logo=python&logoColor=white)

An exploratory data analysis project investigating over 120 years of Nobel Prize history to uncover demographic trends, geographic shifts, and repeat winner patterns.

## 📌 Project Objectives

1.  **Demographic Analysis**: Track the ratio of male to female winners over time to quantify the gender gap evolution.
2.  **Geographic Trends**: Identify which countries and organizations have historically dominated specific Nobel categories.
3.  **Laureate Consistency**: Programmatically isolate individuals and organizations who have won the prize more than once.
4.  **Temporal Visualization**: Model the density of awards across decades to find "Scientific Golden Ages."

## 📂 Technical Implementation

* **Dataset**: Derived from the Nobel Prize API (`nobel.csv`), containing detailed metadata for every laureate from 1901 to 2023.
* **Tooling**: 
    * **Pandas/NumPy**: For data manipulation, multi-indexing, and frequency counting.
    * **Seaborn/Matplotlib**: For categorical plotting and visualizing historical distributions.
* **Key Logic**: Utilized `value_counts()` and logical filtering to generate a list of repeat winners, including the International Committee of the Red Cross and Marie Curie.

## 🚀 Key Insights

* **Gender Distribution**: Visualized the significant disparity in awards and identified the specific eras where female representation began to rise.
* **The "Repeaters"**: Identified the elite group of 6 laureates (individuals and organizations) who have achieved the rare feat of multiple Nobel Prizes.
* **Category Density**: Mapped the frequency of awards across the six major categories to see how the "focus" of global recognition has shifted.

## 🛠️ Usage

Open `notebook.ipynb` in any Jupyter environment to run the analysis. The project is structured to walk through data loading, cleaning, visualization, and final conclusion.

---
**Author:** [Your Name]
