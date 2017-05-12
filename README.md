# Terraform-Provider-NSX

A Terraform provider for VMware NSX.  The NSX provider is used to interact
with resources supported by VMware NSX.  The provider needs to be configured
with the proper credentials before it can be used.

## Wiki Pages
* [Home](https://github.com/sky-uk/terraform-provider-nsx/wiki)
* [Getting Started Guide](https://github.com/sky-uk/terraform-provider-nsx/wiki/Getting-Started-Guide)

## Features
| Feature                 | Create | Read  | Update  | Delete |
|-------------------------|--------|-------|---------|--------|
| DHCP Relay              |   Y    |   Y   |    N    |   Y    |
| Edge Interface          |   Y    |   Y   |    N    |   Y    |
| Logical Switch          |   Y    |   Y   |    N    |   Y    |
| Security Group          |   Y    |   Y   |    Y    |   Y    |
| Security Policy         |   Y    |   Y   |    Y    |   Y    |
| Security Policy Rules   |   Y    |   Y   |    Y    |   Y    |
| Security Tag            |   Y    |   Y   |    Y    |   Y    |
| Security Tag Attachment |   Y    |   Y   |    Y    |   Y    |
| Service                 |   Y    |   Y   |    Y    |   Y    |


### Limitations

At the moment only a very limited number of vSphere NSX resources have been implemented.  These resources also have the basic attributes implemented, look at wiki link above to find more details about each of these resources.

We have only implemented the ability to Create, Read and Delete resources.
Currently there is no implementation of Update.

