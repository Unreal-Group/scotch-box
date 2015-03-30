Vagrant.configure(2) do |config|
  config.vm.box = 'scotch/box'
  config.vm.hostname = 'scotchbox'
  config.vm.network :forwarded_port, host: 4567, guest: 80
  config.vm.synced_folder 'www', '/var/www'
end

