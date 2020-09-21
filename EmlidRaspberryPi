# Dowloading the image
Plesase Get the latest Emlid Raspbian Image from [here](http://files.emlid.com/images/emlid-raspbian-20191128.img.xz)
# Burn the image

Run Etcher using root and burn the image. You can follow this [video](https://youtu.be/i8_TFYWYt_M)

# Setup Pi
  - Connect Keyboard
  - Connect Mouse
  - Connect LCD
  - Power ON the Pi
  - Wait for 5-10 minutes

# Login
Login to your pi using following 
  - username: pi
  - password: raspberry 
  
# Configuring wireless
To configure your wireless please run the following command

```
sudo nano /boot/wpa_supplicant.conf
```

paste the following, replacing yourssid and yourpasskey with your values
```
network={
  ssid="yourssid"
  psk="yourpasskey"
}
```
save the file. 

# Reboot and Ping the pi
Please reboot the pi. Login again and check the ip of the pi using  following command

```
ifconfig
```
Please note the ip. It shall be something like 192.168.x.x. Open your laptop or computer which is connected to same wireless and see if you can ping the pi.
If you can ping the pi, that means your wireless is configuered correctly.

# SSH to pi

Now open putty or other utility and try to ssh into pi, use the password _raspberry_. You can use one of the following 

```
ssh pi@navio.local
```
or
```
ssh pi@192.168.x.x
```

That is it. 
