# ezzram
Systemd compatible script for setting up zram swap devices 

Download [PKGBUILD](https://gist.github.com/Jturnerusa/24522c637bf9f71ad745354d4035e1ae)

Once the package is built and installed, make sure to edit /etc/ezzram.conf. To enable the zram devices run:
    systemctl start ezzram.service
    
