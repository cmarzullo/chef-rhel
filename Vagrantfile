# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.require_version ">= 1.5.0"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.hostname = "rhel-berkshelf"
  config.omnibus.chef_version = :latest

  config.vm.box = "opscode-rhel-7.0"

  config.berkshelf.enabled = true
end
