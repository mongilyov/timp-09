# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.provision "shell", inline: "echo Hello"

  config.vm.define "virtualMachine1" do |virtualMachine1|
    virtualMachine1.vm.box = "bento/ubuntu-22.04-arm64"
  end

  config.vm.define "virtualMachine2" do |virtualMachine2|
    virtualMachine2.vm.box = "bento/ubuntu-22.04-arm64"
  end
end
