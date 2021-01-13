# Raspberry image viewer

## Install

```bash
sudo apt-get install usbmount fbi
```

Edit `/lib/systemd/system/systemd-udevd.service` and replace `PrivateMounts=yes` by `PrivateMounts=no`

Add in the end of `~/.bashrc`:
```bash
./start.sh
```
