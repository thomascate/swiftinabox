VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.define "api01" do |api01|
    api01.vm.box_url = https://cloud-images.ubuntu.com/vagrant/trusty/trusty-server-cloudimg-amd64-juju-vagrant-disk1.box
    api01.vm.box = "Ubuntu1204"
    api01.vm.hostname = "api01"
    api01.vm.network "private_network", ip: "192.168.255.6"

    api01.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "512"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
  end

end
