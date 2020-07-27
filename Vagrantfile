# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define "pgnode01" do |db|
    db.vm.box = "debian/buster64"
    db.vm.network "private_network", ip: "10.128.64.140"
    config.vm.provider "virtualbox" do |vb|
      vb.memory = 2048
      vb.cpus = 2
    end
  end

  config.vm.define "pgnode02" do |db|
    db.vm.box = "debian/buster64"
    db.vm.network "private_network", ip: "10.128.64.142"
    config.vm.provider "virtualbox" do |vb|
      vb.memory = 2048
      vb.cpus = 2
    end
  end

  config.vm.define "pgnode03" do |db|
    db.vm.box = "debian/buster64"
    db.vm.network "private_network", ip: "10.128.64.143"
    config.vm.provider "virtualbox" do |vb|
      vb.memory = 2048
      vb.cpus = 2
    end
  end
end
