Vagrant.configure(2) do |config|
  config.vm.provider "virtualbox"
  config.vm.box = "artful"
  config.vm.box_url = "https://uec-images.ubuntu.com/artful/current/artful-server-cloudimg-amd64-vagrant.box"
  config.vm.provision "shell", path: "scripts/provision.sh" , privileged: false
end
