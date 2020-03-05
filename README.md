# srv_sync
Synchronizes directories to local or remote locations (with rsync). Able to tackle unstable connections and using timetables.


################################ srv_sync help ################################

Synchronizes directories within two systems in a timed manner

Relies on being executed by cron or other job timing daemons in a regularfashion, like every 5 minutes.


How to use:
  srv_sync [path_to_config]    Uses the config file to set parameters like log file, PID files and job config file to use
  srv_sync [--help|-h|help]    Display this help.
