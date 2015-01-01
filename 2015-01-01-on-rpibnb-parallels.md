## rpibnb-discussion

http://forum.openframeworks.cc/t/pre-built-environment-for-raspberry-pi-cross-compiling-and-nfs-booting/16206/30

@moebiussurfing
Some note on getting this running with Parallels

first you need this vagrant plugin
https://github.com/Parallels/vagrant-parallels
install it by using this line
`vagrant plugin install vagrant-parallels`

then get vagrant box for parallels install 
`vagrant box add parallels/ubuntu-12.04`

I also changed this line in `Vagrantfile` according to @eric_gradman
`config.vm.box = "parallels/ubuntu-12.04"`

Now it's provisioning on mine. Finger-crossed if it will run fine :P