# driver for tp-link t4u

## For 5.8 kernel
```
make clean
make
sudo cp 88x2bu.ko /lib/modules/{version kernel}/kernel/drivers/net/wireless
sudo depmod -a
sudo modprobe 88x2bu
```
## For 5.4 kernel
```
git checkout c77953d
make clean
make
sudo cp 88x2bu.ko /lib/modules/{version kernel}/kernel/drivers/net/wireless
sudo depmod -a
sudo modprobe 88x2bu
```
