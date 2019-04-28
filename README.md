make clean && make

sudo insmod rickroll.ko
sudo mknod rickroll c %MAJOR 0 
sudo rmmod rickroll

view logs with dmesg --follow
