# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.define "monitoring" do |monitoring|
    monitoring.vm.box = "monitoring"
    monitoring.vm.box_url = "https://github.com/holms/vagrant-centos7-box/releases/download/7.1.1503.001/CentOS-7.1.1503-x86_64-netboot.box"
    monitoring.vm.network "private_network", ip: "192.168.56.10"
    monitoring.vm.synced_folder ".", "/vagrant_data"
  end
#  config.vm.define "web" do |web|
#    web.vm.box = "web"
#    web.vm.box_url = "https://github.com/holms/vagrant-centos7-box/releases/download/7.1.1503.001/CentOS-7.1.1503-x86_64-netboot.box"
#    web.vm.network "private_network", ip: "192.168.56.11"
#    web.vm.synced_folder ".", "/vagrant_data"
#  end


end
