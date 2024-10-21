# Simple Network Monitor

The Simple Network Monitor (SNM) is a small service to monitor other hosts or network devices. It checks cyclic the availability of certain services. The SNM saves all probes in a database and creates charts out of it.

## How to run

In all cases the application will be available under http://localhost:8080/, it is possible to access the application from outside by replacing localhost with your hostname or IP address.

Requirements:
* Java 8
* [Monitor Plugins](https://www.monitoring-plugins.org) must be available in the PATH
* [nmap](https://nmap.org) must be available in the PATH
