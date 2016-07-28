Kibana init script 
=============================

An init.d shell script that provides start, stop and status commands.


Getting started
---------------

* Copy kibana to /etc/init.d 
* Edit the script and enter the path of kibana "PROG_LOCATION":_


Script usage
------------

### Start ###

Starts Kibana.

    sudo service kibana start

### Stop ###

Stops Kibana.

    sudo service kibana stop

### Status ###

Tells you whether the app is running.

    sudo service kibana status

Logging
-------

* By default, standard output goes to /var/log/kibana.log. 
* Change the variables `LOG_DIR` and `LOG_FILE` if you want a custom location.

License
-------

Copyright (C) 2016 Ehab Al Hakawati

This is open source software, licensed under the MIT License. See the
file LICENSE for details.