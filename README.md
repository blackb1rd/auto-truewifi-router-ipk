Auto-truewifi-router-ipkg
=========================

This package contains shell script auto connect truewifi for Openwrt

How to install
--------------
1. Connecting the internet.

2. Doing opkg update first.
   ```shell
   opkg update
   ```

3. installing package.

   ```shell
   opkg install http://auto-truewifi-router-ipkg.herokuapp.com/packages/truewifi_1-1_all.ipk
   ```

4. Putting the username,password,time in file truewifi.
   ```shell
   vi /etc/config/truewifi
   ```
5. Changing your wifi to TRUEWIFI.

6. Finally rebooting router.
   ```shell
   reboot
   ```

Note: This package is not contain the UCI.

**have fun :)**
