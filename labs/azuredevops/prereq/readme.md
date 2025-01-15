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

<a name="Steps"></a>

## Steps

<a name="Select the project template"></a>

### 1. Select the project template

When you run the app will get info about selecting the project template, select the template by number input

![](images/101.png)

<a name="Select the authentication method"></a>

### 2. Select the authentication method

Here you have 2 methods:

1. Device Login using AD auth

   Register Your Application in Azure AD. Refer <a href="../appregister">Register and Setup</a>

   Login with the displaying code

   After the login organizations will be listed and select org to create project

   ![](images/102.png)

2. With Personal Access Token

   <a href="https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&tabs=Windows#create-a-pat">Create Personal Access Token (PAT)</a> with required scopes

   | Scope                      | Description                                |
   | -------------------------- | ------------------------------------------ |
   | vso.agentpools             | Agent Pools (read)                         |
   | vso.build_execute          | Build (read and execute)                   |
   | vso.code_full              | Code (full)                                |
   | vso.dashboards_manage      | Team dashboards (manage)                   |
   | vso.extension_manage       | Extensions (read and manage)               |
   | vso.profile                | User profile (read)                        |
   | vso.project_manage         | Project and team (read, write and manage)  |
   | vso.release_manage         | Release (read, write, execute and manage)  |
   | vso.serviceendpoint_manage | Service Endpoints (read, query and manage) |
   | vso.test_write             | Test management (read and write)           |
   | vso.variablegroups_write   | Variable Groups (read, create)             |
   | vso.work_full              | Work items (full)                          |

   Specify the organization name and the created PAT

   Enter the new project name and press enter, will be created

   ![](images/103.png)
