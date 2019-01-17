#Linux boot sequence

```
BIOS -> Boot sector -> The Linux kernel -> RAM disk -> initialisation system
```

* **dmesg** - the traditional utility used for viewing the kernel ring buffer

* **journalctl -k** - Systemd utility to view the kernel ring buffer within the systemd jounal


* **Init** - Short for initialisation. Services are started one after the other , in a serial fashion

* **upstart** - Upstart is an event-based replacement for the */sbin/init* daemon which handles starting of tasks and services during boot, stopping them during shutdown and supervising them while the system is running.


