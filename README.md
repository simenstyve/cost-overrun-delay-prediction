# Strategic Decision-Support: Predictive Analytics for Resource Stewardship

Strategic Overview
In complex, global organizations like Human Rights Watch, the ability to anticipate project volatility is critical for effective mission delivery. This project implements a Predictive Analytics Framework designed to identify cost overruns and schedule delays before they occur.

By shifting from reactive reporting to proactive risk-signaling, this tool serves as an early-warning system for leadership, ensuring that donor funds and human resources are allocated where they are most impactful.

Key Capabilities
Dual-Target Modeling: Simultaneously predicts Cost Overrun Risk (Classification) and Schedule Delay Magnitude (Regression).
Early-Warning Logic: Specifically engineered to provide insights during the "at-risk" phase of the project lifecycle.
Feature Engineering: Transforms raw operational data into domain-specific indicators of project health.
Human-in-the-Loop Integration: Outputs are designed to be consumed by project managers and directors, not to replace them, ensuring ethical oversight.


Technology Stack
Language: Python
Data Processing: Pandas, NumPy
Machine Learning: Scikit-learn (SVM, Random Forest, Linear Regressors)
Visualization: Matplotlib, Seaborn for stakeholder reporting.
⚖️ Responsible AI & Governance
Consistent with the principles of Responsible AI, this implementation prioritizes:
Explainability: Emphasizes feature importance to show why a project is flagged as high-risk, allowing for targeted intervention rather than blind trust in a score.
Transparency: Full documentation of data cleaning and normalization steps to prevent hidden biases in risk assessment.
Data Privacy: This framework is built to operate on operational metadata, strictly avoiding the use of sensitive individual or personal data.
Actionable Governance: The system identifies "controllable" factors versus "environmental" factors, helping management distinguish between operational inefficiencies and external hurdles.


Repository Structure
notebooks/cost_overrun_fp.ipynb: End-to-end exploratory data analysis (EDA) and model training.
src/preprocessing.py: Modular code for repeatable data cleaning and feature scaling.
src/models.py: Implementations of the classification and regression pipelines.
src/evaluation.py: Metrics tailored to organizational impact (Precision/Recall).


Strategic Use Cases
Portfolio Risk Monitoring: High-level dashboarding for executive directors to see which global initiatives require additional support.
Budget Forecasting: Refining the accuracy of long-term financial planning by adjusting for predicted variance.
Grant & Resource Accountability: Providing evidentiary data to donors on how risks are identified and mitigated through technology.


Limitations & Future Work
Data Quality Dependency: The model is only as strong as the historical reporting data available.
Integration: Future iterations aim to integrate directly with ERP systems (like NetSuite or SAP) via REST APIs for real-time monitoring.


Author: Styve Simen

Target Role: AI Strategy and Solutions Lead

Leveraging data-driven insights to ensure every resource is used effectively in the service of human rights.
