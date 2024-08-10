# uapt-get
user mode `apt-get`

Allow a user to install and run software without root privileges.
Don't depend on a working system `sources.list` .. yuck

You'll want to add ~/install/usr/bin/ to your `$PATH` (and maybe the bin,
sbin, usr/sbin, usr/games as well).
Don't forget to also add ~/install/usr/lib to your `$LD_LIBRARY_PATH`,
maybe also set `$MANPATH`.

alex@aiei.ch

`/var/tmp` is a place where everyone can write and the stuff stays after
a reboot. crontab using @reboot with some process in `screen` might be
useful
