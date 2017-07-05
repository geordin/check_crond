# check_crond

"check_crond" is a nagios plugin to check the status of crond service.

This plugin is written in bash.

Since the service management is in a different we need to use differet plugins for Centos7.x servers and Cenros6.x servers.

For checking the remote servers, the plugin need to be used in conjunction with the nrpe service.

Regarding the service status, check_crond will give the results OK, CRITICAL, UNKNOWN etc.

    OK - Running fine

    CRITICAL - Stopped or dead

    Unknown - Unknown status
