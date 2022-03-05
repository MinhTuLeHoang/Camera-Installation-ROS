# Camera-Installation-ROS

##How to install raspi-camera correctly

You can refer to these links:
- https://emanual.robotis.com/docs/en/platform/turtlebot3/appendix_raspi_cam/
- 


install raspi-config
```
wget https://archive.raspberrypi.org/debian/pool/main/r/raspi-config/raspi-config_20200601_all.deb -P /tmp
sudo apt-get install libnewt0.52 whiptail parted triggerhappy lua5.1 alsa-utils -y
# Auto install dependancies on eg. ubuntu server on RPI
sudo apt-get install -fy
sudo dpkg -i /tmp/raspi-config_20200601_all.deb

sudo apt-get install raspi-config
```



when select P1 Camera, It will ask you to mount the camera, follow this link:
https://chuckmails.medium.com/enable-pi-camera-with-raspberry-pi4-ubuntu-20-10-327208312f6e


missing raspistill, thì install nó:
(search link sau)


Khi catkin_make gặp lỗi diagnostic_updater bị thiếu
```
sudo apt-get install ros-noetic-diagnostic-updater
```


Khi catkin_make gặp lỗi vchostiff bị thiếu:
```
sudo apt install libraspberrypi-dev libraspberrypi0
```





