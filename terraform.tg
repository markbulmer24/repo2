provider "azurerm" {
    
    features {}
}

terraform {
    backend "azurerm" {
        resource_group_name = "MarkRG"    
        storage_account_name = "markstorage1231"
        container_name = "terraform.tfstate"
    }
}
 

resource "azurerm_resource_group" "MarkRG1" {
  name     = "MarkRG1"
  location = "eastus"
}

