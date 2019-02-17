##RUN

$ docker-compose up

###Endpoint for monitoring
:8090/nginx_status returns the metrics of Nginx.

$ curl localhost:8090/nginx_status
Active connections: 1
server accepts handled requests
 8 8 8
Reading: 0 Writing: 1 Waiting: 0


#Environment variables

|Key	          |Descriptio
| ------------- | ------------- |
|BASIC_AUTH_USERNAME  |Basic auth username  |
| BASIC_AUTH_PASSWORD |Basic auth password  |
| PROXY_PASS          |Proxy destination URL
