# FHIR SERVER
During the past few years, the healthcare industry has accomplished a significant transformation with the digitization of health data. And in the future, the challenge will be to connect and leverage that digitized data to power innovation and AI. Healthcare developers are tasked with the challenge to bring diverse data sets together and develop machine learning across those data sets. The best way to support developers working with health data is to offer tools that allow them to come together for collaboration, creation, sharing, and building on each other’s work.

Fast Healthcare Interoperability Resources (FHIR) is rapidly gaining support in the healthcare community as the next generation standards framework for interoperability, and it’s clear why. FHIR provides a simpler, easier-to-learn, and pragmatic framework. Building on the shared experience of healthcare standards communities, FHIR offers an extensible data model and a REST API to simplify the implementation and interoperability of health data. FHIR Server for Azure provides support infrastructure for immediate provisioning in the cloud, including mapping to Azure Active Directory (Azure AD), and the ability to enable role-based access controls (RBAC).

Developers can save time when it’s required to integrate a FHIR server into an application or use it as a foundation to customize a unique FHIR service. In almost every facet of healthcare, the ambition to create and deliver AI exceeds the tools available to deliver it. Working with data in the FHIR format, developers can use the server to quickly ingest and manage FHIR datasets in a cloud environment, track and manage data access, and begin to normalize data for machine learning workloads.

# Prerequisites
Before deploying the samples scenario, make sure you have Az and AzureAd powershell modules installed:

Install-Module Az
Install-Module AzureAd
The new Az module requires PowerShell version 5.1 or above installed on your computer. So if you have PowerShell version below 5.1, you need to update it. To check your PowerShell version, you can run:

$PSVersionTable.PSVersion
Currently, there is a bug with PowerShell Az Module version 4.6.1 confirmed with Azure ARM team. For now, please avoid using version 4.6.1. Version 4.5 and versions 4.7.0 or above should work fine. To check your Az module version, you can run:

Get-InstalledModule -Name Az
