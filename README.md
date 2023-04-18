# Terraform-Learn
Terraform is an IAC tool, used primarily by DevOps teams to automate various infrastructure tasks. The provisioning of cloud resources, for instance, is one of the main use cases of Terraform. It's a cloud-agnostic, open-source provisioning tool written in the Go language and created by HashiCorp.
# Infrastructure as Code Tool Means
Infrastructure as Code (IaC) is an approach to managing data center server, storage, and networking infrastructure. IaC is meant to significantly simplify large-scale configuration and management. With traditional data center infrastructure management, every configuration change required manual action by operators and system administrators. With IaC, infrastructure configuration information is housed in standardized files, which can be read by software that maintains the state of the infrastructure. IaC can improve productivity and reliability because it eliminates manual configuration steps.
Infrastructure as code benefits:-
1)Improved productivity. Administrators and operators no longer must perform manual configuration steps for data center infrastructure changes. 2)Improved reliability. The configuration of the infrastructure is contained in electronic files, and software is responsible for initiating infrastructure changes, so there is less chance of human error.
# Architecture and Functioning of Terraform
Terraform’s architecture is comprised of two major components that are Terraform Core & Providers
Terraform core receives input from two sources.
1)The first input source is a Terraform configuration created by you as a user.This is where we specify what needs to be constructed or provided.
2)The second input source is a state in which Terraform keeps the most recent configuration of the infrastructure.As a result, Terraform Core takes the input and creates a plan for what needs to be done. It compares the state, the current state, and the desired configuration in the end result.It specifies what changes must be made to the configuration file to attain the desired state. It computes what must be generated, updated, and removed in order to construct and provision the infrastructure.
Providers
The second design component is providers for certain technologies. AWS, Azure, GCP, and other infrastructure as service providers could be used. It 
also offers higher-level components like Kubernetes and other platform-as-a-service technologies, as well as some self-service software.
It allows us to build infrastructure on numerous levels.Terraform offers over a hundred providers for diverse technologies, with each provider offering access to its resources to Terraform customers. So, for example, we can have access to hundreds of AWS resources such as EC2 instances, AWS users, and so on through an AWS provider.
That is how Terraform works, and it aims to assist us in supplying and covering the full application setup, from infrastructure to application.



