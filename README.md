 Azure App Service Demo Application (Static Web App)
A static web application deployed on Microsoft Azure using Azure Static Web Apps.  
This project demonstrates hosting, CI/CD automation, and cloud deployment of a modern static website using GitHub and Azure.

 Project Overview
This project is a front-end static web application built using HTML, CSS, and JavaScript, and deployed to Azure using Azure Static Web Apps.
The application is automatically built and deployed whenever changes are pushed to the GitHub repository, showcasing a complete CI/CD workflow using GitHub Actions.

 Live Deployment
The application is hosted on Azure and publicly accessible via Azure Static Web Apps.

Azure-App-Service-Demo-Application/
│
├── assets/ # Static assets (images, icons, etc.)
├── vendor/ # Third-party libraries
├── index.html # Home page
├── browse.html # Browse page
├── details.html # Details page
├── profile.html # Profile page
├── streams.html # Streams page
├── README.md # Project documentation
└── .github/workflows/ # GitHub Actions CI/CD pipeline

 ->Azure Services Used

- Azure Static Web Apps
  - Hosts the static frontend
  - Provides global CDN and HTTPS
- GitHub Actions
  - Automates build and deployment
- Azure Portal
  - Application configuration and monitoring

 ✨ Features

- Responsive static web pages
- Client-side routing using HTML pages
- JavaScript-based interactivity
- Automated deployment via GitHub Actions
- Secure HTTPS hosting on Azure

 Security & Best Practices
- No secrets are stored in the source code
- Deployment credentials are managed securely by Azure
- HTTPS enabled by default via Azure Static Web Apps

 What I Learned
- Deploying static websites using Azure Static Web Apps
- Setting up CI/CD pipelines with GitHub Actions
- Managing cloud-hosted static applications
- Understanding Azure-hosted frontend architectures
- Integrating GitHub with Azure for automated deployments

<img width="1908" height="910" alt="image" src="https://github.com/user-attachments/assets/872e8488-5140-4057-b7cf-08022e7f4eb2" />
