# **Devops & Cloud Engineering Homework**

## **Objective**
The objective of this assignment is to evaluate your proficiency in deploying and managing applications using Kubernetes, implementing GitOps principles, and integrating AWS services within a DevOps context.

## **Tasks**

1. **Kubernetes Deployment:**

    * Create a VPC in AWS with both public and private subnets.
    * Deploy a Kubernetes cluster in AWS using EKS (Elastic Kubernetes Service) in the private subnet.
    * Deploy a sample application of your choice into the Kubernetes cluster. The application should have at least two microservices.

2. **GitOps Workflow:**

    * Implement a GitOps workflow using ArgoCD for managing the deployment of applications in the Kubernetes cluster.
    * Create a Git repository to store Kubernetes manifests for your sample application.
    * Configure the GitOps tool to continuously synchronize the state of the cluster with the desired state specified in the Git repository.

3. **AWS Integration:**

    * Integrate an Amazon RDS instance for database storage.
    * Implement AWS Secrets Manager to securely manage sensitive information (e.g., database credentials) used by the application.

4. **Scaling and Auto-Healing:**

    * Implement Horizontal Pod Autoscaling (HPA) for one or more components of your sample application.
    * Configure the Kubernetes cluster for automatic scaling based on resource utilization.

5. **Monitoring and Logging:**

    * Integrate AWS CloudWatch for monitoring and logging of the Kubernetes cluster and the deployed application.
    * Set up alerts for critical events or performance thresholds.

6. **Documentation and GitOps Repository:**

    * Provide comprehensive documentation on the entire setup, including steps for deploying the Kubernetes cluster, GitOps workflow, AWS integration, and monitoring/logging configuration.
    * Include a README.md file in your GitOps repository explaining the directory structure, how to contribute, and how the GitOps workflow operates.

**Submission**

1. The Git repository URL containing Kubernetes manifests, the GitOps workflow configuration and Terraform code.
2. It's preferred that all AWS related resources are created using Terraform. 
3. Any additional scripts or configuration files used.
4. Documentation in markdown or plain text format.

**Evaluation:**

Your submission will be evaluated based on the completeness and correctness of the tasks, adherence to best practices, clarity of documentation, and successful integration of AWS services within the Kubernetes and GitOps environment. Considerations for scalability, reliability, and security will be essential.
