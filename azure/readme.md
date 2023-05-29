# 1. Check if we are login in azure cli, if not : [Azure documentation](https://github.com/Gabriel-Villa/azure/blob/main/9.%20Azure%20Cli.docx)

```
az account show
```

# 2. Format the file
```
terraform fmt
```

# 3. Initializes a working directory containing Terraform configuration files.
```
terraform init
```

# 4. Show changes required by the current configuration
```
terraform plan
```

# 5. Create or update infrastructure
```
terraform apply -auto-approve
```
# 6. State management
```
terraform state list
terraform show
terraform state show azurerm_resource_group.mtc-rg
```
# 7. Detailed plan of the resources to be destroyed when the apply -destroy is executed
```
terraform plan -destroy
```

# 8. Destroy all the resources
```
terraform apply -destroy
```