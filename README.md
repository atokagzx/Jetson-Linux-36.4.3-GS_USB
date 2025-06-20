```bash
sudo mkdir /lib/modules/5.15.148-tegra/kernel/drivers/net/can/usb/
cp gs_usb.ko /lib/modules/5.15.148-tegra/kernel/drivers/net/can/usb/
sudo depmod
sudo modprobe gs_usb
```
