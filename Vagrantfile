Vagrant.configure("2") do |config|
  config.vm.box = "eurolinux-vagrant/centos-stream-9"
  config.vm.hostname = "devops-part3"

  config.vm.network "private_network", ip: "192.168.56.54"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "4096"
    vb.cpus = 2
  end
end