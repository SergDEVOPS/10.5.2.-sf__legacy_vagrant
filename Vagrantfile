Vagrant.configure("2") do |config|
  config.vm.box = "new-box"
  config.vm.provider "virtualbox" do |v|
    v.customize ["modifyvm", :id, "--uartmode1", "disconnected"]
  end	
end
