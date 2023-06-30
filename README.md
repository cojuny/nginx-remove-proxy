Nginx Reverse Proxy 
============================

> Basic nginx reverser proxy implementation using docker, load balancing three nginx http servers.

### The directory layout

	.
	├─ reverse-proxy 
	│  	├─ Dockerfile
	│		└─ nginx.conf
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

 ### How to run:
 
1. Install [Docker Engine](https://docs.docker.com/engine/install/).
2. Install [Docker Compose V2 plugins](https://docs.docker.com/compose/migrate/).
3. Locate to the directory.
4. Run the following:
```console
docker compose up -d
```
 5. Visit and view the content in following url:
```console
http://localhost
```
   




