# vagrant-node-red

Vagrant configuration that uses [Ansible](https://www.ansible.com/) to configure and run [Node-RED](https://nodered.org)

To run the project, type `vagrant up` in this directory from the terminal or CLI. To start node-red use the `vagrant ssh` command to access the VM and `node-red` to run the application. Since this is the first time node-red has run it will create follow the configuration in `settings.js` and cant be accessed from `http://127.0.0.1:1880/`

developers may want to run node-red in vscode through node-red extension. It installs as a recommended plugin with the vscode settings here. I also noticed that it will install node-red on the host workstation. 

[](sources)

[](https://github.com/kbjorklid/node-red-vagrant)
[](https://github.com/Ell-i/vagrant-nodered)
[](https://github.com/jdgwartney/vagrant-node-red)
[](https://github.com/jsilence/vagrant-nodered-freeboard)