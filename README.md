# Infrastructure as Code (IaC) with Terraform

## Objective
Provision a **local Docker container** using **Terraform**, leveraging the Docker provider.

---

## Tools Used
- **Terraform**
- **Docker (local setup)**

---

## Task Completed with Ease 

This task was an exciting hands-on experience where I smoothly provisioned and managed Docker infrastructure using Terraform. Below are the key steps I followed along with relevant screenshots.

---

## What I Did

1. **Wrote Terraform Configuration**
   - Created a `main.tf` file.
   - Used the official Docker provider.
   - Defined a Docker image and a container resource.

2. **Initialized Terraform**
   ```bash
   terraform init
    ```

3. **Planned the Infrastructure**
    ```bash
    terraform plan
    ```

4. **Applied the Configuration**
    ```bash
    terraform apply
    ```

5. **Verified Docker Container**

    I confirmed the execution, and Terraform successfully created the Docker image and container as defined.
    ```bash
    docker ps
    ```
    This displayed the resources managed by Terraform – confirming everything was being tracked correctly.

6. **Destroyed Infrastructure**
    ```bash
    terraform destroy
    ```
    Finally, I destroyed the Docker container and cleaned up everything Terraform had created.

### Screentshots Added
/Screenshots