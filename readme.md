Daemon
======

Daemon detaches from the controlling terminal and runs the given 
commands.  This program is a reimplementation of a program available on
[M-Net] (http://www.arbornet.org) in 1998.  At the time, M-Net ran BSD/OS 3.1 
and was used to start programs that would be "more immune" to SIGHUP
than a simple nohup(1) would permit.
