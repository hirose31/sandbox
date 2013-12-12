# NAME

__monitor-elb-address__ - check IP addresses of ELB periodically and notifies us when changed

# QUICKSTART

    cpanm -l local --installdeps .
    cp config-sample.pl config.pl
    vi config.pl
    ./monitor-elb-address -c ./config.pl

# SYNOPSIS

__monitor-elb-address__
__\-c__ _config\_file_
\[__\-i__ _interval_\]
\[__\-d__ | __\--debug__\]

config\_file

__monitor-elb-address__
__\-c__ _config_file_
\[__\-i__ _interval_\]
\[__\-d__ | __\--debug__\]

config_file

__monitor-elb-address__ __\-h__ | __\--help__ | __\-?__

    $ monitor-elb-address -c ./config.pl

# DESCRIPTION

This script checks IP addresses of ELB periodically and notifies us when changed.

# OPTIONS

- __\-c__ _config\_file_, __\--config__ _config\_file_

    Specify a config file path. This option is mandatory.

- __\-i__ _interval_, __\--interval__ _interval_

    Specify monitoring loop interval time by seconds. Default is 60 (seconds).

- __\-d__, __\--debug__

    increase debug level.
    \-d -d more verbosely.

# AUTHOR

HIROSE Masaaki <hirose31@gmail.com>
