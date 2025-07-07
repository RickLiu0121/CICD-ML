# CICD-ML

This is my attempt in implementing the CI/CD process for machine learning models, such as Random Forest. The Github workflow actions is key part in automation process.
The CI (Continuous Integratioin) defines the actions following any update to the main branch, such as save the new model parameters and displaying new test validation results in the commit comment section. The CD (Continuous Deployment) uses the Hugging Face CLI tool for updating the model information on the web server.

Reference: 
Step by Step Guide: https://www.datacamp.com/tutorial/ci-cd-for-machine-learning
GitHub Repository: https://github.com/kingabzpro/CICD-for-Machine-Learning
Hugging Face Space: https://huggingface.co/spaces/kingabzpro/Drug-Classification
Dataset: www.kaggle.com/datasets/prathamtripathi/drug-classification
