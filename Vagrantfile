# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "sbeliakou/centos-6.7-x86_64"
  # config.vm.box = "sbeliakou/centos-6.7-x86_64-ansible-2.0.0.2"

  config.vm.network "forwarded_port", guest: 8080, host: 8080

  config.vm.hostname = "mntlab"
  
  config.vm.provider "virtualbox" do |vb|
    vb = config.vm.hostname
  end

  #config.vm.provision "ansible" do |ansible|
  #  ansible.playbook = 'ansible/provision.yml'
  #  ansible.verbose = 'vv'
  #end
end
