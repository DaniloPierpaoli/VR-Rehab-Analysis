# VR-Based Rehabilitation: A Dual-Domain Framework for Stroke and Joint Pain Recovery

**Author**: Danilo Pierpaoli  
**Status**:  In Progress  
**Last updated**: July 2025

---

##  Overview

This project explores the use of **Virtual Reality (VR)** as an emerging tool in physical rehabilitation. VR offers immersive environments that enhance patient **engagement**, **motor learning**, and **recovery tracking**.

We focus on two clinical domains:

-  **Neurological rehab** (stroke recovery)
-  **Musculoskeletal rehab** (joint pain)

Using a mix of **synthetic and open-source datasets**, we develop a dual-domain analytical framework for modeling patient recovery, extracting features from movement signals, and visualizing clinical progress.

---

##  Objectives

- Simulate rehab data for both stroke and joint pain patients
- Apply signal processing (e.g. FFT, SDE) to movement signals
- Enrich synthetic sessions with real motion traces from public datasets
- Build machine learning pipelines to predict recovery outcomes
- Use generative AI to simulate therapist notes and session logs
- Create visual dashboards for monitoring and insight

---

##  Tech Stack

- Python (NumPy, Pandas, Scikit-learn, SciPy)
- Signal processing (FFT, SDE)
- ML pipeline tooling (scikit-learn, XGBoost)
- Generative AI (OpenAI API or transformers)
- Power BI or Streamlit for visualization
- Git & GitHub for version control

---

##  Project Structure (Planned)

```text
VR-Rehab-Analytics/
 ├── data/
 │   ├── synthetic/
 │   ├── real/
 │   └── merged/
 ├── notebooks/
 │   ├── 01_Data_Wrangling/
 │   ├── 02_EDA/
 │   ├── 03_SignalAnalysis/
 │   ├── 04_ML_Models/
 ├── scripts/
 │   ├── simulate_patients.py
 │   ├── simulate_signals.py
 │   ├── fft_analysis.py
 ├── powerbi/
 ├── README.md
 ├── requirements.txt
