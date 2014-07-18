apt-fast-vagrant-install
========================
add the following line to your vagrant file provisions
```
config.vm.provision :shell, :path => ".vagrantScripts/apt-fast-install.sh"
```

Then replace apt-get with apt-fast in any of your scripts

[Link to apt-fast](https://github.com/ilikenwf/apt-fast)
