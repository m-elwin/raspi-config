This fork of https://github.com/RPi-Distro/raspi-config allows raspi-config to be used on Ubuntu's raspberry pi edition.

To build the debian package, on the raspberryp pi:
```
fakeroot debian/rules clean
fakeroot debian/rules build
frakeroot debian/rules binary
cd ..
apt install ./raspic-config-<version>.deb
