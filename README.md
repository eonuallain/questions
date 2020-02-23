# questions

What is the DNS protocol?
<br />https://ns1.com/resources/dns-protocol

Linux system calls
<br />http://man7.org/linux/man-pages/man2/syscalls.2.html

How to debug system calls
<br />https://www.tecmint.com/strace-commands-for-troubleshooting-and-debugging-linux/

Socket states
<br />https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/include/net/tcp_states.h?id=HEAD
```
       ESTABLISHED
              The socket has an established connection.

       SYN_SENT
              The socket is actively attempting to establish a connection.

       SYN_RECV
              A connection request has been received from the network.

       FIN_WAIT1
              The socket is closed, and the connection is shutting down.

       FIN_WAIT2
              Connection is closed, and the socket is waiting for a shutdown from the remote end.

       TIME_WAIT
              The socket is waiting after close to handle packets still in the network.

       CLOSE  The socket is not being used.

       CLOSE_WAIT
              The remote end has shut down, waiting for the socket to close.

       LAST_ACK
              The remote end has shut down, and the socket is closed. Waiting for acknowledgement.

       LISTEN The socket is listening for incoming connections.  Such sockets are not included in the output unless you spec‐
              ify the --listening (-l) or --all (-a) option.

       CLOSING
              Both sockets are shut down but we still don't have all our data sent.

       UNKNOWN
              The state of the socket is unknown
```              
