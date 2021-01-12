# Raspberry image viewer

## Install

```bash
sudo apt-get install usbmount
```

Edit `/lib/systemd/system/systemd-udevd.service` and replace `PrivateMounts=yes` by `PrivateMounts=no`
