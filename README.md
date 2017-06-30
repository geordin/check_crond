# check_crond

"check_crond" is a nagios plugin to check the status of crond service.

This plugin is written in bash and is compatible only with Centos7 or later.

For checking the remote servers, the plugin is need to be used in conjuction with the nrpe service.

According to the service status, check_crond will give the results OK, CRITICAL, UNKNOWN etc.

OK - Running fine

CRITICAL - Stopped or dead

Unknown - Unknown status
