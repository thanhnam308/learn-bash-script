# Linux Filesystem Hierarchy
We can `cd` to any of dirs below from anywhere.
```
/
├── bin
├── boot
├── dev
├── etc
├── home
├── lib
├── media
├── mnt
├── opt
├── root
├── sbin
├── srv
├── tmp
├── usr
│   ├── bin
│   ├── include
│   ├── lib
│   └── sbin
└── var
    ├── cache
    ├── log
    ├── spool
    └── tmp
```
Details of some remarkables directories:
|<div style="text-align:center">Directory name</div>|<div style="text-align:center">Description</div>|
|:-:|-|
|`/`|This is the top level directory.<br>Parent dir for all other dirs.<br>Called as ROOT directory.<br>Represented by forward slash (/).<br>It's equivalent to `C:\` in Windows.|
|`/root`|This is home directory for root user (super user).<br>Provides working evironment for root user.<br>It's equivalent to `C:\Documents and Settings\Administrator` in Windows.|
|`/home`|This is home directory for other users.<br>Provide working environment for other users (other than root).<br>It's equivalent to `C:\Documents and Settings\username` in Windows.|
|`/usr`|By default softwares are installed in `/usr` directory (UNIX Sharable Resources).<br>It's equivalent to `C:\Program Files` in Windows.|
|`/bin`|Contains commands used by all users (binary files).|
|`/sbin`|Contains commands used by only super user (root user's binary files).|
|`/var`|Contains variables data like mails, log files,...|
|`/boot`|Where the Linux kernel is located<br>We may need to use this dir if using more different types of kenels.|
|`/mnt`<br>`/cdrom`<br>`/floppy`|This is where external devices filesystems located.|
|`/lib`|Place to store library files.|
|`/tmp`|Place to store temporary files.|
