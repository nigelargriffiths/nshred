# nshred
Shredding your disks to remove all data for security via a small C program

If you are repurposing a computer or giving it to some one else, then you want to ensure you remove all data from the disks. 
Removing the files does not remove the file content and special scanning devices can even detect previous data recorded on the disks.

An AIX computer with internal or remote disk drawer "real brown spinning" disks. 

Updated: This tool does not apply to Fibre Channel SAN disk LUNs, high function disk subsystem, SSP, or solid-state drives (SSD). 
These devices might not destroy your data that uses multiple writes due to advanced technique including snapshots, de-duplication, 
remote asynchronous mirrors, remapping on write for wear-levelling and blocks are scattered across many drives.
