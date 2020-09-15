# ezzram
Systemd compatible script for setting up zram swap devices 

Download the [PKGBUILD](https://aur.archlinux.org/packages/ezzram/)

Once the package is built and installed, make sure to edit /etc/ezzram.conf. To setup the zram devices run:
    
    systemctl start ezzram.service
    
You can enable the service to run at boot:

    systemctl enable ezzram.service
    
