---
name: .NET MAUI - MIAUI
description: "This sample demonstrates how to implement authentication in a .NET MAUI to-do app"
page_type: sample
languages:
- csharp
- xaml
products:
- dotnet-maui
- dotnet-core
urlFragment: authentication-MIAUI
---

# MIAUI

This sample demonstrates how to implement authentication using Azure AD B2C in a .NET MAUI to-do app.

## Login Page
<p align="center">
    <img width="450" src=./Screenshots/login.png>
    <img width="450" src=./Screenshots/login2.png>
</p>

## Tasks Page
<p align="center">
    <img width="450" scr=./Screenshots/tasks.png>
</p>

## Details Page
<p align="center">
    <img width="450" src=.Screenshots/tasks.png>
</p>

Before using the app:
- [Create project and deploy the backend](https://docs.microsoft.com/en-us/azure/developer/mobile-apps/azure-mobile-apps/quickstarts/maui/#deploy-the-backend-to-azure)
- [Register the application](https://docs.microsoft.com/en-us/azure/developer/mobile-apps/azure-mobile-apps/quickstarts/maui/#deploy-the-backend-to-azure)
After completing these steps you will be able to retrieve a ClientId from the Azure AD Directory that should be using in the Services/Constants.cs file

For more information about the sample see:
- [Store data locally with SQLite](https://docs.microsoft.com/en-us/learn/modules/store-local-data/3-store-data-locally-with-sqlite)