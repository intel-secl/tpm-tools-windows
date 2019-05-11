# Intel<sup>®</sup> Security Libraries for Data Center  - Windows TPM Tools
#### This project provides tools for provisioning and management of TPM in windows systems.

## Key features
- Provides interface for managing TPM in Windows Systems

## System Requirements
- RHEL 7.5/7.6
- Epel 7 Repo
- Proxy settings if applicable

## Software requirements
- git
- maven (v3.3.1)
- ant (v1.9.10 or more)

# Step By Step Build Instructions
## Install required shell commands
Please make sure that you have the right `http proxy` settings if you are behind a proxy
```shell
export HTTP_PROXY=http://<proxy>:<port>
export HTTPS_PROXY=https://<proxy>:<port>
```
### Install tools from `yum`
```shell
$ sudo yum install -y wget git zip unzip ant gcc patch gcc-c++ trousers-devel openssl-devel makeself
```

## No Direct dependencies

## Build Windows TPM Tools

- Git clone the `Windows TPM Tools`
- Run scripts to build the `Windows TPM Tools`

```shell
$ git clone https://github.com/intel-secl/tpm-tools-windows.git
$ cd tpm-tools-windows
$ ant
```

# Links
 - Use [Automated Build Steps](https://01.org/intel-secl/documentation/build-installation-scripts) to build all repositories in one go, this will also provide provision to install prerequisites and would handle order and version of dependent repositories.

***Note:** Automated script would install a specific version of the build tools, which might be different than the one you are currently using*
 - [Product Documentation](https://01.org/intel-secl/documentation/intel%C2%AE-secl-dc-product-guide)
