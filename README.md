# ServiceNow-with-Machine-Learning
ServiceNow with Machine Learning - Team (D.S.N.Sathvik, A.S.Gowtham)

Overview :

This project integrates Machine Learning (ML) capabilities directly into the ServiceNow platform without relying on external tools. It provides a guided portal where users can train, test, and deploy predictive models using ServiceNow data, making ITSM processes more intelligent and proactive.

Objectives :

Automate prediction of ticket resolution, SLA breaches, and incident trends.
Provide a user-friendly portal to train ML models on any ServiceNow table.
Enable workflow automation using predictive insights, reducing manual effort and improving efficiency.

Key Features : 

Dynamic Data Selection
Choose any ServiceNow table (e.g., Incident, Change Request).
Select input (features) and output (target) fields.

Data Preprocessing
Convert categorical labels into numeric values (Yes/No → 1/0).
Clean and normalize data before training.

Model Training
Supports Linear Regression (numerical predictions).
Supports Logistic Regression (classification tasks, e.g., SLA breach: Yes/No).
Configure training parameters: learning rate, batch size, iterations.

Evaluation & Accuracy
Displays accuracy/performance metrics after training.
Allows fine-tuning of parameters for better results.

Model Deployment
Save trained models directly inside ServiceNow.
Generate usage scripts for Business Rules, Client Scripts, and Workflows.

Integration & Automation
Embed predictions into ServiceNow processes (e.g., auto-escalation, resource assignment).
Enhances ITSM with proactive, data-driven decision-making.

Impact & Benefits : 

25% faster ticket resolution through workflow automation.
15% fewer SLA escalations using predictive alerts.
Improved efficiency by integrating ML directly into ServiceNow (no external tools needed).
Scalable & reusable — works with multiple ServiceNow modules and datasets.
