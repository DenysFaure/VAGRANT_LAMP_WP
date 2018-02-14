Vagrant.configure("2") do |config|
	config.vm.box = "ubuntu/xenial64"
#	config.vm.box_version = "2.0.2"
	config.vm.provision "ansible" do |ansible|
	  	ansible.playbook = "playbook111.yml"
	config.vm.network "private_network", ip: "192.168.56.101"
	end 	
end
