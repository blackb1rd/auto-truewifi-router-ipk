Auto-truewifi-router-ipkg
=========================

This package contains script auto connect truewifi

How to install
--------------
1. Do opkg update first.
```shell
opkg update
```

2. Select you version.

   **kamikaze**
   ```shell
   opkg install http://auto-truewifi-router-ipkg.herokuapp.com/packages/kamikaze/truewifi_1-1_all.ipk
   ```
   **backfire**
   ```shell
   opkg install http://auto-truewifi-router-ipkg.herokuapp.com/packages/backfire/truewifi_1-1_all.ipk
   ```
   **attitude_adjustment**
   ```shell
   opkg install http://auto-truewifi-router-ipkg.herokuapp.com/packages/attitude_adjustment/truewifi_1-1_all.ipk
   ```

3. Insert the username and password in file truecond.
```shell
vi /usr/bin/truecond
```

4. Finally reboot router.
```shell
reboot
```

**have fun :)**
