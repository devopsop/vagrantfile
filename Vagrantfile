Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-7.3"
  config.vm.network "forwarded_port", guest: 80, host: 80
  config.vm.network "forwarded_port", guest: 8080, host: 8080
  config.vm.network "private_network", ip: "192.168.33.10"
end
