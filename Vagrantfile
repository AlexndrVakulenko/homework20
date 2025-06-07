Vagrant.configure("2") do |config|

config.vm.define "pxeserver" do |server|
		server.vm.box = 'bento/ubuntu-22.04'
		server.vm.host_name = 'pxeserver'
		server.vm.network "forwarded_port", guest: 80, host: 8080
		server.vm.network :private_network,ip: "10.0.0.20",virtualbox__intnet: 'pxenet'
		server.vm.network :private_network, ip: "192.168.56.10"
		server.vm.provider "virtualbox" do |vb|
	vb.memory = "1024"
	vb.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
	end
end
end
