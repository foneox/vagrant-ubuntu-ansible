Vagrant.configure(2) do |config|

  config.vm.box = "ubuntu/trusty64"
  config.vm.provision :shell, path: "ansible-install.sh"
  config.vm.provision :shell, path: "pip-robo-install.sh"
  config.vm.provision :shell, path: "export-keys.sh"
  config.vm.provision :shell, path: "run-ansible.sh"

end
