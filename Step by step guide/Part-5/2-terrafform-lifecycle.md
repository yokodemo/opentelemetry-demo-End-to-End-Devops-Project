# Terraform Lifecycle

Terraform uses a well-defined lifecycle to manage infrastructure as code.  The lifetime is comprised of multiple steps that ensure resources are created, updated, or removed in a regulated manner.

## 1. **Initialization (`terraform init`)**
- Prepares the working directory for Terraform operations.
- Downloads required provider plugins and modules.
- Configures the backend for storing state files.

## 2. **Planning (`terraform plan`)**
- Analyzes the existing state and the desired configuration.
- Shows a preview of what actions Terraform will take.
- Helps in reviewing changes before applying them.

## 3. **Application (`terraform apply`)**
- Executes the planned changes to create, update, or destroy resources.
- Stores the updated state in the backend.


