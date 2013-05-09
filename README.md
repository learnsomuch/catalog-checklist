catalog-checklist
=================

Information gathering before troubleshooting in linux flavours. This script suggests a list of important Items which helps a lot to understand the current state of a server environment.

Checklist categories:

~ Who is there ?  { w, last, lastlog, whoami }
  
~ Programs executed ?  { history }

~ Programs running ?  { ps -ef / ps aux , pstree -a }

~ Services listening ?  { netstat }

~ CPU, RAM, Hardware { /proc/cpuinfo, free -m, lspci, dmidecode, ethtool }

~ IO performances, Mount point and file systems { iostat, vmstat, mpstat, mount, df -h }

~ Kernel, network { sysctl, netstat, route } 

~ logs { system logs, Application logs if any }

~ cronjobs { crontab -l }


Suggestions 
===========

Please suggest if anything in the above list is missing. email to sankar(at)learnsomuch.com . Also if any one interested to contribute, you are most welcome :-)
