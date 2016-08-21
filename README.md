# Internet Applications Vagrant Stack

This Vagrant is a very simple implementation for the internet applications course.

## USE
**You need have installed [VirtualBox](https://www.virtualbox.org/) and [Vagrant](https://www.vagrantup.com/) in your system**

Install VirtualBox Guest Additions Plugin
```
$ vagrant plugin install vagrant-vbguest
```

Start The virtual machine
```
$ vagrant up
```

Connect to the virtual machine via ssh:

```
$ vagrant ssh
```

Logout vagrant (This command is used inside the virtual machine)
```
$ logout
```

Stop the virtual machine
```
$ vagrant halt
```

Restart the virtual machine
```
$ vagrant reload
```

Add new dependencies to the virtual machine
```
$ vagrant provision
```

Remove completly
```
$ vagrant destroy
```
