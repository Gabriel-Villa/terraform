# Error: Code="PlatformImageNotFound" Message="The platform image 'Canonical:UbuntuServer:20.04-LTS:latest' is not available.

```
az vm image list --all --publisher="Canonical" --sku="20_04-lts"  
```

And select one sku

<br />

# Error: Code="BadRequest" Message="The selected VM size 'Standard_F2' cannot boot Hypervisor Generation '2'

Change  size   = "Standard_F2s" to  size = "Standard_F2s_v2"

# Ip public address empty




