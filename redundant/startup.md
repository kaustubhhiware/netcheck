If you wish to run this indicator at startup, here is a list of things I tried and failed :
* used `netcheck.conf` & .sh and place it in `/etc/init` folder.
* setting up a cron job with `@reboot`
* basic startup applications gui
* upstart
* .desktop file

If any of the above work for you,let me know. Check your `/var/lib/syslog` for debugging.
