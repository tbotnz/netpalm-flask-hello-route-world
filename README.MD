# netpalm-flask-hello-route-world
simple hello world app to pull route table off multiple devices and render into a nice searchable datatable

![netpalm route table](/netpalm_route.gif)

### getting started
- build a [netpalm](https://github.com/tbotnz/netpalm) instance and load the ```ip_route_service.j2``` service template via the API or at build
- git clone the project ``` git clone https://github.com/tbotnz/netpalm-flask-hello-route-world.git && cd netpalm-flask-hello-route-world ```
- update the app.py with your ```NETPALM_SERVER_IP``` ```NETPALM_SERVER_PORT``` ```NETPALM_API_KEY```
- install the requirements ```pip3 install -r requirements.txt```
- run the app ```python3 app.py```
