# dns scanner for saddam
Note this code is not mind... i will be adding more options in the future.

# Requierments
 * pthread.h (sys lib)
 * stropts.h (sys lib)
 * gcc
 
# compile: 
  * gcc main.c -pthread -o DNSAmpScanner
  
# usage 
```
./DNSAmpScanner <ip class start> <ip class end> <outfile> <threads> <scan delay in ms>
```
