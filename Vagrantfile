# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bmcgonigle/centos68"
#  config.vm.box = "centos/7"
  config.vm.hostname = "git.host"

#  config.vm.network "forwarded_port", guest: 8080, host: 8480

   config.vm.provision "shell",
     path: "./provision.sh"
end
