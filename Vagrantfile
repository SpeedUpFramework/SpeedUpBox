# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
 
  config.vm.box = "Sparkosis/SpeedUp"
  config.vm.hostname = "SpeedupBox"
  
  config.vm.network "private_network", ip: "192.168.33.12"

  config.vm.synced_folder "./www", "/var/www"

end
