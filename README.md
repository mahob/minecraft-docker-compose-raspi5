# Minecraft on a Raspberry Pi 5

Big thanks to https://github.com/mtoensing for provideing the installtion scripts:

https://github.com/mtoensing/RaspberryPiMinecraft

I addes some systemd unit files to start and stop the minecraft service. Just copy them to `/etc/systemd/system/` and enable them:

```bash
cp ./etc/* /etc/systemd/system/

sudo systemctl daemon-reload
sudo systemctl sudo systemctl enable minecraft
sudo systemctl enable  minecraft-stop-week*
sudo systemctl start minecraft
```

You can now connect to your raspi and play Minecraft. Enjoy!
 