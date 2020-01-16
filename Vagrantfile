Vagrant.configure("2") do |config|
  config.vm.box = "marina"
  config.vm.hostname = "jenkins.box"
  config.vm.provision "ansible" do |ansible|
    ansible.verbose = "v"
    ansible.playbook = "playbook.yml"
  end
end
