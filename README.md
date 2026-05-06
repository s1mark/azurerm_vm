module "private_vm" {
  source              = "./modules/linux_vm"
  vm_name             = "user-node-01"
  location            = "germanywestcentral"
  resource_group_name = # tbd
  subnet_id           = # tbd
}
