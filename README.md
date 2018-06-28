# RDSSkeletonKey
RDSSkeletonKey is a python port of Stanley Sixteens RDS enumeration tool
I'd like to announce the availability of a free security reconnaissance /
RDS. This tool enables the user to scan for vulnerable RDS instances on AWS environments using a defined RDS protocol.

Amazon RDS is available on several database instance types - optimized for memory, performance or I/O - and provides 
you with six familiar database engines to choose from, including Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle, and 
Microsoft SQL Server. 

You can use the AWS Database Migration Service to easily migrate or replicate your existing databases to Amazon RDS.

The important benefit of using an established connection and matching TCP
packets to send a TTL-based probe is that such traffic is happily allowed
through by many stateful firewalls and other defenses without further
inspection (since it is related to an entry in the connection table).

Dependencies

    dnet
    dpkt
    pypcap

Download

    RDSSkeletonKey - released January 25st, 2017

Example Run

    Starting RDSSkeletonKey.py -  1.1.1.1
 
[+] Waiting for traffic from target on eth0...
[+] Traffic acquired, waiting for a gap...
[+] Target acquired: 1.1.1.1
[+] Setting up a sniffer...
[+] Sending probes...

TRACE RESULTS
-------------
Scanning RDS Target 1.1.1.1
[+] RDS service open, unauthenticated RDS found.
[+] RDS service name: kermit:98010119
