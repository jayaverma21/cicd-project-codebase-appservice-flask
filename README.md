# Flask Azure DevOps Deployment

This repository contains a Flask web application that is deployed to code base azure App Service using an Azure DevOps YAML pipeline.

##  Project Overview

- 🐍 Backend: Flask (Python)
- ☁️ Cloud Platform: Azure App Service
- 🔄 CI/CD: Azure DevOps YAML Pipeline

The project demonstrates how to automate the deployment of a Flask application using a YAML-based pipeline in Azure DevOps.

## 📂 Project Structure
.
├── app.py
├── requirements.txt
├── azure-pipelines.yml
└── README.md


## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/flask-azure-devops-deployment.git
cd flask-azure-devops-deployment
2. Create Virtual Environment
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
3. Install Dependencies
pip install -r requirements.txt
4. Run the Application Locally
python app.py

App will run on:

http://localhost:5000
🔄 CI/CD Pipeline

This project uses an Azure DevOps YAML pipeline (azure-pipelines.yml) to:

Install dependencies

Build the Flask app

Deploy to Azure App Service

☁️ Deployment

The deployment is automated via Azure DevOps pipeline:

Code is pushed to the repository

Pipeline is triggered automatically

Application is deployed to Azure App Service

📌 Requirements

Python 3.x

Azure DevOps account

Azure subscription

📖 Notes

Make sure to configure your Azure service connection in Azure DevOps.

Update the azure-pipelines.yml file with your App Service name and subscription details.

🤝 Contributing

Feel free to fork this repository and submit pull requests.
