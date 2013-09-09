Auto-truewifi-router-ipkg
=========================

This package contains script auto connect truewifi for Openwrt

How to install
--------------
1. Connect your internet.

2. Do opkg update first.
```shell
opkg update
```

3. Select you version.

   ```shell
   opkg install http://auto-truewifi-router-ipkg.herokuapp.com/packages/truewifi_1-1_all.ipk
   ```

4. Insert the username,password,time in file truewifi.
```shell
vi /etc/config/truewifi
```
5. Connect TRUEWIFI.

6. Finally reboot router.
```shell
reboot
```
Note: No have UCI.

**have fun :)**
