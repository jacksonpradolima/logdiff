# Logdiff

Logdiff is a tool for identifying patterns and changes in log files.

    Usage: logdiff [options] file

    Options:
      -h, --help  show this help message and exit
      -n N        Set similarity threshold (default 0.75)

Often, you'll want to be able to page the output of logdiff. The best tool for this is `less` with the "raw colours" option enabled.

e.g. `logdiff mylog.log | less -r`
