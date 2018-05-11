# rd-ansible-remote-vagrantfile
## Library of shared vagrantfiles

This git repo drives the shared vagrantfiles used within the rd-open-ansible project

## Usage
This repo contains an 'example_shim', simply place this with the name 'Vagrantfile' in the repository. Then define the remote vagrantfile using the variable:

```remote_vagrantfile = "https://raw.githubusercontent.com/bbc/rd-ansible-remote-vagrantfile/master/vagrantfile_ansible_roles"```

it will pull in a remote Vagrantfile.

### Current vagrantfile:

+ vagrantfile_ansible_roles
> This is a shared generic vagrantfile which has both docker and virtualbox and various distros. Designed for fairly generic role testing.

+ vagrantfile_ansible_roles-virtualbox_drives
> This is a shared vagrantfile which creates a bunch of extra hard drives and is virtualbox specific.

+ vagrantfile_ansible_roles-virtualbox_networking
>  This is a shared vagrantfile which creates extra networking and is virtualbox specific.
