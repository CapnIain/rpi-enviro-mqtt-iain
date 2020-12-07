# rpi-enviro-mqtt-iain
MQTT for enviro-pi with ADC used for leak detection

Fork of https://github.com/robmarkcole/rpi-enviro-mqtt/blob/master/mqtt-all.py

To enable the service do the following

sudo systemctl --force --full edit enviro.service
- paste the service file
sudo systemctl enable enviro.service
- reboot
