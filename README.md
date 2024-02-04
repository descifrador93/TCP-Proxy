
# TCP Proxy in Python

A simple TCP proxy implemented in Python that allows you to intercept and modify TCP traffic between a client and a server.


## Usage
- Make sure you have Python installed on your system.

- Example: Fire up the Proxy using following command.

```shell
tim@kali: sudo python proxy.py 192.168.1.203 21
ftp.sun.ac.za 21 True
```

- Now launch any FTP client and set it to use localhost and port 21 as its remote host and port.

- In another terminal on the Kali machine, start an FTP session to the Kali machine's IP address using the default port, 21:

```shell
tim@kali:$ ftp 192.168.1.203
```
You will get amazing results after that.
