# Hello vagrant

## Up and running

- Initialize Vagrant: `vagrant init hashcorp/bionic64`;
- Start the virtual machine: `vagrant up`;
- Destroy the box: `vagrant destroy box_name` if you pass `-f` will delete without ask;
- List what box are outdated `vagrant box outdated`;
- Search and update your boxes `vagrant box update`;
- Stop the box `vagrant halt`;
- Keep the actual state of box `vagrant suspend`;

## Additional commands:

- `egrep -v "^.*#|^$" Vagrantfile` command for remove unnecessary comments
