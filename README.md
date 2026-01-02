# SmokeHealth Analytics
This project analyses patient data to assess the impact of smoking on organ health. The project covers the full analytic workflow—data cleaning with Power Query, building a data model, creating advanced DAX measures, and designing an interactive dashboard with KPIs, charts, and slicers. It demonstrates how to turn clinical data into visual insights for identifying high-risk patient groups and supporting preventive healthcare decisions.

# Dataset
## Patient Health & Smoking Risk Dataset
* **Author:** Isaac Emmanuel
* **Source:** [YouTube Link](https://www.youtube.com/watch?v=OgDq5GfUVrk)
* **About:** This synthetic dataset is designed to analyze the impact of lifestyle factors, particularly smoking, on patient organ health. It contains individual patient records with demographic, behavioral, and clinical indicators, including smoking history, BMI, blood pressure risk, cholesterol, and family history. 

# Objectives
- [x] Analyze the patient cohort by key demographics (Age Group, Gender) and behavioral profiles (Smoking Status).
- [x] Determine the core relationships between smoking metrics (Years_of_Smoking, Cigarettes_Per_Day) and the primary health outcome (Organ_Condition).
- [x] Uncover risk factor trends by quantifying the correlation of additional variables (BMI, BP_Risk, Cholesterol, Alcohol_Consumption) with organ health.
- [x] Identify high-risk patient segments by synthesizing demographic, lifestyle, and clinical data to pinpoint groups most susceptible to organ damage.
- [x] Synthesize actionable insights into an interactive dashboard for data-driven decision-making in preventive healthcare and patient education.

# Dashboard
![SmokeHealth Analysis Dashboard Walkthrough](//dashboard%20items/Smoking%20Risk%20Analysis%20dashboard%20walkthrough.gif)
<table>
  <tr>
    <th>Organ</th>
    <th>Healthy</th>
    <th>Damaged</th>
  </tr>
  <tr>
    <td>Heart</td>
    <td><img src="/dashboard items/Human Body-Healthy slide.png" width="300"/></td>
    <td><img src="/dashboard items/Human Heart-Damaged slide.png" width="300"/></td>
  </tr>
  <tr>
    <td>Body</td>
    <td><img src="/dashboard items/Human Body-Healthy slide.png" width="300"/></td>
    <td><img src="/dashboard items/Human Body-Damaged slide.png" width="300"/></td>
  </tr>
  <tr>
    <td>Kidney</td>
    <td><img src="/dashboard items/Human Kidney-Healthy slide.png" width="300"/></td>
    <td><img src="/dashboard items/Human Kidney-Damaged slide.png" width="300"/></td>
  </tr>
  <tr>
    <td>Liver</td>
    <td><img src="/dashboard items/Human Liver-Healthy slide.png" width="300"/></td>
    <td><img src="/dashboard items/Human Liver-Damaged slide.png" width="300"/></td>
  </tr>
  <tr>
    <td>Lungs</td>
    <td><img src="/dashboard items/Human Lungs-Healthy slide.png" width="300"/></td>
    <td><img src="/dashboard items/Human Lungs-Damaged slide.png" width="300"/></td>
  </tr>
</table>

# Key Findings
### 1. Dominant Risk Factor Identification
- Smoking (both current and former status) is the most significant behavioral factor correlated with organ damage, especially for the Lungs and Heart.
- The impact is systemic. While lung damage is expected, the data shows the Liver (37.7% damaged) and Kidney (37.0%) are actually the most affected organs, underscoring that smoking causes whole-body harm beyond the respiratory system.
### 2. The Role of Cumulative Exposure
- Organ damage is not just about current status but cumulative lifetime exposure. 
- The "Avg Years of Smoking" and "Cigarettes Per Day" metrics consistently rise with age in damaged organ groups, showing a dose-response relationship.
- This intensification is behavioral. There is a strong positive correlation (0.73) between years smoked and daily intake, meaning long-term smokers tend to increase their habit, compounding risk instead of plateauing.
### 3. Demographic Disparities
- Male patients show a higher prevalence of current and former smoking status across damaged organ analyses, indicating a gender disparity in high-risk smoking behavior within this dataset.
### 4. A Population-Wide Health Crisis, Not a Niche Issue
- Over 54% of the patient population has a history of smoking (Current + Former). This means smoking-related risks are a majority concern, affecting core population health metrics rather than a small, isolated group.
### 5. Damage is Progressive and Age-Amplified
- Health damage from smoking is not static. Older age groups demonstrate the culmination of this progression, with higher smoking duration, higher daily intake, and greater metabolic risk. This creates a clear trajectory where the health consequences of smoking accumulate decisively over decades.

# Technologies
* Excel
* Microsoft Power BI

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](/raw%20data/) within this repo.    
