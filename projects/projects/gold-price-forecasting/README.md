# 🪙 Gold Market Intelligence & Predictive Forecasting System

<!-- PROJECT OVERVIEW WITH SOFT LIGHT BLUE-GREY CARD -->
<div style="background-color: #f4f6f9; border-left: 5px solid #d4af37; padding: 20px; border-radius: 8px; margin-bottom: 25px; box-shadow: 0 1px 3px rgba(0,0,0,0.05);">
    <h2 style="color: #b59410; margin-top: 0; font-family: 'Segoe UI', sans-serif; font-weight: 700;">📌 Project Overview</h2>
    <p style="color: #1e293b; font-size: 15px; line-height: 1.6; margin-bottom: 10px;">
        This project develops an enterprise-grade <strong>Gold Market Intelligence & Predictive Forecasting System</strong> engineered to model and predict gold price fluctuations across both global (<span style="color: #2e7d32; font-weight: bold;">USA - USD</span>) and domestic (<span style="color: #e65100; font-weight: bold;">India - INR per 10g</span>) markets.
    </p>
    <p style="color: #1e293b; font-size: 15px; line-height: 1.6;">
        The system is deployed via a single, all-inclusive master analytical notebook designed to programmatically extract multiple time-series data tables from a unified database, run rigorous feature engineering, and deploy multi-model machine learning ensembles to generate forward-looking financial market intelligence.
    </p>
    <div style="margin-top: 15px;">
        <span style="background-color: #d4af37; color: #111; padding: 4px 10px; border-radius: 4px; font-weight: bold; font-size: 12px; margin-right: 8px;">Ensemble ML</span>
        <span style="background-color: #e2e8f0; color: #334155; padding: 4px 10px; border-radius: 4px; font-weight: bold; font-size: 12px; margin-right: 8px;">Time-Series Split</span>
        <span style="background-color: #e2e8f0; color: #334155; padding: 4px 10px; border-radius: 4px; font-weight: bold; font-size: 12px;">Recursive Inference</span>
    </div>
</div>

---

## 🛠️ Core Analytical Workflows

### 1. Data Engineering & Automated Ingestion
* **Unified Sheet Extraction:** Uses a centralized extraction script to auto-parse, unpack, and convert isolated data segments from a single master Excel source file into clean CSV workspaces.
* **Structural Auditing:** Conducts detailed dimension checks, row-vector logging, and field profiling to map the data terrain.
* **Sanitization Pipeline:** Implements sequential data deduplication and drop criteria for missing rolling features to preserve historical time-series alignment.

### 2. Multi-Target Advanced Feature Engineering
* **Localized Currency Translation:** Programmatically transforms global troy-ounce commodity evaluations into domestic consumer weights ($10\text{g}$) via synchronized conversion equations.
* **Multi-Scale Momentum Mapping:** Engineers Exponential Moving Averages ($\text{EMA}_3, \text{EMA}_6, \text{EMA}_{12}$) paired with active Rate of Change ($\text{ROC}$) attributes to capture price acceleration.
* **Volatility & Seasonality Tracking:** Quantifies market risk metrics through rolling standard deviations and preserves yearly patterns via cyclical sine and cosine monthly calendar coordinates.

### 3. Progressive Machine Learning Ensembling
* **Anomalous Scaling:** Deploys robust feature scaling using `RobustScaler` to shield the regressors from macro shocks, extreme outliers, and market spikes.
* **Chronological Validation Split:** Implements a strict time-series data split ($90\%$ Training / $10\%$ Testing) to eradicate data leakage and realistically measure model generalization.
* **Recency-Weighted Optimization:** Applies linear sample weight arrays across the training timeline, training algorithms to prioritize modern market regimes.
* **Blended Prediction Synthesis:** Merges an optimized multi-model machine learning architecture ($40\%\ \text{XGBoost} + 30\%\ \text{LightGBM} + 30\%\ \text{CatBoost}$) to lower structural variance.

### 4. Multi-Step Inference & Trend Correction
* **Recursive Feedback Loops:** Builds a multi-step recursive forecasting sequence where calculated values at prediction month $T$ cycle back as feature inputs to solve month $T+1$.
* **Variance Boundary Adjustments:** Fuses a calculated trend growth modifier based on recent data velocities to prevent signal dampening across a forward-looking 3-month forecast window.

---

## 💻 Technologies & Libraries Used

* **Core Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Feature Engineering & Scales:** Scikit-Learn (`RobustScaler`, Metrics Evaluation)
* **Ensemble Modeling Regressors:** XGBoost, LightGBM, CatBoost
* **Analytical Domains:** Advanced Time-Series Forecasting, Feature Scaling, Multi-Model Ensembling, Recursive Inference, Recursive Attribute Generation, Financial Risk Modeling

---

<!-- EXPECTED OUTCOMES WITH SOFT LIGHT MINT GREEN CARD -->
<div style="background-color: #f0f7f1; border: 1px dashed #4caf50; padding: 20px; border-radius: 8px; margin-top: 25px; margin-bottom: 25px; box-shadow: 0 1px 3px rgba(0,0,0,0.05);">
    <h2 style="color: #2e7d32; margin-top: 0; font-family: 'Segoe UI', sans-serif; font-weight: 700;">🚀 Expected Project Outcome</h2>
    <p style="color: #1e293b; font-size: 15px; line-height: 1.6; margin-bottom: 0;">
        An end-to-end, deployment-ready financial intelligence engine capable of auto-extracting raw structural macroeconomic data, constructing descriptive momentum attributes, evaluating multi-model ensemble validation margins, and exporting actionable, asset-ready 3-month future price predictions (June, July, and August 2026).
    </p>
</div>

---

## 📊 Project Artifacts & Deliverables

* `gold-prediction-model.ipynb` — Interactive master notebook containing all automated spreadsheet extraction logic, advanced macroeconomic feature engineering pipelines, machine learning ensemble model validations, and predictive time-series visualizations.
* `Gold_Industry_Ready_Dataset.xlsx` — The raw, multi-sheet master database hosting the entire structural tracking parameters, macro indicators, and historical exchange rates required to feed the analytics engine.
* **Visual Dashboards:** [Browse Complete Screenshot Directory]([projects/projects/gold-price-forecasting/screenshots](https://github.com/Jahanvi-Rana/jahanvi-analytics-portfolio/tree/main/projects/projects/gold-price-forecasting/screenshots))
* **Dashboard Video Walkthrough:** [Watch Power BI Dashboard Demo on Google Drive 🎥](https://drive.google.com/file/d/152X6GEbXTDm5v7WR89sKmGtMc5DLDdbl/view?usp=sharing)

---

## 💡 Interactive Dashboard Walkthrough Guide
*Since this video demonstration is a silent walkthrough, the following navigation index outlines the exact Business Intelligence configurations, user experiences (UX), and dynamic operations being demonstrated:*

* **🌐 UI/UX & Navigation Bar Validation:** Demonstrating the execution of the interactive navigation menu. This highlights the responsiveness of the navigation bar, verifying that a user can click and route across separate dashboard elements smoothly without system delays.

* **🎛️ Interactive Canvas & Slicer Cross-Filtering:** A functional evaluation of live visual slicers across the sheets. This demonstrates how slicer interactions immediately update, adapt, and recalculate charts simultaneously across the entire layout to ensure real-time analysis.

* **📊 Complete Multi-Sheet Layout Audit:** A sequential review scanning every analytical sheet one by one. This establishes the structural composition, alignment integrity, and final production-ready look of the completed dashboard workspace.
