# ABR Video Proxy Project

This is a CDN video playing proxy using ABR algorithm to determine bitrate for forwarding.

To Start video server:

```
sudo ./netsim.py ../topos/topo1 start
```



To start the proxy:

```
python proxy.py log1.txt 0.3 8001 1.0.0.1 4.0.0.1
```



To start playing video:

Point browser to proxyServerIp:8001

