# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|


    config.vm.box = "ubuntu/xenial64"
    config.vm.network "forwarded_port", guest: 1880, host: 1880

    config.vm.provider :virtualbox do |vb|
        vb.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
        vb.customize ["modifyvm", :id, "--natdnsproxy1", "on"]
      end

    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "provisioning/playbook.yml"
    end

end
