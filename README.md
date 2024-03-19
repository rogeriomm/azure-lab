


# Install tools
## Install ASDF
      * https://asdf-vm.com/guide/getting-started.html

```shell
echo . "$HOME/.asdf/asdf.sh" >> $HOME/.bashrc
```
## Install Azure CLI
```shell
version="2.58.0"
asdf plugin add azure-cli
asdf install azure-cli $version
asdf global azure-cli $version
```

## Install Terraform
```shell
version="1.7.5"
asdf plugin add terraform
asdf install terraform $version
asdf global terraform $version
```



```shell
az account set --subscription []
```
