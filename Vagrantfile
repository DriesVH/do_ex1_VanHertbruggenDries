Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "dries.be"
config.vm.network "forwarded_port", guest: 80, host: 1234
end
