---
title: Azure DevOps Lab Prerequisites
layout: page
sidebar: vsts
permalink: /labs/azuredevops/prereq/
folder: /labs/azuredevops/prereq/
version: Lab version - 1.39.0
updated: Last updated - 13/01/2025
---

<a name="Overview"></a>

## Overview

Certain Azure DevOps labs require a preconfigured **Parts Unlimited** team project. This document outlines the required steps to set up the required data.

<a name="Overview"></a>

## Steps

<a name="Ex0Task1"></a>

### 1. Select the project template

After the runing the app, you will get info about selecting the project template. Select the template by number input

![](images/101.png)

<a name="Ex0Task2"></a>

### 2. Select the authentication method

Here you have 2 methods:

1. Device Login using AD auth

   - Register Your Application in Azure AD. Refer <a href="../appregister">Register and Setup</a>
   - Login with the displaying code.
   - After the login organizations will be listed

   ![](images/102.png)

2. With Personal Access Token

   <a href="https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&tabs=Windows#create-a-pat">Create Personal Access Token (PAT)</a> with required scopes

   ![](images/103.png)
