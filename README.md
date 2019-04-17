# Machinify

Create a docker-machine configuration for a machine running RancherOS that you have ssh access to.

This is known to work from a git-bash prompt in Windows. The target machine is running RancherOS on Hyper-V.

RancherOS version 1.5.1 was provisioned through docker-machine.

## Options

-s - regenerate Server certificate

**WARNING**: other clients will need to download the new server certificate to connect.

-R - regenerate Root certificate.

**WARNING**: all dependent applications and clients will need new certificates generated from the new root key.

ssh/scp options will usually be -i for the identity file. Setting up an ssh-agent or similar is recommended.

## Contributing

Please submit pull requests if you want to see improvements! 
