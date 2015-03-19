# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|
  # The most common configuration options are documented and commented below.
  # For a complete reference, please see the online documentation at
  # https://docs.vagrantup.com.

  # Every Vagrant development environment requires a box. You can search for
  # boxes at https://atlas.hashicorp.com/search.
  config.vm.box = "mwiley/vagrant-rails"

  # PostgreSQL Server port
  config.vm.network "forwarded_port", host: 5432, guest: 5432

  # Default Rails server port
  config.vm.network "forwarded_port", host: 3000, guest: 3000

  # Foreman server port
  config.vm.network "forwarded_port", host: 5000, guest: 5000
end
