# Steps to create the VM using Vagrant (after installing Vagrant and VirtualBox)

1. Copy the file "Vagrantfile" to some folder in your local machine.
2. Open the default shell in your local machine and navigate to the folder where the "Vagrantfile" was copied to.
3. Type the following in the shell: "vagrant up" (without quotes)
4. The vagrant file will begin executing an at some point the VM will start up on VirtualBox.
5. Use these credentials to login to the guest OS:</br>
Username: vagrant</br>
Password: vagrant</br>

# Acknowledgments
* Used vagrant virtual box image of [Windows 8.1 64-bit by mwrock](https://atlas.hashicorp.com/mwrock/boxes/Windows8.1-amd64).

#References
* https://docs.vagrantup.com/v2/getting-started/index.html
* https://docs.vagrantup.com/v2/provisioning/shell.html 
* https://docs.vagrantup.com/v2/virtualbox/configuration.html
