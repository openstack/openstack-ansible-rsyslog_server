Vagrant.configure(2) do |config|
  config.vm.provider "virtualbox" do |v|
    v.memory = 2048
    v.cpus = 2
  end

  config.vm.define "ubuntu1604" do |xenial|
    xenial.vm.box = "ubuntu/xenial64"
    xenial.vm.provision "shell", inline: <<-SHELL
      sudo su -
      cd /vagrant
      ./run_tests.sh
    SHELL
  end

  config.vm.define "opensuse421" do |leap421|
    leap421.vm.box = "opensuse/openSUSE-42.1-x86_64"
    leap421.vm.provision "shell", inline: <<-SHELL
      sudo su -
      cd /vagrant
      ./run_tests.sh
    SHELL
  end

  config.vm.define "centos7" do |centos7|
    centos7.vm.box = "centos/7"
    centos7.vm.provision "shell", inline: <<-SHELL
      sudo su -
      cd /vagrant
      ./run_tests.sh
    SHELL
  end

end
