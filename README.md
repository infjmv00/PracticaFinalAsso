# #Montar la primera vez
#sudo su
#dd bs=4096 count=100 if=/dev/zero of=image
#./mkassoofs image
#insmod assoofs.ko
#mkdir mnt
#mount -o loop -t assoofs image mnt

#Desmontar y montar
#umount mnt
#rmmod assoofs.ko
#make clean
#make
#./mkassoofs image
#insmod assoofs.ko
#mount -o loop -t assoofs image mnt/
