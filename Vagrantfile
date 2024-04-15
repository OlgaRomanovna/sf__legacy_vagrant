Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64" # Выбираем базовый образ Ubuntu 20.04

  config.vm.provision "shell", inline: <<-SHELL
    sudo apt-get update
    sudo apt-get install -y postgresql-8.4
  SHELL
end
