Nginx Reverse Proxy 
============================

> Basic nginx reverser proxy implementation using docker, load balancing three nginx http servers.

### A top-level directory layout

├─ reverse-proxy
│  	├─ Dockerfile
│	└─ nginx.conf
│ 
├─ server1
│	└─ index.html
│ 
├─ server2
│ 	└─ index.html
│ 	
├─ server3
│ 	└─ index.html
│ 	
├─ compose.yaml
│
└─ README.md
