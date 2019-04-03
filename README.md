# dynamic-load-balancer
A sample load balancer with consul service registry implemented in nodejs 
1. consul agent -dev
2. forever start index.js api-service && forever start index.js api-service && forever start index.js api-service && forever start index.js web-service
3. start loadBanncer.js
4. curl localhost:8080/api
5. curl localhost:8080/web


# Notice change of pid for response
