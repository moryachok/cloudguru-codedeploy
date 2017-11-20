Vagrant.configure(2) do |config|
  config.vm.define "ubuntu" do |ubuntu|
      ubuntu.vm.box = "ubuntu/trusty64"
      ubuntu.vm.hostname = "ubuntu"
      ubuntu.vm.network "private_network", ip: "192.168.33.10"
  end
end