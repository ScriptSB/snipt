Vagrant.configure("2") do |config|
  config.vm.box = "phusion/ubuntu-14.04-amd64"
  config.vm.hostname = "local.snipt.net"
  config.vm.synced_folder ".", "/var/www/snipt/"
  config.vm.network "forwarded_port", guest: 80, host: 80
end
