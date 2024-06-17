# raspberryPi_setup

## Hardware
- Raspberry Pi 4 Model B 8GB [Datasheet](https://datasheets.raspberrypi.com/rpi4/raspberry-pi-4-datasheet.pdf)
- SOC: BMC2711 [Reference](https://www.raspberrypi.com/documentation/computers/processors.html#bcm2711)
- 128GB SD card

## Software
- Ubuntu 20.04
- Raspberrypi Imager [Reference](https://ubuntu.com/download/raspberry-pi)
> By default Raspberry Pi does not support the Ubuntu 20.04 Desktop image. After installation run the following
```
sudo apt-get install ubuntu-desktop
```

## Remote SSH
Best tutorial I could find for headless remote access via SSH [Link](https://youtu.be/ZKfnGqMrnug?si=8Tgtny_HrIdzjnHg)

## Power monitor 
- Using the TC66C USC charge tester 
- Reference guide to all details [Link](https://youtu.be/rOlhibDUJgs?si=OIWAIgBVffbeVPSH)

## Reducing power

Can disable 
-  USB ports
-  HDMI
-  Bluetooth

Reference [https://core-electronics.com.au/guides/disable-features-raspberry-pi/](https://core-electronics.com.au/guides/disable-features-raspberry-pi/)

Not Relevant but can reduce standby power on shutdown : [https://www.jeffgeerling.com/blog/2023/reducing-raspberry-pi-5s-power-consumption-140x](https://www.jeffgeerling.com/blog/2023/reducing-raspberry-pi-5s-power-consumption-140x)
