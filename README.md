# WebApplication
It is a web application hosted on AWS, configured by terraform and version controlled by Github

## Project Definition

### EC2 Instance Creation with Terraform

This project showcases the process of provisioning an Amazon EC2 instance using Terraform, demonstrating the principles of Infrastructure as Code (IaC). By utilizing Terraform, I was able to define, deploy, and manage cloud infrastructure efficiently and reliably.

### Goals

- **Learn Terraform Basics**: Gain hands-on experience with Terraform and its syntax for defining cloud resources.
- **Provision EC2 Instance**: Successfully create an EC2 instance on AWS, configuring it with the necessary parameters like AMI, instance type, and tags.
- **Understand Infrastructure Management**: Explore how Terraform manages the state of infrastructure and enables easy updates and resource management.

### Key Features

- **Infrastructure as Code**: All configurations are defined in HCL (HashiCorp Configuration Language) files, making the infrastructure setup reproducible and version-controlled.
- **Modular Design**: The project can be extended to include additional resources (like ELB, RDS) by adding more modules, promoting scalability and reusability.
- **Outputs and Clean Up**: The project includes output values for easily retrieving important information about the created resources, along with a cleanup procedure to dismantle the infrastructure when no longer needed.

### Technologies Used

- **Terraform**: A tool for building, changing, and versioning infrastructure safely and efficiently.
- **AWS**: Amazon Web Services, the cloud platform used for hosting the EC2 instance.

### Expected Outcomes

By the end of this project, I expect to have a functional EC2 instance running on AWS, alongside a deeper understanding of how Terraform can be leveraged for managing cloud infrastructure. This project serves as a foundational step toward mastering cloud engineering and DevOps practices.

---
