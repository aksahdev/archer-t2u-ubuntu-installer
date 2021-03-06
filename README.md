
# Archer T2U Ubuntu installer

Installation:

* You should have python3 installed.

```bash
$ git clone https://github.com/ivannieto/archer-t2u-ubuntu-installer.git
$ cd archer-t2u-ubuntu-installer/ && python3 t2u-driver-installer.py
```

This script installs the driver for Archer T2U USB Wi-Fi adapter patched by:

* [chenhaiq](https://github.com/chenhaiq)
* [mt7610u_wifi_sta_v3002_dpo_20130916](https://github.com/chenhaiq/mt7610u_wifi_sta_v3002_dpo_20130916).

It works on systems using Ubuntu <=17.10.

For more info configuring the adapter please refer to [CONFIGURATION.md](https://github.com/ivannieto/archer-t2u-ubuntu-installer/blob/master/CONFIGURATION.md).

Also reading the [README.md](https://github.com/ivannieto/archer-t2u-ubuntu-installer/blob/master/driver-files/README.md) included in `driver-files` will solve some possible runtime errors.

Just follow the instructions from the program prompt.

## **Restart your computer when the installation is finished**

Once you had restarted, you can enable or disable the driver. Plug your USB dongle and run:

```bash
$ sudo t2u-driver
```

## Removing t2u-driver from the system

To uninstall t2u-driver type:

```bash
$ sudo uninstall-t2u-driver
```
