# TFTP
Basic TFTP Implementation in C language.

To run the TFTP:
```
gcc my_tftp.c -o my_tftp
./tftp 127.0.0.1
```

It will show a tftp prompt:
```
moy_tftp >
```
To know about its workings, use help:
```
moy_tftp > help
SIMPLE TFTP Client

Implementation by @moynakbag


**USAGE**
The available commands are as follows. They all have their usual meainings.
put <filename>
get <filename>
quit
help
```
