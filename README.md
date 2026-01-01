## 🎬 Watch Me Build This Lab!

# host-static-website-lab
Hands on lab demonstrating how to host a static website using Azure Blob Storage

# Azure Static Website Deployment Lab

## Overview

This lab demonstrates how to deploy a **static website using Microsoft Azure Blob Storage**. The goal is to showcase foundational cloud skills including resource management, storage configuration, and static web hosting—all presented in a clean, recruiter‑friendly workflow.

By the end of this lab, a publicly accessible static website is live using Azure’s native static website hosting feature.

---

## Technologies Used

* **Microsoft Azure**
* **Azure Storage Account (Blob Storage)**
* **Static Website Hosting**
* **HTML (Java-based dynamic structure generated with ChatGPT)**

---

## Lab Objectives

* Create and organize Azure resources properly
* Configure Azure Blob Storage for static website hosting
* Deploy and host a custom HTML website
* Validate successful public access via Azure endpoint

---

## Step-by-Step Implementation

### 1. Resource Group Creation

* Created a **new Azure Resource Group** named:

  ```
  Skool
  ```

  This ensures clean organization and isolation of lab resources.

---

### 2. Storage Account Deployment

* Created a **brand-new Azure Storage Account**:

  ```
  skoolstorage246810
  ```
* Successfully deployed the storage account within the **Skool** resource group.

---

### 3. Enable Static Website Hosting

* Navigated to the storage account
* Selected **Static Website** under the **Data Management** section
* Enabled static website hosting
* Configured:

  * **Index document:** `indexjava.html`
  * **Error document path:** `404`

This automatically created the `$web` container used for hosting site files.

---

### 4. Website Content Creation

* Prompted ChatGPT to generate a **dynamic Java-based HTML file** suitable for a static Azure website
* Ensured the file followed static hosting requirements

---

### 5. Upload Website Files

* Navigated to:

  ```
  Data Storage → Containers → $web
  ```
* Uploaded the `indexjava.html` file to the `$web` container

---

### 6. Validate Deployment

* Returned to the **Static Website** configuration page
* Copied the **Primary Endpoint URL**
* Opened the endpoint in a new browser tab
* Confirmed the website loads successfully and is publicly accessible

---

## Result

A fully functional **Azure-hosted static website** deployed using Blob Storage, demonstrating hands-on experience with:

* Cloud resource provisioning
* Storage configuration
* Static web hosting
* Deployment validation

---

## Why This Lab Matters

This project highlights practical Azure fundamentals that are directly applicable to real-world cloud and DevOps roles, including:

* Clean resource management
* Platform-as-a-Service (PaaS) usage
* Web hosting without servers

---

## Author

**Jason Roland**
Cloud • IT • Security Enthusiast

---

## Notes

This lab was built for learning and portfolio demonstration purposes and can be easily extended with:

* Custom domains
* HTTPS enforcement
* CI/CD pipelines
* Azure Front Door or CDN integration
