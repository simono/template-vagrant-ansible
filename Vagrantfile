# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/wily64"

  config.vm.provision "ansible" do |a|
    a.playbook = "playbook.yml"
    #a.verbose = 'vvvv'
  end
end
