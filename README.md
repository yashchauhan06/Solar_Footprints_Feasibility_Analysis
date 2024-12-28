# Solar Footprints Feasibility Analysis

This project focuses on evaluating the feasibility of potential solar installation sites in California using predictive machine learning models. The primary goal is to support data-driven decisions for renewable energy expansion by classifying sites as feasible or non-feasible based on various technoeconomic criteria.

## Project Overview
The dataset provides insights into infrastructure proximity, land classification, and available acreage for solar installations. Through this analysis, stakeholders can optimize resource allocation, minimize risks, and align projects with California's renewable energy and environmental goals.

## Business Context
- **Challenges Addressed**:
  - Avoiding costly and suboptimal site investments.
  - Supporting strategic planning for solar energy growth.
  - Balancing economic priorities with environmental sustainability.

## Objectives
1. **Classify Sites for Feasibility**: Develop models to determine whether a site is suitable for solar installations.
2. **Optimize Resource Allocation**: Prioritize high-value, cost-effective locations to maximize returns.
3. **Support Strategic Planning**: Align renewable energy projects with California’s goals.
4. **Minimize Risks**: Avoid financial, operational, and environmental pitfalls by identifying non-feasible sites.

## False Positives and False Negatives
- **False Positives (FP)**:
  - Predicting a site as feasible when it is not.
  - **Impact**: Financial losses, inefficiency, environmental risks.
- **False Negatives (FN)**:
  - Predicting a site as non-feasible when it is feasible.
  - **Impact**: Missed opportunities, reduced ROI, slower renewable energy adoption.

**Strategic Balance**:
- Emphasizing low FPs for risk-averse stakeholders.
- Minimizing FNs for rapid renewable energy deployment.
- Hybrid approaches to address both concerns effectively.

## Methodology
1. **Data Preparation**:
   - Feature selection, handling missing values, and scaling.
2. **Model Development**:
   - Logistic Regression, Decision Trees, and Support Vector Machines.
3. **Model Evaluation**:
   - Performance metrics: Confusion Matrix, Precision, Recall, F1 Score, ROC Curve, and AUC.
   - Focus on precision and recall trade-offs to prioritize stakeholder goals.
4. **Optimization**:
   - Grid Search for hyperparameter tuning to enhance model performance.

## Technologies Used
- **Programming**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Tools**:
  - MLflow: For experiment tracking, model registration, and version control.
  - GridSearchCV: For hyperparameter tuning.

## Business Impact
- **Cost Savings**: Avoids suboptimal investments.
- **Strategic Planning**: Facilitates faster renewable energy deployment.
- **Sustainability**: Aligns economic goals with environmental priorities.

## Getting Started
1. Clone this repository.
2. Set up your MLflow credentials:
   - Ensure access to an MLflow tracking server.
   - Configure the tracking URI and credentials.
4. Run the notebook `Solar_Footprints_Feasibility_Analysis.ipynb`:
   - Track model training and evaluation metrics with MLflow.
   - View artifacts registered in the MLflow Model Registry.
5. Check the MLflow dashboard for:
   - Experiment tracking.
   - Model registration, versioning, and deployment readiness.

## Results
The project delivers actionable insights for site feasibility with recommendations to optimize decision-making and align with California's clean energy goals.

