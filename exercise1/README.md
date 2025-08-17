# Exercise 1: Ubuntu 20.04 LTS Setup with Vagrant

This exercise involved provisioning an Ubuntu 20.04 LTS virtual machine locally via Vagrant, which was completed successfully.

## The Summary of Steps taken are provided below:

- Initialized a Vagrant project by creating a working folder and generating a default `Vagrantfile`.
- Customized the `Vagrantfile` to:
  - Use the Ubuntu 20.04 LTS box (`ubuntu/focal64`).
  - Enable a private network with DHCP so the VM receives an IP address automatically.
- Started the virtual machine using `vagrant up`, which downloaded and booted the box.
- Accessed the VM via `vagrant ssh`.
- Verified the network configuration by running `ifconfig` inside the VM.

I documented the setup by saving the `Vagrantfile` and `ifconfig` output in the exercise1 folder for your review.