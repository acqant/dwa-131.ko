dwa-131.ko
==========

dwa-131 on rockchip

cd /system/lib/modules
cp wlan.ko  rkwifi.ko
insmod rkwifi.ko
setprop wlan.driver.status ok
press the wifi button and it should come up
