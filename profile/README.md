## Weiterleiter

Weiterleiter is a PoC (at the moment) TCP forwarder (planning in future to extend a list of protocols to UDP and HTTP, too). Its purpose is to forward data from reserved for some local application port, to the actual local application. This may be handy in cases, 
when there's no public IP address available for local application, or you want to protect it at L4 level. Maybe, in future this project may also become a L4 balancer.
