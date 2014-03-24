keylogger
=========

Linux kernel level keylogger.

To build:
>make

To install the keylogger module:
>sudo insmod keylogger.ko

Test whether the module is loaded:
>lsmod | grep "keylogger"

Test whether the logging is happening:
>cat /var/log/kern.log
The log file will show the keystrokes logged after the module has been loaded.

To uninstall the keylogger module:
>sudo rmmod keylogger

