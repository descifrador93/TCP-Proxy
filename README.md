
# TCP Proxy in Python

A simple TCP proxy implemented in Python that allows you to intercept and modify TCP traffic between a client and a server.


## Usage
- Make sure you have Python installed on your system.

- Run the proxy server by executing the following command:

```shell
python proxy.py [localhost] [localport] [remotehost] [remoteport] [receive_first]
```


Replace `[localhost]`, `[localport]`, `[remotehost]`, `[remoteport]`, and `[receive_first]` with the appropriate values.


## Parameters

- `[localhost]`: The local address the proxy will bind to.
- `[localport]`: The local port the proxy will listen on.
- `[remotehost]`: The remote host the proxy will forward traffic to.
- `[remoteport]`: The remote port the proxy will forward traffic to.
- `[receive_first]`: Whether the proxy should wait for data from the remote host before sending to the client (True/False).

