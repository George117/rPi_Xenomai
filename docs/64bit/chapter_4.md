# [Documentation](https://source.denx.de/Xenomai/xenomai/-/wikis/Building_Applications_For_Xenomai_3)
### 1. Add xeno dynamic libraries path to dynamic linker

```
 cd /etc/ld.so.conf.d
```

Create the file ``xeno.conf``
```
sudo nano xeno.conf
```
Add the following two lines and save the files
```bash
# xeno dynamic libs path
/usr/xenomai/lib/
```


