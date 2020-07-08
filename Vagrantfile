Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-18.04"

  config.vm.define "main" do |config
    config.vm.hostname = "main"
    config.vm.network "private_network", ip: "172.16.0.10"
  end

  config.vm.define "server1" do |config
    config.vm.hostname = "server1"
    config.vm.network "private_network", ip: "172.16.0.20"
  end

  config.vm.define "server2" do |config
    config.vm.hostname = "server2"
    config.vm.network "private_network", ip: "172.16.0.30"
  end

  config.vm.define "server3" do |config
    config.vm.hostname = "server3"
    config.vm.network "private_network", ip: "172.16.0.40"
  end
end
