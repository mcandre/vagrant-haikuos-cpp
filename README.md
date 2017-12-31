# vagrant-haikuos-cpp: a Vagrant box for building C/C++ binaries for HaikuOS

# DISCLAIMER

Currently broken, awaiting a newer Vagrant release after v2.0.1, in order to provide support for HaikuOS guests.

# EXAMPLE

```console
$ vagrant up
$ vagrant ssh -c "cd /vagrant && clang++ -o hello hello.cpp && ./hello"
...
```

# REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* A VM provider, such as [VirtualBox](https://www.virtualbox.org), [VMware](https://www.vmware.com), or [libvirt](https://libvirt.org)
