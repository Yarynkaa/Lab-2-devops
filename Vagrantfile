
Vagrant.configure("2") do |config|

  config.vm.provider "virtualbox" do |vb|
    vb.gui = false
    vb.memory = 2048
  end

  config.vm.define "vm1" do |ubuntu|
    ubuntu.vm.box = "ubuntu/focal64"
  end

  config.vm.define "vm2" do |centos|
    centos.vm.box = "centos/7"
  end

end
