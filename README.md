# bmc-pcap
Dump for Supermicro iKVM BMC pcap tests

To contribute, please note the specific motherboard, the BMC firmware version number, and whether the test was a success or failure.

Example
```
# tcpdump -ni eth0 -s 0 host 1.1.1.1 -w X10DRW-E_1.81.pcap
```
