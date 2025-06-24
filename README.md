# 🌱 Soil Nutrient Gap Prediction for SDG 2 – Zero Hunger

This project uses machine learning to predict Nitrogen (N), Phosphorus (P), and Potassium (K) nutrient gaps in farm soils across Africa.

## 🎯 Goal
Enable smallholder farmers to receive science-backed fertilizer recommendations by applying AI to soil data.

## 🧠 ML Methodology
- **Approach:** Supervised Learning
- **Model:** Random Forest Regressor
- **Targets:** N_gap, P_gap, K_gap
- **Features:** Soil chemical and remote sensing indicators
- **Performance:** MAE = **47.80**

## 📂 Files
- `soil_gap_model.py`: Python model training script
- `SoilGap_Submission.csv`: Final prediction file
- `demo_screenshot.png`: Screenshot of MAE result in Colab

## 🤖 Ethical Reflection
- Promotes sustainability by avoiding fertilizer overuse
- Targets SDG 2 by helping improve yields affordably
- Offers potential for local extension service integration

## ✅ Dataset
- `Train.csv` and `Gap_Train.csv` from Zindi AI4D Africa Soil Challenge

> Built and submitted as part of the Power Learn Project
