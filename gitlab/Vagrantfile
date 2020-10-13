# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-16.04"
  config.vm.network "private_network", ip: "192.168.50.10" 
  config.vm.hostname = "gitlab"
  config.vm.provider "virtualbox" do |v|
    v.memory = 3072
    v.cpus = 2
  end
end
