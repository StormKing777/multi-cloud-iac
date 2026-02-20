# Multi-Cloud IaC: Automated Environment Deployment

## Project Summary
This project emphasizes the **"Infrastructure as Code" (IaC)** methodology by using **Terraform** to automate the deployment of resources across both **AWS** and **Azure**. This approach eliminates manual configuration errors and ensures environment consistency.

* **Languages Used:** HCL (HashiCorp Configuration Language).
* **Environments Used:** AWS, Microsoft Azure.
* **Technologies Used:** Terraform.

---

## 🛠️ Implementation Steps

### 1. Provider Configuration & State Management
![Step 1 Screenshot]
* **Action:** Configured Terraform providers for AWS and Azure and initialized the backend state.

### 2. Resource Definition (VPCs & VNETs)
![Step 2 Screenshot]
* **Action:** Wrote HCL code to define Virtual Private Clouds (AWS) and Virtual Networks (Azure) with matching security rules.

### 3. Execution (Plan & Apply)
![Step 3 Screenshot]
* **Action:** Executed `terraform plan` to verify the build and `terraform apply` to deploy the global infrastructure.
