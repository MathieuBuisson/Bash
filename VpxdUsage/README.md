##Description :

This script extract vCenter Server resource utilization from the vpxd-profiler logs in a vCenter log bundle.

It extracts the following information :
* Duration covered by the specified vpxd-profiler logs
* Minimum CPU usage
* Maximum CPU usage
* Minimum virtual memory usage
* Maximum virtual memory usage
* Minimum physical memory usage
* Maximum physical memory usage
* Average virtual memory growth
* Average physical memory growth


###Parameters :

It takes a single argument : The path to the vpxd-profiler log(s) to examine. You can specify more than one log file by using wildcards.