Vagrant.configure(2) do |config|
  config.vm.define "ubuntu" do |ubuntu|
    ubuntu.vm.box = "ubuntu/xenial64"
    ubuntu.vm.provision "shell", inline: <<-SHELL
      sudo su -
      cd /vagrant
      ./run_tests.sh
    SHELL
  end
  config.vm.define "centos" do |centos|
    centos.vm.box = "centos/7"
    centos.vm.provision "shell", inline: <<-SHELL
      sudo su -
      cd /vagrant
      ./run_tests.sh
    SHELL
  end
end
