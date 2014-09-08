VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.define "api01" do |api01|
    api01.vm.box_url = "https://oss-binaries.phusionpassenger.com/vagrant/boxes/latest/ubuntu-14.04-amd64-vbox.box"
    api01.vm.box = "Ubuntu1404"
    api01.vm.hostname = "api01"
    api01.vm.network "private_network", ip: "192.168.255.6"
    api01.vm.network "public_network", ip: "172.31.255.5"

    api01.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "512"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
  end

  config.vm.define "api02" do |api02|
    api02.vm.box_url = "https://oss-binaries.phusionpassenger.com/vagrant/boxes/latest/ubuntu-14.04-amd64-vbox.box"
    api02.vm.box = "Ubuntu1404"
    api02.vm.hostname = "api02"
    api02.vm.network "private_network", ip: "192.168.255.7"
    api02.vm.network "public_network", ip: "172.31.255.6"

    api02.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "512"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
  end

  config.vm.define "node01" do |node01|
    node01.vm.box_url = "https://oss-binaries.phusionpassenger.com/vagrant/boxes/latest/ubuntu-14.04-amd64-vbox.box"
    node01.vm.box = "Ubuntu1404"
    node01.vm.hostname = "node01"
    node01.vm.network "private_network", ip: "192.168.255.10"

    node01.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "512"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
  end

  config.vm.define "node02" do |node02|
    node02.vm.box_url = "https://oss-binaries.phusionpassenger.com/vagrant/boxes/latest/ubuntu-14.04-amd64-vbox.box"
    node02.vm.box = "Ubuntu1404"
    node02.vm.hostname = "node02"
    node02.vm.network "private_network", ip: "192.168.255.11"

    node02.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "512"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
  end

  config.vm.define "node03" do |node03|
    node03.vm.box_url = "https://oss-binaries.phusionpassenger.com/vagrant/boxes/latest/ubuntu-14.04-amd64-vbox.box"
    node03.vm.box = "Ubuntu1404"
    node03.vm.hostname = "node03"
    node03.vm.network "private_network", ip: "192.168.255.12"

    node03.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", "512"]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
  end

end
