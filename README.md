# IPCmediaServer
Video file server created based on solutions proposed by [ant-thomas](https://github.com/ant-thomas/zsgx1hacks).

A few days ago I bought SMARTROL ZX-C23 camera on one of the Chinese portals and I missed the function of viewing video recordings directly from SD card. The whole trick is to swap several files, including uploading a newer version of the busybox, which has an HTTPD server.

Connection to the server is possible at http://IP:8080/cgi-bin/webui - where IP is the camera address assigned by the router.

All video traffic **is not transmitted** through external servers! However, I use several CDNs (Content Delivery Network) from where I get resources like jQuery or FontAwesome.

That's how it looks:

**Live view**:
![IPCmediaServer live view](https://raw.githubusercontent.com/JG24/IPCmediaServer/master/docs/IPCmediaServer-live.png)

**Playback**:
![IPCmediaServer playback](https://raw.githubusercontent.com/JG24/IPCmediaServer/master/docs/IPCmediaServer-playback.png)

The site is responsive and can be successfully viewed on smartphones.
