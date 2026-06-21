# Welcome to AzureSecNotByDefault 🛡️

We build production-ready, enterprise-grade Infrastructure as Code (IaC) blueprints designed to eliminate weak cloud vendor defaults. Every module is hard-coded against real-world threats and mapped to modern compliance frameworks.

### 🎯 Our Mission
To bridge the gap between compliance requirements and actual secure cloud deployments. Shift left with confidence.

### 🏗️ Main Repositories

*   📦 **[azure-secure-iac-foundry](https://github.com/AzureSecNotByDefault/azure-secure-iac-foundry)** - Hardened Terraform & Bicep modules.

### 🛡️ Core Hardening Focus (Not-By-Default Blueprint)

Here is how we override insecure cloud defaults out-of-the-box:

| Resource | Vendor Default State (Insecure) | Our Production Standard (Hardened) | Target Framework |
| :--- | :--- | :--- | :--- |
| **Azure Key Vault** | Public access enabled, soft-delete purgeable, RBAC disabled (Vault Policies). | **Disabled public access (Private Endpoints only), enforced Purge Protection, strict Azure RBAC integration.** | NIS 2, CIS, MCSB |
