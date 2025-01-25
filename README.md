# action_build
编译immortalwrt固件

源：https://github.com/hanwckf/immortalwrt-mt798x

1. `sudo bash -c 'bash <(curl -sL https://build-scripts.immortalwrt.eu.org/init_build_environment.sh)'`

2. git clone -b openwrt-21.02 --depth 1 https://github.com/hanwckf/immortalwrt-mt798x

3. cp -f .config feeds.conf.default diy-part4.sh immortalwrt-mt798x/

4. cd immortalwrt-mt798x

5. make menuconfig

6. push, github action will start automatically