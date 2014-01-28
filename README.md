Syslog_to_Bro
=============

Syslog listener to Broccoli

The goal here is to listen to UDP syslog messages and send them
directiony into Bro using the Broccoli API.  Avoid having to tail flat
log files.

Borrowed heavily from:

https://gist.github.com/marcelom/4218010
https://github.com/jsiwek/sshd_audit_mux/blob/master/sshd_audit_mux.py  


