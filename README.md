# DevOps-Terraform-Cloud-Interview-Questions

A. DevOps Interview Questions ✨



B. Terraform Interview Questions ✨

1. How would you create a Terraform CI/CD pipeline for different environments?
2. What resources have you created using Terraform? Explain using the STAR method.
3. Why do we need modules? How do you get output values from a module? Have you used public or private modules?
4. What will you do if a Terraform file gets corrupted?
5. How does Terraform refresh work?
6. What happens if you delete the Terraform state file? How can you recover it?
7. Explain immutable vs mutable infrastructure.
8. What is IaC (Infrastructure as Code) and its lifecycle?
9. What does idempotent mean in Terraform? Give an example.
10. What is configuration drift? How do you detect and correct it?
11. How does Terraform handle dependencies between resources?
12. Explain Terraform state and its importance.
13. What are Terraform backends? Name a few types.
14. How do you manage multiple environments in Terraform?
15. How do you handle sensitive data like passwords or secrets in Terraform?
16. Difference between terraform plan and terraform apply.
17. Difference between local state and remote state.
18. What are workspaces in Terraform? How are they useful?
19. How do you upgrade Terraform modules safely?
20. How do you roll back changes if a Terraform deployment fails?
21. Explain the difference between taint and destroy.
22. How do you version control Terraform code effectively?
23. How can you test or validate Terraform configurations before applying them?
24. Difference between count and for_each.
25. Difference between dynamic blocks and for_each in Terraform.
26. Explain the purpose of depends_on in Terraform.

27. Terraform Commands
terraform init                    # Install required plugins, initialize working directory
terraform init -upgrade           # Upgrade Terraform modules
terraform get                     # Download/update modules and dependencies
terraform plan                    # Generate execution plan
terraform apply                   # Apply changes to infrastructure
terraform apply -auto-approve     # Apply without prompting
terraform apply -replace=<resource_name> # Replace specific resource
terraform workspace new <name>    # Create new workspace
terraform workspace list          # List all workspaces
terraform workspace select <name> # Switch workspace
terraform workspace delete        # Delete a workspace
terraform import <resource>       # Import existing resource into state
terraform show                    # View current state
terraform destroy                 # Destroy infrastructure
terraform plan -destroy           # Preview destruction
terraform apply -destroy          # Destroy resources
terraform destroy -auto-approve  # Destroy without confirmation
terraform providers               # List installed providers
terraform version                 # Show Terraform version
terraform output                  # Show output variables
terraform apply -refresh=false    # Apply without refreshing state
terraform state rm <resource>     # Remove resource from state
terraform state pull              # Download current state
terraform state list              # List all resources
terraform validate                # Validate syntax/configuration
terraform fmt                     # Format configuration
terraform fmt -recursive          # Format all files recursively
terraform refresh                 # Sync Terraform state with real infrastructure
terraform graph                   # Visualize resource relationships
terraform state mv <current> <dest> # Move resource in state file
terraform state push               # Upload local state to remote backend
terraform providers mirror         # Mirror provider plugins locally
terraform providers lock           # Lock provider dependencies
terraform providers schema         # Display provider schema
terraform taint <resource>        # Mark resource as tainted
terraform untaint <resource>      # Remove taint from resource





AWS Cloud Interview Questions ✨
