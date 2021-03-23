# Web Scrapper By Python 🔎
## Python Version
- Python 3.8.6

## Version 1
- Packages: requests, BeautifulSoup4, CSV
- Scrapping python job information in StackOverflow and Indeed
- Save scrapped information to .csv file

## Version 2
- Framework: Flask
- Packages: requests, BeautifulSoup4, CSV
- Scrapping every jobs in StackOverflow
- Spread in to html page

## Build & Deploy
- Build: Dockerfile & Dockercompose
- Deploy to: Azure Webapps, k8s(AKS)
- Pipeline 1 (Azure Webapps)
```
source push & merge -> github -> trigger -> docker build -> push to dockerhub -> deploy to azure webapps 
```

## CI/CD Pipeline
- Github Actions
- Azure DevOps
