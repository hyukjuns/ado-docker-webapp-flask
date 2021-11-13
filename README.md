# Flask Framework를 사용한 Web Application 개발과 Azure DevOps를 사용한 CI/CD 배포

## Application Info
## Job Info Scrapping Web Application
### Language & Framework 
- Lang: Python 3.8.6
- Framework: Flask 1.1.2
### Version 1
- Packages: requests, BeautifulSoup4, CSV
- Scrapping python job information in StackOverflow and Indeed
- Save scrapped information to .csv file

### Version 2
- Framework: Flask
- Packages: requests, BeautifulSoup4, CSV
- Scrapping every jobs in StackOverflow
- Spread in to html page
---
## CI/CD Info
### Platform
- Azure DevOps
    - CI/CD: Pipelines (azure-pipelines.yml)
### CI
1. Source Integration in github
2. Build Dockerfile
3. Push Image to Dockerhub
### CD
1. Deploy to Azure Webapp
---
## Server Info
### Platform
- Azure App Service
    - Webapp for Container(Linux)