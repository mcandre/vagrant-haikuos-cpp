# DEPRECATED

See https://github.com/mcandre/vagrant-haiku-cpp instead

# vagrant-haikuos-cpp: a Vagrant box for building C/C++ binaries for HaikuOS

# DISCLAIMER

Currently broken, awaiting a newer Vagrant release after v2.0.1, in order to provide support for HaikuOS guests.

# EXAMPLE

```console
$ vagrant up
$ vagrant ssh -c "cd /vagrant && clang++ -o hello hello.cpp && ./hello"
...
```

# RUNTIME REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* The [VirtualBox](https://www.virtualbox.org) hypervisor provider

## Recommended

* [vagrant-rsync-back](https://github.com/smerrill/vagrant-rsync-back) assists in copying artifacts from the guest to the host

# BUILDTIME REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* The [VirtualBox](https://www.virtualbox.org) hypervisor provider
* [make](https://www.gnu.org/software/make/)

# EXPORT

```console
$ make vagrant-haikuos-cpp.box
```
