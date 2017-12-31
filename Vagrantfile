Vagrant.configure("2") do |config|
  config.vm.box = "haikuos/x86_64"

  config.vm.guest = :haiku

  # Vagrant does not bother resetting SSH keys to the proper state when
  # packaging boxes for reuse. To work around that limitation, we
  # disable SSH key regeneration for this and all downstream boxes.
  config.ssh.insert_key = false

  # config.vm.synced_folder ".", "/vagrant", type: "rsync"
  # config.vm.provision "shell", path: "bootstrap.sh"
end
