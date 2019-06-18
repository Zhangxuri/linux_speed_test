# linux_speed_test
To test ipv4 and ipv6 speed in linux.
## Install 
```
wget https://raw.githubusercontent.com/Zhangxuri/linux_speed_test/master/bench.sh && bash bench.sh
```
## Result
```bash
----------------------------------------------------------------------
CPU model            : Intel(R) Core(TM) i9-7900X CPU @ 3.30GHz
Number of cores      : 20
CPU frequency        : 1586.578 MHz
Total size of Disk   : 4573.5 GB (3921.4 GB Used)
Total amount of Mem  : 128604 MB (2191 MB Used)
Total amount of Swap : 31127 MB (16 MB Used)
System uptime        : 6 days, 23 hour 55 min
Load average         : 4.98, 4.92, 5.12
OS                   : Ubuntu 16.04.6 LTS
Arch                 : x86_64 (64 Bit)
Kernel               : 4.4.0-142-generic
----------------------------------------------------------------------
I/O speed(1st run)   : 263 MB/s
I/O speed(2nd run)   : 203 MB/s
I/O speed(3rd run)   : 288 MB/s
Average I/O speed    : 251.3 MB/s
----------------------------------------------------------------------
Node Name                       IPv4 address            Download Speed
Wechet                          223.99.231.155          2.36MB/s
----------------------------------------------------------------------
Node Name                       IPv6 address            Download Speed
Tinghua                         2402:f000:1:408:8100::1 22.8MB/s
----------------------------------------------------------------------
```
