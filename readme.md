- to create a container

az storage container set-permission --name 'container' --account-name <StorageAccountName> --public-access <blob>

- update file, user the '--overwrite'
  
az storage blob upload --account-name <StorageAccountName> --container-name '<ContainerName>' --name <fileName> --file <local-file-path> --overwrite
