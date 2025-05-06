## 🚀 **Terraform Azure Automation**

### [Terraform Azure Automation](https://github.com/erdhirajsingh93/terraform-azure-automation)

A collection of **Terraform scripts** to automate the provisioning of resources in **Azure**. This repository demonstrates how to efficiently deploy cloud resources, including networking, storage, compute, and more, using Infrastructure as Code (IaC). By leveraging Terraform's capabilities, you can easily set up an **Azure environment** with reusable and version-controlled code.

### 🛠️ **Key Features**

* **Automated Cloud Infrastructure**: Fully automated provisioning of Azure resources (VMs, networking, storage, etc.).
* **Scalable Design**: Infrastructure designed for easy scaling and future enhancements.
* **Reusable Modules**: Modular design allowing reuse across different Azure projects.
* **Security Best Practices**: Implements best practices for securing cloud resources like Network Security Groups (NSGs), Managed Identities, etc.
* **Cost-Effective Infrastructure**: Optimized for low-cost Azure environments without sacrificing security or scalability.

---

### 📜 **What’s Included**

This project consists of multiple Terraform files, including:

* **`main.tf`**: Contains the primary configuration and resource definitions.
* **`variables.tf`**: Defines the input variables used throughout the configuration.
* **`outputs.tf`**: Outputs the important details like resource IPs, URLs, etc.
* **`providers.tf`**: Contains provider settings for connecting Terraform with Azure.

---

### 📝 **Steps to Use**

1. **Clone the Repository**:
   Clone this repository to your local machine using:

   ```bash
   git clone https://github.com/erdhirajsingh93/terraform-azure-automation.git
   ```

2. **Set Up Azure Credentials**:
   Ensure that you have an **Azure account** and the **Azure CLI** installed. Authenticate your session with:

   ```bash
   az login
   ```

3. **Initialize Terraform**:
   Initialize the Terraform working directory with the following command:

   ```bash
   terraform init
   ```

4. **Review Plan**:
   Run a Terraform plan to see what changes will be made:

   ```bash
   terraform plan
   ```

5. **Apply Configuration**:
   Apply the Terraform configuration to provision the resources in Azure:

   ```bash
   terraform apply
   ```

6. **Destroy Resources**:
   If you want to destroy the infrastructure when you're done, run:

   ```bash
   terraform destroy
   ```

---

### 🌐 **Key Resources Automated**

* **Virtual Machines (VMs)**: Provision Azure VMs for hosting applications or services.
* **Storage Accounts**: Set up Azure Storage for file and object storage.
* **Virtual Networks (VNets)**: Automate networking setup, including subnets, security groups, and peering.
* **Azure Active Directory**: Configure Azure AD for identity management and access control.

---

### ⚙️ **Technologies Used**

* **Terraform**: Infrastructure as Code (IaC) tool to manage and automate Azure resource provisioning.
* **Azure CLI**: Command-line interface to interact with Azure.
* **Azure Resource Manager (ARM)**: Azure's native tool for managing resources.

---

### 💡 **Why Use Terraform for Azure Automation?**

* **Declarative Syntax**: Terraform uses a simple, human-readable language to define infrastructure, making it easy to understand and maintain.
* **State Management**: Terraform maintains the state of your infrastructure, ensuring that changes are tracked and applied correctly.
* **Platform-Agnostic**: Although this project focuses on **Azure**, Terraform supports other cloud providers like **AWS** and **GCP**, making it suitable for multi-cloud environments.
* **Version Control**: Track infrastructure changes with Git, providing better collaboration and rollback capabilities.

---

### 🚀 **Use Cases for This Project**

* **Automating Azure Resource Deployment**: Automate the process of deploying Azure resources, ensuring consistency and repeatability.
* **CI/CD Integration**: Integrate Terraform into your CI/CD pipelines to automatically provision infrastructure during deployments.
* **Learning and Practicing Terraform**: If you're new to **Terraform** or **Azure**, this repository serves as a great learning resource for understanding infrastructure automation.

---

### 📄 **License**

This project is licensed under the MIT License – see the [LICENSE](https://github.com/erdhirajsingh93/terraform-azure-automation/blob/main/LICENSE) file for details.
