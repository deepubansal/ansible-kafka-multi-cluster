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

config.vm.define "aws1" do |aws1|
    aws1.vm.box = "grtjn/centos-6.5"
    aws1.vm.hostname = "aws1"
    aws1.vm.network "private_network", ip: "192.168.10.21"
  end

config.vm.define "aws2" do |aws2|
    aws2.vm.box = "grtjn/centos-6.5"
    aws2.vm.hostname = "aws2"
    aws2.vm.network "private_network", ip: "192.168.10.22"
  end

config.vm.define "aws3" do |aws3|
    aws3.vm.box = "grtjn/centos-6.5"
    aws3.vm.hostname = "aws3"
    aws3.vm.network "private_network", ip: "192.168.10.23"
  end

config.vm.define "aws4" do |aws4|
    aws4.vm.box = "grtjn/centos-6.5"
    aws4.vm.hostname = "aws4"
    aws4.vm.network "private_network", ip: "192.168.10.24"
  end

config.vm.define "aws5" do |aws5|
    aws5.vm.box = "grtjn/centos-6.5"
    aws5.vm.hostname = "aws5"
    aws5.vm.network "private_network", ip: "192.168.10.25"
  end

config.vm.define "aws6" do |aws6|
    aws6.vm.box = "grtjn/centos-6.5"
    aws6.vm.hostname = "aws6"
    aws6.vm.network "private_network", ip: "192.168.10.26"
  end

config.vm.define "aws7" do |aws7|
    aws7.vm.box = "grtjn/centos-6.5"
    aws7.vm.hostname = "aws7"
    aws7.vm.network "private_network", ip: "192.168.10.27"
  end

config.vm.define "aws8" do |aws8|
    aws8.vm.box = "grtjn/centos-6.5"
    aws8.vm.hostname = "aws8"
    aws8.vm.network "private_network", ip: "192.168.10.28"
  end



  # Disable automatic box update checking. If you disable this, then
  # boxes will only be checked for updates when the user runs
  # `vagrant box outdated`. This is not recommended.
  # config.vm.box_check_update = false

  # Create a forwarded port mapping which allows access to a specific port
  # within the machine from a port on the host machine. In the example below,
  # accessing "localhost:8080" will access port 80 on the guest machine.
  # config.vm.network "forwarded_port", guest: 80, host: 8080

  # Create a private network, which allows host-only access to the machine
  # using a specific IP.
  # config.vm.network "private_network", ip: "192.168.33.10"

  # Create a public network, which generally matched to bridged network.
  # Bridged networks make the machine appear as another physical device on
  # your network.
  # config.vm.network "public_network"

  # Share an additional folder to the guest VM. The first argument is
  # the path on the host to the actual folder. The second argument is
  # the path on the guest to mount the folder. And the optional third
  # argument is a set of non-required options.
  # config.vm.synced_folder "../data", "/vagrant_data"

  # Provider-specific configuration so you can fine-tune various
  # backing providers for Vagrant. These expose provider-specific options.
  # Example for VirtualBox:
  #
  # config.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
  #   vb.gui = true
  #
  #   # Customize the amount of memory on the VM:
  #   vb.memory = "1024"
  # end
  #
  # View the documentation for the provider you are using for more
  # information on available options.

  # Define a Vagrant Push strategy for pushing to Atlas. Other push strategies
  # such as FTP and Heroku are also available. See the documentation at
  # https://docs.vagrantup.com/v2/push/atlas.html for more information.
  # config.push.define "atlas" do |push|
  #   push.app = "YOUR_ATLAS_USERNAME/YOUR_APPLICATION_NAME"
  # end

  # Enable provisioning with a shell script. Additional provisioners such as
  # Puppet, Chef, Ansible, Salt, and Docker are also available. Please see the
  # documentation for more information about their specific syntax and use.
  # config.vm.provision "shell", inline: <<-SHELL
  #   sudo apt-get update
  #   sudo apt-get install -y apache2
  # SHELL
end
