# Azure CMS Application Deployment

## Project Overview
This project deploys a Flask-based CMS application to Microsoft Azure. The application allows users to create posts, edit posts, upload images, and store data using Azure services.

## Azure Services Used
- Azure App Service for hosting the Flask application
- Azure SQL Database for storing users and posts
- Azure Blob Storage for storing uploaded images
- GitHub Actions for deployment

## Deployment Steps
1. Set up the local Flask application and verified it worked locally.
2. Created an Azure SQL Database and initialized the `users` and `posts` tables.
3. Created an Azure App Service and connected it to GitHub Deployment Center.
4. Added required environment variables for SQL and Blob Storage in Azure App Service.
5. Created an Azure Storage Account and an `images` blob container.
6. Uploaded an image through the CMS and verified that it appeared in Blob Storage.
7. Verified the deployed CMS was working on Azure.

## Environment Variables
The following app settings were configured in Azure App Service:
- SQL_SERVER
- SQL_DATABASE
- SQL_USER_NAME
- SQL_PASSWORD
- BLOB_ACCOUNT
- BLOB_CONTAINER
- BLOB_STORAGE_KEY

## Application URL
https://rakshit-cms-app-b5cudkbxe3h4anbw.centralus-01.azurewebsites.net

## Repository
Add your GitHub repository link here after pushing:
https://github.com/YOUR_USERNAME/azure-cms-project

## Screenshots Included
1. Azure Web App Overview
2. Azure SQL Database Overview
3. Blob Storage `images` container with uploaded image
4. CMS application page showing the uploaded image