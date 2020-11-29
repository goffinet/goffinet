I am working on several projects around IaC :

- [goffinet/virt-scripts](https://github.com/goffinet/virt-scripts/) is a Bash collection in front of Libvirt to manage KVM guests in Linux labs.
- [goffinet/packer-kvm](https://github.com/goffinet/packer-kvm) is a kvm builder for images used by [goffinet/virt-scripts](https://github.com/goffinet/virt-scripts/).
- [goffinet/terraform-libvirt](https://github.com/goffinet/terraform-libvirt) is a Terraform lab plan that uses [goffinet/packer-kvm](https://github.com/goffinet/packer-kvm) images.
- [goffinet/kvm-ansible-lab](https://github.com/goffinet/kvm-ansible-lab/) is an Ansible playbook that installs a lab with Ansible as provisionner and Libvirt/KVM as provider.
- [goffinet/vagrant-libvirt-ubuntu-bionic-ansible-lab](https://github.com/goffinet/vagrant-libvirt-ubuntu-bionic-ansible-lab/) is an Ubuntu Bionic only Bash script that installs a lab with Vagrant as provisionner and Libvirt/KVM as provider (and also Packer and Terraform for KVM).
- [goffinet/vagrant-ansible-lab](https://github.com/goffinet/vagrant-ansible-lab/) is an Ansible playbook that installs a lab with Vagrant as provisionner and Virtualbox as provider.
- [goffinet/ansible-install-gns3-server](https://github.com/goffinet/ansible-install-gns3-server) is an Ansible playbook to automate GNS3 servers installation on Packet or Scaleway (archived, here for reminder).
- [goffinet/ansible-ccna-lab](https://github.com/goffinet/ansible-ccna-lab) is an Ansible playbook to orchestrate CCNA labs.
- [goffinet/docker-ansible-lab](https://github.com/goffinet/docker-ansible-lab/) is a bash script that installs Docker and launch a lab for Ansible learning.
