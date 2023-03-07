# openwrt-r8168-1
Realtek RTL8168 Driver for Openwrt
# Download and put it into openwrt/package/ folder 
# make menuconfig
and navigate to Kernel module --> network devices --> [*] ksmod-rtl8168 xxxxx  
# make V=s -j4 
# have fun.
