# Login accounting

More info in `utmp(5)`.

**/var/run/utmp** - currently logged-in users
**/var/log/wtmp** - record of all logins and logouts

## Bugs

`file` chokes on reading `utmp`/`wtmp`.
