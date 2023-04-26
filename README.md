# IdleScan
In this command, the following options are used:

-sI: Specifies an idle scan, which uses a zombie host to disguise the true source of the scan.
zombie_ip_address: Specifies the IP address of the zombie host to use for the scan.
-p 1-65535: Specifies the range of ports to scan.
--data-length 4: Specifies the length of the probe packets to send.
--scan-delay 10: Specifies the delay between probe packets, in milliseconds.
-oA: Specifies the output format as three different file types (normal, XML, and grepable) with the same base name.
scan_results: Specifies the base name for the output files.
target_ip_address: Specifies the IP address of the target to scan.
This scan will perform an idle scan using a zombie host to disguise the true source of the scan. The scan will probe all ports in the range of 1-65535 with packets that have a length of 4 bytes and a delay of 10 milliseconds between probes. The output will be saved in three different file types (normal, XML, and grepable) with the base name scan_results.

Note that the idle scan is a complex and advanced scanning technique that requires a deep understanding of network protocols and TCP/IP stack behavior.
