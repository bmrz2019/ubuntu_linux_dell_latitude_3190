# Dell latitude 3190 Ubuntu


- screen size 11" 
- HD TN, 
- Celeron N4120, 
- 4GB RAM, 
- 128GB NVMe SSD, 
- Windows 10 Pro

##  ```lubuntu-18.04.04-desktop-amd64.iso``` 

### tldr; everything works 100 %

- Brightness +/-
- Audio (mic + speaker fine)
- Webcam
- hibernate
- WiFi
- HDMI (even 4K works fine - without stuttering)

### Not good

- Just 4GB RAM
- No ethernet port
- Only 2 X USB 3

### Upgrades

- RAM slots - None (embedded)
- 1 X m2 SSD (nvme) 
- So much space for 2.5 inch disks. 


## Device information

- 
- Verify with ```inxi -Fxxxrz```

- output

```
user@dell: ~ $ inxi -Fxxxrz
System:    Host: e6430s Kernel: 4.15.0-106-generic x86_64 bits: 64 gcc: 7.5.0
           Desktop: LXDE (Openbox 3.6.1) info: lxpanel dm: lightdm Distro: Ubuntu 18.04.4 LTS
Machine:   Device: laptop System: Dell product: Latitude 3190 serial: N/A  Chassis: type: 10 serial: N/A
           Mobo: Dell model: 0CGVKX v: A00 serial: N/A UEFI: Dell v: 1.16.0 date: 07/12/2021
Battery    BAT0: charge: 39.9 Wh 100.0% condition: 39.9/42.0 Wh (95%) volts: 13.0/11.4
           model: SMP DELL VM73297 Li-poly serial: <filter>status: Discharging cycles: 0
CPU:       Quad core Intel Celeron N4120 (-MCP-) arch: N/A cache: 4096 KB
           flags: (lm nx sse sse2 sse3 sse4_1 sse4_2 ssse3 vmx) bmips: 8755
           clock speeds: min/max: 800/2600 MHz 1: 919 MHz 2: 940 MHz 3: 1051 MHz 4: 1241 MHz
Graphics:  Card: Intel Device 3185 bus-ID: 00:02.0 chip-ID: 8086:3185
           Display Server: x11 (X.Org 1.19.6 ) drivers: modesetting (unloaded: fbdev,vesa)
           Resolution: 1366x768@60.00hz
           OpenGL: renderer: Mesa DRI Intel UHD Graphics 600 (Geminilake 2x6)
           version: 4.5 Mesa 19.2.8 (compat-v: 3.0) Direct Render: Yes
Audio:     Card Intel Device 3198 driver: snd_hda_intel bus-ID: 00:0e.0 chip-ID: 8086:3198
           Sound: Advanced Linux Sound Architecture v: k4.15.0-106-generic
Network:   Card: Intel Wireless 8265 / 8275 driver: iwlwifi bus-ID: 01:00.0 chip-ID: 8086:24fd
           IF: wlp1s0 state: up mac: <filter>
Drives:    HDD Total Size: 128.0GB (13.0% used)
           ID-1: /dev/nvme0n1 model: NVMe_KIOXIA_128GB size: 128.0GB
           serial: <filter> firmware: 10410104
Sensors:   System Temperatures: cpu: 32.0C mobo: 25.0C
           Fan Speeds (in rpm): cpu: N/A
```


  


## Images

![alt text](https://raw.githubusercontent.com/bmrz2019/latitude_3190/main/inside.jpg "01")

![alt text](https://raw.githubusercontent.com/bmrz2019/latitude_3190/main/back.jpg "01")

![alt text](https://raw.githubusercontent.com/bmrz2019/latitude_3190/main/battery.jpg "01")

![alt text](https://raw.githubusercontent.com/bmrz2019/latitude_3190/main/nvme.jpg "01")

![alt text](https://raw.githubusercontent.com/bmrz2019/latitude_3190/main/usb.jpg "01")


