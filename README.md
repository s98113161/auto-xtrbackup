# auto-xtrabackup
this shell helped you automatic backup mysql database by xtrabackup.

make sure u already install Percona XtraBackup, then you can just put file into below folder and grant executble permission(chmod):
```sh
/usr/local/bin/
```
and you can full backup by this command 
```sh
umbackup -b full
```
and incremental backup
```sh
umbackup -b inc
```
those backup file will create at 
```sh
/data/backups/
```

and you can execute frequency by add to crontab.
more crontab detail as follow:
https://www.computerhope.com/unix/ucrontab.htm
