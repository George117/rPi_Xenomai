# [Documentation](https://source.denx.de/Xenomai/xenomai/-/wikis/Building_Applications_For_Xenomai_3)
### 1. Add xeno dynamic libraries path to dynamic linker

1.1
```
 cd /etc/ld.so.conf.d
```

Create the file ``xeno.conf``
```
sudo nano xeno.conf
```
Add the following two lines and save the file
```bash
# xeno dynamic libs path
/usr/xenomai/lib/
```

Reboot the rPi

Run to check if the xeno libs bindings are availabe
```
 sudo ldconfig -v
```

![bindings](assets/images/4/xeno_libs_bindings.png)
