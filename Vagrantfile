# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure(2) do |config|
 
  #Aqui se pondria el link de mega de la box
  config.vm.box = "hejuso/JustCode"
 
  config.vm.network "forwarded_port", guest: 80, host: 8080

  config.vm.synced_folder "src/", "/var/www"
  config.vm.synced_folder ".", "/vagrant", disabled: true

  
end
