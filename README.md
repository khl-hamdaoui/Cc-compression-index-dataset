# Cc-compression-index-dataset

This dataset contains compiled geotechnical properties and corresponding compression index (Cc) values from previously published studies. It is intended for reproducibility, model development, and SHAP-based interpretability research in geotechnical engineering.

---

## 📄 File Information

- **Format:** `.xlsx`
- **Number of samples:** 1243

---

## 📥 Input Features (Predictors)

| Variable    | Description                                                    | Unit       |
|-------------|----------------------------------------------------------------|------------|
| **PL (%)**  | Plastic Limit – the water content at which soil begins to behave plastically | Percent (%) |
| **PI (%)**  | Plasticity Index – PI = LL − PL, indicates soil plasticity      | Percent (%) |
| **e0**      | Initial Void Ratio – ratio of voids to solids before compression | Unitless    |
| **w (%)**   | Natural Water Content – water content of the soil as sampled    | Percent (%) |

These variables are commonly used in predicting the compressibility of fine-grained soils.

---

## 🎯 Output Variable (Target)

| Variable | Description                                      | Unit       |
|----------|--------------------------------------------------|------------|
| **Cc**   | Compression Index – indicates compressibility under loading | Unitless |

---

## 📚 Source

The dataset is compiled from previously published literature and standardized for machine learning and SHAP analysis.

---

## 📬 Contact

For any questions or clarification, please contact:

**PhD Student. K. Hamdaoui**  
📧 k.hamdaoui92@univ-chlef.dz
