# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure('2') do |config|
  config.vm.define 'hive' do |hive|
    hive.vm.box      = 'ubuntu/xenial64'
    hive.vm.hostname = 'hive-ci'
    hive.vm.network 'private_network', ip: '192.168.33.10'
  end

  # config.vm.define 'android-runner' do |runner|
  #   runner.vm.box   = 'ubuntu/xenial64'
  #   runner.hostname = 'android-runner'
  #   runner.vm.network 'private_network', ip: '192.168.33.20'
  # end
  #
  # config.vm.define 'ios-runner' do |runner|
  #   runner.vm.box = 'AndrewDryga/vagrant-box-osx'
  #   runner.hostname = 'ios-runner'
  #   runner.vm.network 'private_network', ip: '192.168.33.30'
  # end
end
