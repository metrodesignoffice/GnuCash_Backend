Database Back-end Server for GnuCash on a LAN or WAN
Database Set-Up

Set up the database and then use the mysql client on another (test) system to make sure you can access the DB -- before you try to connect GnUCash.

For Linux Clients:

Get the DB fully set up and functional, and THEN you can install the dbi mysql dbd drivers and then connect GnuCash to the MySQL via the correct URI.  (/THAT/ should be in the GnuCash docs/wiki).

Other Client Systems:

The client systems will likely vary a bit, incorporating clients like mine, fedora and windows vms, maybe a few other distros?  Maybe the odd Hackintosh?

Different clients may have different requirements for getting the sql connectors working.  YMMV.
