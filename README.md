# driver for tp-link t4u

```
make clean
make
sudo cp 88x2bu.ko /lib/modules/{version kernel}/kernel/drivers/net/wireless
sudo depmod -a
sudo modprobe 88x2bu
```
