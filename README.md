# parse-ut60e
Parse RS-232 output from Uni-T UT60E DMM

# What does parse-ut60e do

`parse-ut60e` prints RS-232 readings from the UT60E DMM.

The meter has a cable that can be connected to a serial port. Then you can use `parse-ut60e` to print meter readings to stdout.

# How to use it

1. Compile `parse-ut60e`:
    $ cc -o parse-ut60e parse-ut60e.c

2. Plug the cable into a serial port

3. Run:
    $ ./parse-ut60e -f /dev/tty-something

# More information

https://perfec.to/posts/ut60e/

# TODO

* man page
* usage examples
