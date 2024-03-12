# Deploy HTML App to Azure Web App - Technology Services

This project demonstrates the process of deploying a static HTML application to Azure Web App using GitHub Actions. It encompasses setting up CI/CD pipelines to automate the deployment process, ensuring seamless updates and management of the web application hosted on Azure.

## Technologies Used

- HTML/CSS
- GitHub Actions for CI/CD
- Azure Web App Services
- Azure Cloud Shell and PowerShell for Azure Credentials setup

## Features

- **CI/CD Pipeline**: Automated deployment pipeline using GitHub Actions, enabling continuous integration and deployment to Azure Web App.
- **Azure Web App**: Utilization of Azure Web App services for hosting the static HTML site, showcasing scalability and reliability.
- **Security**: Implementation of Azure credentials and publish profiles to securely deploy the application.

## Getting Started

### Prerequisites

- An Azure account.
- A GitHub account.
- Basic understanding of HTML/CSS and Azure Web Services.

### Setup

1. **Fork this repository**: Start by forking this repository to your GitHub account.

2. **Create an Azure Web App**: Set up your Azure Web App in the Azure Portal, noting down the app name and ensuring that your subscription is active.

3. **Configure GitHub Secrets**: Add your Azure deployment credentials as secrets in your GitHub repository settings. Required secrets include:
   - `AZURE_WEBAPP_PUBLISH_PROFILE`: Your Azure Web App's publish profile.

4. **Customize Workflow (if needed)**: Modify the `.github/workflows/deploy.yml` file to match your Azure Web App configuration and any specific deployment requirements.

### Deployment

The deployment process is automated through GitHub Actions. Any push to the main branch triggers the deployment workflow, which deploys the latest version of the site to Azure Web App.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments

- This project was built as part of learning and demonstrating the use of Azure Web App Services and GitHub Actions for CI/CD.
- Special thanks to the open-source projects and tools that made this project possible.
