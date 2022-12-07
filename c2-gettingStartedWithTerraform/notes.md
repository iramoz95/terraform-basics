# Terraform

## Commands

- **terraform init:** tell terraform to scan the code, figure out which providers you are using, and download the code for them
- **terraform plan:** lets you see what Terraform will do before actually making any changes
- **terraform apply:** creates the described instances
- **terraform graph**: show you the dependency graph
- **terraform output**: list all outputs without applying any changes
  - You can run terraform output <OUTPUT_NAME> to see the value of a specific output called <OUTPUT_NAME>. This is particulary handy for scripting.
