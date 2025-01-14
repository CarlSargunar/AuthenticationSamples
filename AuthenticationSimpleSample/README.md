---
name: .NET MAUI - Authentication Azure AD B2C
description: "This sample demonstrates how to implement authentication using Azure AD B2C (using external platforms)"
page_type: sample
languages:
- csharp
- xaml
products:
- dotnet-maui
- dotnet-core
urlFragment: authentication-B2C
---
<h1 align="center">Simple Azure AD B2C Authentication Sample</h1>

<div align="center">
This sample demonstrates how to implement authentication using Azure AD B2C to login with Microsoft and other external platforms. </br>
This sample currently works on Windows, Android and iOS </br></br>
</div>

## Login Page
<p align="center">
    <img width="450" src=./Screenshots/login.png>
</p>

## Azure Login Page
This page is prompted after clicking the login button
<p align="center">
    <img width="450" src=./Screenshots/login2.png>
</p>

## Setting Page
<p align="center">
    <img width="450" src=./Screenshots/settingsPage.png>
</p>

Before running the app:
- [Create project and deploy the backend](https://docs.microsoft.com/en-us/azure/developer/mobile-apps/azure-mobile-apps/quickstarts/maui/#deploy-the-backend-to-azure)
- [Register the application](https://docs.microsoft.com/en-us/azure/developer/mobile-apps/azure-mobile-apps/quickstarts/maui/#deploy-the-backend-to-azure)
After completing these steps you will be able to retrieve a ClientId from the Azure AD Directory that should be using in the Services/Constants.cs file


For more information about the sample see:
- [Set up Google - Azure AD B2C](https://docs.microsoft.com/azure/active-directory-b2c/identity-provider-github?WT.mc_id=Portal-Microsoft_AAD_B2CAdmin&pivots=b2c-user-flow)
- [Set up Facebook - Azure AD B2C](https://docs.microsoft.com/azure/active-directory-b2c/identity-provider-facebook?WT.mc_id=Portal-Microsoft_AAD_B2CAdmin&pivots=b2c-user-flow)
- [Set up Twitter - Azure AD B2C](https://docs.microsoft.com/azure/app-service/configure-authentication-provider-twitter)
