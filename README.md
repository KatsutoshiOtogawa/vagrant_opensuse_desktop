# vagrant_opensuse_desktop
opensuse Destop in vagrant envrionment. if you need suse development environment, you use this.

now this opensuse version is 15.1!

## How to use

You install Windows Remote Desktop Client in advance.

You execute below commands.

```
$ git clone https://github.com/KatsutoshiOtogawa/vagrant_opensuse_desktop.git
$ cd vagrant_opensuse_desktop
$ vagrant up
```

After Vagrant get box,and you wait 40,50 minitues, vagrant install this Desktop environment.

After installed, execute below command.

```
$ vagrant rdp
```

You launching Windows Remote Desktop client,and you type [password is vagrant user].
You will access opensuse via Remote Desktop!
