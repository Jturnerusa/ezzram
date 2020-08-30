# ezzram
Systemd compatible script for setting up zram swap devices 

Download the [PKGBUILD](https://gist.github.com/Jturnerusa/24522c637bf9f71ad745354d4035e1ae)

Once the package is built and installed, make sure to edit /etc/ezzram.conf. To setup the zram devices run:
    
    systemctl start ezzram.service
    
You can enable the service to run at boot:

    systemctl enable ezzram.service
    
