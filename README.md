# data_center_explorer
A python program that uses SNMP to explore a data center


This program uses SNMP to explore a data center.  It goes through each machine that it can, gets the TCP
connection table, and uses that to find more machines.  As it visits each machine, it lists lots of useful
things about that machine.

This program assumes that it has readonly SNMP access rights to all of the computers in the data center.


