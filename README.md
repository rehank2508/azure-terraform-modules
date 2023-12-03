# Terraform Azure Modules Repository

Welcome to the Terraform Azure Modules repository! This repository provides Terraform modules for major Azure resources along with example code demonstrating how to use these modules. Feel free to use and provide feedback.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Modules](#modules)
- [Usage Examples](#usage-examples)

## Prerequisites

Before using the Terraform modules in this repository, ensure that you have the following prerequisites:

- [Terraform](https://www.terraform.io/downloads.html) installed.
- Azure subscription and appropriate credentials.

## Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/rehank2508/azure-terraform-modules.git
    cd terraform-azure-modules
    ```

2. Initialize your Terraform configuration:

    ```bash
    terraform init
    ```

3. Configure your Azure credentials:

    ```bash
    export ARM_CLIENT_ID="your-client-id"
    export ARM_CLIENT_SECRET="your-client-secret"
    export ARM_SUBSCRIPTION_ID="your-subscription-id"
    export ARM_TENANT_ID="your-tenant-id"
    ```

4. Apply the Terraform configuration:

    ```bash
    terraform apply
    ```

## Modules

This section provides an overview of the available Terraform modules for Azure resources. Each module is designed for specific Azure resources and includes usage instructions.

## Usage Examples
Explore the examples directory for detailed usage examples of each module. Each example includes a README.md file explaining the scenario and how to use the corresponding module.
