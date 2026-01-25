
### DEVICES

badkamer

MAC 38:18:2b:36:21:2c
192.168.1.244

ARP tabel: https://192.168.1.1/ARPTable

This device is using only humidity sensor now, with a hardcoded pattern.

workon esphome
pip install --update esphome
esphome run open-air-mini.yaml --device 192.168.1.244
esphome logs open-air-mini.yaml --device 192.168.1.244 