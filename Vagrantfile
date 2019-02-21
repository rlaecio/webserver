Vagrant.configure("2") do |config|
	config.vm.box = "CentosBox/Centos7-v7.3-Web-Server"
	config.vm.provider "virtualbox" do |v|
		v.memory = 1024
	end

	config.vm.define :webserver do |web_config|
		web_config.vm.network :public_network, :ip => "192.168.0.150"
	end
end
